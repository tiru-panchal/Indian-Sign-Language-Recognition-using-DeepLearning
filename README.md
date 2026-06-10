# Deep Learning Based Indian Sign Language Recognition for Static and Dynamic Gestures

## Overview

This project presents a Deep Learning-based Indian Sign Language (ISL) Recognition System designed to bridge the communication gap between hearing-impaired individuals and non-sign language users. The system recognizes both static and dynamic ISL gestures using Computer Vision and Deep Learning techniques.

The project implements MobileNetV2-based transfer learning models for static gesture recognition (Digits 0–9 and Alphabets A–Z) and a CNN-LSTM architecture for dynamic gesture recognition of common greetings and words.

---

## Features

* Real-time Indian Sign Language Recognition
* Static Gesture Recognition (Digits and Alphabets)
* Dynamic Gesture Recognition using Video Sequences
* Transfer Learning with MobileNetV2
* CNN-LSTM Model for Sequential Gesture Classification
* Real-time Webcam-Based Prediction
* Performance Evaluation using Accuracy, Confusion Matrix, and Classification Reports

---

## Technologies Used

* Python
* TensorFlow
* Keras
* OpenCV
* MediaPipe
* NumPy
* Pandas
* Scikit-learn
* MobileNetV2
* CNN
* LSTM

---

## Project Architecture

### Static Gesture Recognition

* Digit Recognition (0–9)
* Alphabet Recognition (A–Z)
* Image Preprocessing
* Data Augmentation
* Transfer Learning using MobileNetV2
* Real-time Prediction

### Dynamic Gesture Recognition

* Video Frame Extraction
* Sequence Generation
* CNN-Based Spatial Feature Extraction
* LSTM-Based Temporal Learning
* Dynamic Gesture Classification

---

## Dataset

The project uses Indian Sign Language gesture datasets consisting of:

### Static Gestures

* Digits (0–9)
* Alphabets (A–Z)

### Dynamic Gestures

* Hello
* Good Morning
* Good Afternoon
* Good Evening
* Good Night
* Thank You
* Happy
* Family
* Food
* House
* Yes
* No
* Easy
* Difficult
* Strong
* Child
* Boy
* Girl
* And other commonly used ISL gestures

---

## Model Performance

| Model                       | Accuracy |
| --------------------------- | -------- |
| Digit Recognition           | 84%      |
| Alphabet Recognition        | 90%      |
| Dynamic Gesture Recognition | 92%      |

---

## Project Workflow

1. Data Collection
2. Data Preprocessing
3. Data Augmentation
4. Feature Extraction
5. Model Training
6. Model Evaluation
7. Real-Time Prediction
8. Performance Analysis

---

## Results

The developed system successfully recognizes Indian Sign Language gestures in real time and demonstrates strong performance for both static and dynamic gesture classification tasks. The system was tested under different lighting conditions and with multiple users to ensure robustness.

---

## Future Enhancements

* Speech Synthesis Integration
* Text-to-Sign Conversion
* Sentence-Level Gesture Recognition
* Transformer-Based Models
* Mobile Application Deployment
* Cloud Deployment using AWS
* Real-Time Assistive Communication Platform

---

## Repository Structure

```text
Indian-Sign-Language-Recognition/
│
├── dataset/
├── models/
├── notebooks/
├── src/
├── screenshots/
├── requirements.txt
├── README.md
└── .gitignore
```

---

## Author

Tirumala Panchal

M.Sc. Data Science

GitHub: https://github.com/tiru-panchal
