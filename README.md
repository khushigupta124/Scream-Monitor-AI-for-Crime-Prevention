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

<h3>1. Selecting an Audio File</h3>
<p>The user selects an audio file for detection.</p>
<p align="center">
  <img src="https://github.com/khushigupta124/Scream-Monitor-AI-for-Crime-Prevention/blob/main/kivy%20output%202.png?raw=true" width="500">
</p>

<h3>2. Scream Detection Result</h3>
<p>After clicking the <b>"Detect Scream"</b> button, the system analyzes the audio file. The model detected a <b>scream sound</b> and classified it as <b>HIGH RISK</b>.</p>
<p align="center">
  <img src="https://github.com/khushigupta124/Scream-Monitor-AI-for-Crime-Prevention/blob/main/kivy%20output%201.png?raw=true" width="500">
</p>

