Speech Emotion Recognition (RAVDESS Dataset)

Overview
This project implements Speech Emotion Recognition (SER) using the RAVDESS dataset. Two deep learning models were trained and compared:
- CNN using Mel-Spectrograms
- Bi-LSTM using MFCC features

Both models predict:
- Emotion (8 classes)
- Intensity (normal / strong)

Project Files
- notebooks/ — Jupyter notebook with full code
- models/ — Saved trained weights (.pth files)
- report/ — Final project report (PDF)
- examples/ — Confusion matrices & sample outputs

Tasks Performed
- Dataset preprocessing
- Feature extraction (Mel-Spectrograms & MFCCs)
- CNN & LSTM model training
- Accuracy & loss curves
- Confusion matrices
- IoU scores
- Final model predictions

Dataset (RAVDESS)
Includes 24 actors with recordings across:
- 8 emotions
- 2 intensity levels

Dataset link:
https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio

Example Prediction
Emotion: 05 (angry)
Intensity: 02 (strong)

Author
Ateeb Chaudary
Machine Learning Final Project (22F-3155)
