# Task 1: Data Cleaning and Preprocessing – Netflix Dataset

## ✅ Objective:
Clean and preprocess a raw Netflix dataset using Python (Pandas).

## 📌 Key Steps Performed:
- Loaded raw dataset in Pandas
- Checked null values using .isnull().sum()
- Removed duplicates using .drop_duplicates()
- Cleaned and renamed columns
- Converted date_added to datetime format
- Extracted added_year and added_month from the date
- Saved the cleaned dataset as netflix_cleaned.csv

## 📁 Files Included:
- Task1_Cleaning.ipynb – Code notebook with cleaning process
- netflix_cleaned.csv – Final cleaned dataset
- README.md – Project summary and documentation

## 🧠 Interview Questions Covered:
1. What are missing values and how do you handle them?
   - Missing values are empty or null cells. We handle them by removing or filling them using .dropna() or .fillna().
2. How do you treat duplicate records?
   - With .drop_duplicates() in Pandas.
3. Difference between .dropna() and .fillna()?
   - dropna() removes null rows; fillna() fills them with specified values.
4. What is outlier treatment?
   - Identifying values far from others and treating or removing them to prevent skewed analysis.
5. Explain standardizing data.
   - Bringing data into a consistent format (e.g., lowercase country names, date formats).
6. How do you fix inconsistent data formats?
   - By converting using .astype() or pd.to_datetime().
7. Common data cleaning challenges?
   - Missing values, typos, inconsistent formats, duplicate rows.
8. How to check data quality?
   - Using .info(), .describe(), .isnull().sum(), and data profiling.

## 👩‍💻 Prepared By:
*Sanika Homkar*
