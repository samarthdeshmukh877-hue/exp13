# Data Wrangling and Missing Values Preprocessing

## Project Overview
This project focuses on data wrangling techniques using Python. The primary goal is to perform data preprocessing on a dataset, specifically identifying and handling missing values (NaN) to ensure data quality for analysis.

## Key Operations Performed
* **Detection of Missing Values**: Utilizing `isna()` and `notna()` functions to create boolean masks for data gaps.
* **Statistical Analysis of Nulls**: Calculating missing value counts both column-wise (`axis=0`) and row-wise (`axis=1`).
* **Data Cleaning Techniques**:
  * **Dropping Data**: Removing rows containing any null values using `dropna()`.
  * **Imputation**: Filling missing gaps with specific constants using the `fillna()` method.

## Technical Procedure
1.  **Environment Setup**: Import `pandas` and `numpy` libraries.
2.  **Dataset Construction**: Creation of a sample DataFrame with intentional `np.nan` values for testing.
3.  **Exploratory Data Analysis**:
    * Visualize the null structure using boolean mapping.
    * Summarize total missing counts per category to understand data loss.
4.  **Handling Missing Values**: Apply cleaning methods (Drop or Fill) depending on the analysis requirements.

## Conclusion
Through this experiment, I successfully implemented preprocessing workflows. Key takeaways include:
- **isna()** is essential for initial data auditing.
- **dropna()** is useful for cleaning small datasets but must be used carefully to avoid losing valuable information.
- **fillna()** provides a flexible way to maintain dataset size by replacing missing entries with estimated or constant values.
