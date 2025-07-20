# 🧹 Data Cleaning Project - Customer Personality Analysis Dataset 🛍️

This project demonstrates a complete step-by-step data cleaning workflow on a real-world marketing dataset. The dataset contains various data types including numeric, categorical, dates, and email addresses (added synthetically). 📊📅📧

## Features ✨

- ✅ Load dataset with mixed data types  
- 📧 Add synthetic email column for demonstration  
- 🔍 Handle missing values (detect and drop rows with missing data)  
- 🧩 Detect and remove duplicate rows  
- 🚫 Detect and remove outliers from numeric columns using IQR method  
- 🗓️ Convert date columns to datetime format  
- ✔️ Validate and clean email addresses  
- 📝 Standardize text columns (lowercase, strip whitespace)  
- 💾 Save cleaned dataset to CSV  

## Dataset 📂

The original dataset used is the **"Customer Personality Analysis"** marketing dataset from Kaggle:  

[Customer Personality Analysis - Kaggle](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)  

In this project, we load it from a local CSV file with tab separator.  

## How to Run ▶️

1. Clone the repository or download the code files.  
2. Install required Python packages:

```bash
pip install -r requirements.txt
