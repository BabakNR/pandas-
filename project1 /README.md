# SleepSense: Sleep Quality Analysis and Prediction 💤

This Jupyter notebook analyzes wearable sensor data to predict sleep quality using **Pandas**, **NumPy**, and **Scikit-learn**.

## 📊 Overview

This project includes:
- Generation of a synthetic dataset (`1000` rows) simulating real-world sleep patterns.
- Data preprocessing (cleaning and feature engineering).
- Exploratory data analysis (correlations, statistical summaries).
- Predicting sleep quality using **Logistic Regression**.

## 📁 Dataset

The dataset is saved to `data/sleep_data.csv` and includes:

| Column          | Description                                         |
|-----------------|-----------------------------------------------------|
| timestamp       | Date and time of the record                         |
| heart_rate      | Heart rate in beats per minute (float, 50–100)      |
| sleep_duration  | Sleep duration in hours (float, 4–9)                |
| body_movement   | Body movement intensity (float, 0–30)               |
| sleep_quality   | Sleep quality label (`good`, `average`, `poor`)     |

## ✅ Features

- **Daily average heart rate**
- **Normalized sleep duration**
- **Correlation matrix**
- **Sleep quality prediction**
- **Overall and test accuracy metrics**

## 🚀 How to Run

1. Clone the repository or download the `.ipynb` file.
2. Open the notebook using Jupyter:

```bash
jupyter notebook SleepSense.ipynb
