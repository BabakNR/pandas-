# Data Cleaning Project: Diamonds Dataset

## Dataset 

Real dataset used: diamonds.csv

## Project Overview

This project performs data cleaning on the diamonds dataset, including:

- Loading real dataset
- Handling missing values
- Removing outliers (IQR on price)
- Removing duplicates
- Data type correction and column standardization
- Visualization with heatmap and interactive Plotly scatter plot

## Files

- cleaning_diamonds.py (main cleaning script)
- diamonds_cleaned.csv (output cleaned data)

## Requirements

```
pandas
numpy
matplotlib
seaborn
plotly
```

## How to Run

```
pip install -r requirements.txt
python cleaning_diamonds.py
```

## Interactive Plot

The interactive scatter plot of Price vs Carat uses Plotly and will open in your default browser when you run the script.
