# 🧠 IBM Employee Attrition Prediction (Complete Version)

This project analyzes IBM HR data to predict employee attrition using data preprocessing, visualization, and machine learning.

## 📊 Dataset

- **Source**: [Kaggle - IBM HR Attrition](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- **File**: WA_Fn-UseC_-HR-Employee-Attrition.csv
- Download and place it in the `data/` folder.

## 🛠 Workflow

1. Load and clean data
2. Encode categorical columns
3. Visualize with Seaborn (countplot, histplot, heatmap)
4. Scale features
5. Train a Random Forest model
6. Save model and scaler

## 📁 Structure

```
employee-attrition-complete/
├── data/
│   └── WA_Fn-UseC_-HR-Employee-Attrition.csv
├── models/
│   ├── attrition_model.pkl
│   ├── scaler.pkl
│   ├── attrition_distribution.png
│   ├── income_vs_attrition.png
│   ├── age_distribution.png
│   └── correlation_heatmap.png
├── train_model.py
├── README.md
└── requirements.txt
```
