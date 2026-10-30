# Brain–Computer Interface (BCI): From EEG Signals to Prosthetic Control

A first-year university project (Electronics) that explains how an EEG-based Brain–Computer Interface works, from recording brain signals to controlling a prosthetic device.

## Overview

A Brain–Computer Interface (BCI) lets the brain communicate with an external device without muscle movement. This project covers the full BCI pipeline and the challenges facing the field.

**Pipeline:** EEG Recording → Preprocessing → Feature Extraction → Classification → Translation → Prosthetic Output

## Topics Covered

### 1. Signal Acquisition & Preprocessing

- EEG electrodes and the International 10–20 placement system (C3, Cz, C4 for motor imagery)
- Noise and artifact removal: band-pass filter (8–30 Hz), notch filter, ICA
- Segmentation into epochs

### 2. Feature Extraction Techniques

- Time-domain: statistical features, ERPs and P300
- Frequency-domain: Power Spectral Density, Autoregressive models
- Time-frequency: Wavelet Transform, STFT

### 3. Classification & Machine Learning

- Algorithms: LDA and SVM
- Evaluation: accuracy, k-fold cross-validation, confusion matrix

### 4. Translation & Prosthetic Control

- Discrete, proportional, and finger-level control
- Mapping EEG patterns to prosthetic commands
- Algorithms: threshold mapping, linear regression, EEGNet

### 5. Challenges, Limitations & Future Trends

- Invasive vs. semi-invasive vs. non-invasive BCIs
- Signal noise, neural drift, and "BCI illiteracy"
- Future: biocompatible hardware, generative AI decoders, neurorights and data privacy

## Files

- `electronics.pptx`: the full presentation

## What I Learned

- How EEG signals are recorded and cleaned
- How machine learning turns brain signals into commands
- The trade-offs between different types of BCIs

## Status

Completed as a course project.