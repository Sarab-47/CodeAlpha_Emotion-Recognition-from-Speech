# CodeAlpha_Emotion-Recognition-from-Speech
# 🎧 Emotion Recognition from Speech using TESS Dataset

This project uses deep learning (CNN) and MFCC audio features to recognize emotions in speech based on the [TESS dataset](https://www.openslr.org/107).

## 📂 Dataset

Please download the TESS dataset and place it in the project root directory under the folder named `TESS/`.

##📌 Features

✅ Speech-based emotion recognition  
✅ MFCC feature extraction  
✅ CNN-based classification model  
✅ Predict emotion from your own `.wav` audio file  
✅ Tested on [TESS Dataset](https://www.openslr.org/107


##⚙️ How It Works

1. Load `.wav` audio files from the TESS dataset
2. Extract **MFCC features** (Mel-frequency cepstral coefficients)
3. Train a **CNN** model on extracted features
4. Evaluate accuracy and test with custom audio


## 🧠 Model

- Extracts MFCCs from `.wav` files
- Trains a CNN to classify emotions like happy, sad, angry, etc.
- Can test custom `.wav` files

## 🧪 Run Predictions

```bash
python predict_single.py path/to/your_audio.wav
