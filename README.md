# Footstep Audio Classification and Elderly Activity Monitoring

This repository contains two machine learning projects focused on signal data processing and real-time monitoring:

1. **Footstep Audio Classification**: A machine learning pipeline to classify footstep audio data and distinguish between two individuals.
2. **Elderly Activity Monitoring**: An analysis of PIR motion sensor data for monitoring elderly activity and ensuring safety with real-time alerts.

---

## Table of Contents

1. [Project Overview](#project-overview)
2. [Footstep Audio Classification](#footstep-audio-classification)
3. [Elderly Activity Monitoring](#elderly-activity-monitoring)
4. [Setup Instructions](#setup-instructions)
5. [Model Inference](#model-inference)
6. [Evaluation Metrics](#evaluation-metrics)
7. [Credits](#credits)

---

## **Project Overview**

This repository combines two critical applications:

1. **Footstep Audio Classification**: This project involves building a machine learning pipeline to classify footstep audio and differentiate between two individuals. It includes steps for preprocessing audio data, extracting features, and applying machine learning models.
2. **Elderly Activity Monitoring**: This project analyzes PIR motion sensor data to monitor the activity of an elderly person, providing real-time alerts when unusual patterns are detected.

---

## **Footstep Audio Classification**

**Objective**: To build a machine learning pipeline capable of classifying footstep audio files from two different individuals.

#### Approach:
- **Preprocessing**: Applied **high-pass filters**, **Spleeter** to separate voices, and normalized audio data.
- **Feature Extraction**: Extracted features like **MFCC**, **Stride**, and **Cadence** from the footstep audio.
- **Model**: 
  - Trained a **Random Forest** model for classification.
  - Implemented a **Convolutional Neural Network (CNN)** using **TensorFlow/Keras** for improved accuracy (After Data Augmentation).
- **Deployment**: Created a **Streamlit** app for real-time footstep classification where users upload **.wav** files.

---

## **Elderly Activity Monitoring**

**Objective**: To analyze PIR motion sensor data and create an alert system for monitoring elderly activity patterns.

#### Approach:
- **Data Cleaning**: Handled missing values, irrelevant columns, and time-format issues in the dataset.
- **Exploratory Data Analysis (EDA)**: Analyzed time-based patterns such as **motion frequency** and **location-based activity**.
- **Alerting System**: Developed thresholds for abnormal activity and inactivity, triggering real-time alerts to caregivers.
- **Health Monitoring**: Created a baseline routine to monitor changes in the elderly person's daily activities and alert caregivers about potential health risks.

---

## **Setup Instructions**

To run the project locally, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/username/Footstep-Audio-Classification-and-Elderly-Activity-Monitoring.git
