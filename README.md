# CodeAlpha_Emotion-Recognition-from-Speech
# 🎧 Emotion Recognition from Speech using TESS Dataset

This project uses deep learning (CNN) and MFCC audio features to recognize emotions in speech based on the [TESS dataset](https://www.openslr.org/107).

## 📂 Dataset

Please download the TESS dataset and place it in the project root directory under the folder named `TESS/`.

## 🧠 Model

- Extracts MFCCs from `.wav` files
- Trains a CNN to classify emotions like happy, sad, angry, etc.
- Can test custom `.wav` files

## 🧪 Run Predictions

```bash
python predict_single.py path/to/your_audio.wav
