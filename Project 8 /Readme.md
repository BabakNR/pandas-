# 📞 Telecom Customer Data Cleaning

This project performs data cleaning on a telecom call details record (CDR) dataset.

## 📋 Features

- Load and inspect dataset
- Remove duplicate rows
- Clean and standardize phone numbers
- Detect and remove outliers using the IQR method
- Export the cleaned dataset

## 📁 Dataset

The raw dataset should be placed at:
```
C:\Users\Ali\Desktop\Call Details-Data.csv
```

> Make sure to adjust the path or column names if your dataset differs.

## 🧼 Cleaning Steps

1. Load CSV data
2. Check and remove duplicate rows
3. Clean phone numbers (remove special characters and standardize with `+1`)
4. Detect and remove outliers from numeric columns: `call_duration`, `charge_amount`
5. Save the cleaned dataset to:
```
C:\Users\Ali\Desktop\cleaned_cdr.csv
```

## 🛠 Requirements

See [`requirements.txt`](./requirements.txt) for dependencies.

## 💡 Usage

```bash
python clean_telecom_data.py
```

## 🧪 Output

- Cleaned dataset saved as `cleaned_cdr.csv`
- Boxplots for outlier detection
