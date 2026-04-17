# Data Wrangling and Preprocessing (Experiment 13)

## Student Details
- Name: Samarth Deshmukh  
- PRN: 25070123101  

---

## Objective
To perform data wrangling and preprocessing on a dataset, including handling missing values, data cleaning, and formatting.

---

## Experiment Description

This experiment demonstrates:
- Detecting missing values
- Handling NaN values
- Data cleaning and formatting
- Converting data types
- Standardizing text data
- Formatting date columns

---

## Dataset Description

The dataset contains the following columns:

- Roll No  
- Name  
- Age  
- Marks  
- Department  
- Admission_Date  

Some values are missing or improperly formatted (e.g., "-", mixed date formats, lowercase text).

---

## Steps Performed

### 1. Creating DataFrame with Missing Values
- Introduced NaN values using NumPy
- Checked missing values using:
  - `isna()`
  - `notna()`
  - `sum()`

---

### 2. Handling Missing Values
- Dropped missing values using:
  - `dropna()`
- Filled missing values using:
  - Constant values
  - Mean of columns

---

### 3. Data Cleaning
- Replaced "-" with NaN
- Converted columns to numeric using:
  - `pd.to_numeric()`

---

### 4. Filling Missing Data
- Replaced missing Age and Marks with mean values

---

### 5. Standardizing Data
- Converted Department column to uppercase

---

### 6. Date Formatting
- Converted Admission_Date to proper datetime format using:
  - `pd.to_datetime()`

---

## Key Functions Used

- `isna()`
- `notna()`
- `dropna()`
- `fillna()`
- `replace()`
- `to_numeric()`
- `str.upper()`
- `to_datetime()`

---

## Result

- Missing values were successfully handled
- Data types were corrected
- Dataset was cleaned and standardized
- Dates were converted into proper format

---

## Conclusion

Data preprocessing is an essential step in data analysis. This experiment demonstrates how to clean, transform, and prepare raw data for further analysis using Pandas.

---
