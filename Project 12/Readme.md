# Data Cleaning and EDA on Exercise Sample Dataset

This project demonstrates **step-by-step data cleaning**, **outlier detection**, **analysis**, and **visualization** on a sample of the `exercise` dataset from seaborn.

## Steps
1. Load dataset
2. Inspect initial data (shape, info, describe)
3. Check and handle missing values
4. Check and remove duplicates
5. Drop unnecessary columns
6. Fix data types (id, time, diet, kind)
7. Detect outliers with Boxplot for all numeric columns
8. Remove or handle outliers using IQR method
9. Visualize distributions
10. Interactive scatter and boxplots with Plotly

## Notes
- Numeric columns are checked for outliers and cleaned.
- Boxplots and interactive plots are included for analysis.
- The dataset used is a small sample with `pulse` as numeric feature.

## Run
```bash
pip install -r requirements.txt
jupyter notebook exercise_cleaning_EDA.ipynb
```
