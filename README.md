# Predictive Maintenance using LSTM Autoencoder

A machine learning system for **predictive maintenance, anomaly detection, and Remaining Useful Life (RUL) prediction** for industrial machines using time-series sensor data.

This project uses **LSTM Autoencoder networks** to learn normal behavior patterns of machine sensors and detect anomalies that may indicate potential machine failures.

---

## Project Overview

Modern industries rely on predictive maintenance to reduce downtime and avoid catastrophic machine failures. Traditional maintenance strategies like reactive or scheduled maintenance are inefficient.

This project implements a **data-driven predictive maintenance system** capable of:

• Detecting abnormal machine behavior  
• Predicting machine failure patterns  
• Estimating Remaining Useful Life (RUL)  

The model is trained using **sensor time-series data** from machine bearings and identifies anomalies using reconstruction error from an LSTM Autoencoder.

---

## Key Features

- Time-series sensor data processing
- LSTM Autoencoder architecture
- Anomaly detection using reconstruction loss
- Remaining Useful Life (RUL) estimation
- Data preprocessing and feature scaling
- Sliding window sequence generation
- Visualization of anomalies and predictions

---

## Dataset

The project uses the **IMS Bearing Dataset** which contains vibration sensor data from industrial bearings.

Dataset includes:

- Vibration signals
- Sensor measurements
- Time series machine condition data

Dataset file used in this repository:

