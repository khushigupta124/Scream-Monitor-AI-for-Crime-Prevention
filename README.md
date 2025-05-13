# Human Scream Detection and Alert System 

A machine learning-based system designed to detect human screams in real-time or from audio files, enabling rapid alert generation and assisting in crime prevention or emergency response scenarios.

##  Overview

This project integrates **machine learning**, **audio signal processing**, and **software engineering** principles to develop a real-time scream detection system with alert capabilities. The system uses Mel Frequency Cepstral Coefficients (MFCCs) as features and a neural network for classification. The model predicts whether an audio sample contains a scream or non-scream, assigning a risk level based on its confidence.

-  **Real-Time Scream Detection** using microphone input.
-  **Audio File Detection** for pre-recorded samples.
-  **Risk Level Indication** based on model confidence.
-  **Neural Network Classifier** trained on MFCC features.
-  **Accuracy Report** of model predictions.
-  **User Interface** for easy interaction using Kivy.

## User Interface Screenshots

### 1. Selecting an Audio File
The user selects an audio file for detection.
![Select Audio File](https://github.com/khushigupta124/Scream-Monitor-AI-for-Crime-Prevention/blob/main/kivy%20output%202.png?raw=true)

### 2. Scream Detection Result
After clicking the **"Detect Scream"** button, the system analyzes the audio file. The model detected a **scream sound** and classified it as **HIGH RISK**.
![Scream Detected (High Risk)](https://github.com/khushigupta124/Scream-Monitor-AI-for-Crime-Prevention/blob/main/kivy%20output%201.png?raw=true)
