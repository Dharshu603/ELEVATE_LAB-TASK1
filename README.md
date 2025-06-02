# ELEVATE_LAB-TASK1
# Task 1: Data Cleaning and Preprocessing

## 🔍 Objective
Clean and prepare a raw dataset containing missing values, duplicates, inconsistent text formats, and incorrect data types.

## 📂 Dataset Used
**Customer Personality Analysis**  
Source: [Customer Personality Analysis](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)

## 🛠 Tools
- Python
- Pandas

## 🧼 Data Cleaning Steps
- Identified and removed rows with missing values.
- Removed duplicate rows to ensure unique records.
- Standardized text columns (e.g., gender, country) to lowercase and consistent values.
- Converted date columns to `dd-mm-yyyy` format using `pd.to_datetime()`.
- Renamed column headers to lowercase with underscores instead of spaces.
- Corrected data types (e.g., age as integer, date as datetime).

## 📁 Files Included
- `original_dataset.csv` – Raw data downloaded from Kaggle.
- `cleaned_dataset.csv` – Final cleaned dataset.
- `data_cleaning_script.py` – Python script used for cleaning.
- `README.md` – This file.
- Cleaned data set(/content/cleaned_dataset.csv)
- 

## ✅ Output
The cleaned dataset is ready for analysis, modeling, or visualization.

---
