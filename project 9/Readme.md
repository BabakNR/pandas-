# Loan Data Cleaning Script

This repository contains a Python script to perform data cleaning and preprocessing on a loan dataset (`loan_data.csv`).  
The script handles:

- Loading the dataset
- Inspecting the dataset shape, info, and descriptive statistics
- Cleaning categorical columns (like `purpose`)
- Encoding categorical variables
- Detecting and removing outliers using IQR method
- Renaming columns to standardized format
- Visualizing correlations with heatmap
- Saving the cleaned dataset (`loan_data_cleaned.csv`)

## Requirements

- Python 3.7+
- pandas
- numpy
- matplotlib
- seaborn

## How to Use

1. Place your `loan_data.csv` file in the same directory as the script.
2.  Open the Jupyter Notebook:

```bash
jupyter notebook data_cleaning.ipynb

```
