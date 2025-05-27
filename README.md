# 🌪️ Extreme Weather Event Prediction using CNNs

## 📘 Overview

This project simulates and predicts extreme weather events using Convolutional Neural Networks (CNNs) trained on synthetic meteorological data. It demonstrates how deep learning can be used to classify spatial weather patterns based on sensor-like grid data.

## 🧪 What It Does

- Generates synthetic meteorological "image-like" data (e.g., temperature, pressure, wind)
- Labels samples as extreme or normal based on a predefined condition
- Trains a CNN to classify extreme weather events
- Evaluates model performance and exports synthetic data

## 📊 Input Features

- **Temperature**
- **Pressure**
- **Wind Speed**

Each feature is simulated over a 10×10 grid to mimic satellite or sensor readings.

## 🧰 Tools & Libraries

- Python
- NumPy, Pandas
- TensorFlow/Keras
- Scikit-learn
- Matplotlib (for visualization)

## 🚀 How to Run

1. **Install Dependencies**
   ```bash
   pip install numpy pandas tensorflow scikit-learn matplotlib
