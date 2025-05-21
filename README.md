# Scream Monitor: Human Scream Detection and Alert System

A machine learning-based system built to detect human screams from real-time microphone input or pre-recorded audio files. Designed to enhance public safety, this solution enables rapid alert generation in potential emergency or crime scenarios through real-time signal classification.

---

## Overview

This project integrates **AI**, **audio signal processing**, and **software engineering** to deliver a deployable, intelligent scream detection and alert system. Using **Mel Frequency Cepstral Coefficients (MFCCs)** and a trained neural network, it distinguishes scream sounds from non-scream audio, assigns risk levels, and visualizes predictions through an interactive user interface.

---

## Key Features

- **Real-Time Detection**  
  Live scream detection using a connected microphone.

- **Audio File Support**  
  Analyze pre-recorded `.wav` audio files for distress sounds.

- **Risk Classification System**  
  Dual-level risk indicator (e.g., **High Risk**, **Low Risk**) based on model confidence to reduce false positives.

- **Neural Network Model**  
  Built and trained on **MFCC features** extracted from a curated dataset of over **5,000 audio clips**.

- **Graphical User Interface (GUI)**  
  Built using **Kivy**, offering users an intuitive experience for testing audio samples.

---
## Model Performance Metrics

The neural network classifier was trained and evaluated on a labeled dataset of over **5,000 MFCC-based audio samples**. After preprocessing and model optimization, the following performance results were achieved:

- **Accuracy**: 88.24%  

- **ROC AUC Score**: 81.13%  

- **Precision**: 90.74%  
 
- **Recall (Sensitivity)**: 94.23%   

-  **F1 Score**: 92.45%  

These results validate the system’s effectiveness in recognizing distress signals with a high level of accuracy and reliability, while minimizing false positives.

---

## User Interface Snapshots


<h3>1. Selecting an Audio File</h3>
<p>The user selects an audio file for detection.</p>
<p align="center">
  <img src="https://github.com/khushigupta124/Scream-Monitor-AI-for-Crime-Prevention/blob/main/kivy%20output%201.png?raw=true" width="500">
</p>

<h3>2. Scream Detection Result</h3>
<p>After clicking the <b>"Detect Scream"</b> button, the system analyzes the audio file. The model detected a <b>scream sound</b> and classified it as <b>HIGH RISK</b>.</p>
<p align="center">
  <img src="https://github.com/khushigupta124/Scream-Monitor-AI-for-Crime-Prevention/blob/main/kivy%20output%202.png?raw=true" width="500">
</p>

---

## Planned Enhancements

- **SMS or Email Alerts**  
  Automated notifications upon detecting high-risk events.

- **GPS Integration**  
  Geotagging incidents using GPS data for location-aware alerts.

- **Cloud-based Monitoring**  
  Remote logging and dashboard for law enforcement or emergency services.

- **Edge Deployment**  
  Portable version for embedded devices like **Raspberry Pi** or **Android smartphones**.

---

