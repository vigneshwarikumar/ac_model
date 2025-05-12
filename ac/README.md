# End-to-End Speech Recognition Pipeline

## Project Overview

This project implements a complete **speech recognition pipeline** with components for signal processing, acoustic modeling, and performance evaluation. It addresses the challenge of accurate speech recognition in noisy environments using traditional and deep learning-based approaches.

## 📌 Problem Statement

Speech recognition systems struggle with background noise and require robust feature extraction and modeling. This project builds a pipeline that includes:

- Noise Reduction
- Feature Extraction (MFCCs, Pitch, Energy)
- Voice Activity Detection (VAD)
- Acoustic Modeling using:
  - Hidden Markov Models (HMMs)
  - Deep Learning (RNN/CNN)
- Evaluation using metrics like WER, Accuracy, Precision, Recall, F1-score, SNR

## 🔧 Technologies & Skills

- Python
- Signal Processing
- Machine Learning & Deep Learning
- Data Preprocessing
- Power BI for Dashboarding

## 📊 Use Cases

- Call Center Automation
- Accessibility Tools
- Voice Assistants
- Meeting Transcription
- Voice-Controlled IoT Devices

## 📁 Dataset

We used a large-scale corpus of read English speech from [LibriSpeech ASR corpus](https://www.openslr.org/12), including clean and noisy audio with aligned transcriptions and speaker metadata.

## 🧭 Project Pipeline

### 1. Data Collection and Cleaning
- Normalize, segment, and denoise audio data.

### 2. Feature Extraction
- MFCCs, pitch, energy features
- Apply VAD to isolate speech

### 3. Visualization
- Waveforms, spectrograms, feature distributions

### 4. Acoustic Modeling
- Train HMM models
- Train deep learning models (RNN/CNN)

### 5. Evaluation
- Word Error Rate (WER)
- Accuracy, Precision, Recall, F1-Score
- Signal-to-Noise Ratio (SNR)
- Latency & Training Time

### 6. Power BI Dashboard
- Model comparisons
- Feature insights
- Accuracy visualization

## 📈 Results

- Accurate speech recognition pipeline
- Comparison between HMM and Deep Learning models
- Visualization of model performance and features

## 📦 Deliverables

- Source Code
- Trained ASR Model
- Power BI Dashboard
- Project Report (EDA, methodology, results)
- Speech Recognition Pipeline Scripts

## 📅 Timeline

The project is to be completed in **10 days** from the assigned start date.

---

> **Note:** For more technical details, refer to the report or explore the individual components in the repository.
