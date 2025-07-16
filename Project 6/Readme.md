# Medical Appointment Data Cleaning

This project demonstrates a complete data cleaning and preprocessing pipeline using the real-world **Medical Appointment No Shows** dataset.

## Dataset
- Source: https://www.kaggle.com/datasets/joniarroba/noshowappointments
- Description: The dataset contains information about over 100,000 medical appointments in Brazil and whether patients showed up for their appointments.

## Cleaning Steps
1. Load and explore the dataset
2. Drop duplicates
3. Fix invalid values (e.g. negative ages)
4. Convert date columns and compute time differences
5. Handle categorical variables (gender, no_show)
6. Detect and remove outliers using IQR method
7. Save the cleaned dataset

## Usage
Run the Jupyter Notebook: `data_cleaning.ipynb`

## Output
A cleaned version of the dataset: `appointments_cleaned.csv`

