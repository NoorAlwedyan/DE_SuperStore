# DE_SuperStore
A Data Cleaning and Preprocessing project using Python and Pandas on the Superstore dataset, including data quality checks, outlier detection, categorical encoding, and feature scaling.
# Superstore Data Cleaning and Preprocessing

## Project Overview
This project focuses on cleaning and preprocessing the Superstore dataset using Python and Pandas.

The main goal is to improve data quality, identify potential data issues, and prepare the dataset for further analysis and machine learning tasks.

## Dataset
The project uses the Superstore dataset, which contains information about sales, customers, products, orders, shipping, discounts, and profits.

## Project Objectives
- Explore and understand the dataset.
- Identify and handle missing values and duplicate records.
- Clean and standardize categorical data.
- Correct data types and validate data consistency.
- Detect and investigate outliers.
- Apply categorical encoding techniques.
- Perform feature scaling.

## Data Preprocessing Workflow

### 1. Data Understanding
- Loaded and inspected the dataset.
- Examined dataset dimensions, column names, and data types.
- Used descriptive statistics to understand numerical features.

### 2. Data Cleaning
- Checked for missing values.
- Identified and removed duplicate records.
- Standardized text values.
- Corrected data types.
- Validated business rules and data consistency.

### 3. Outlier Detection
- Used the Interquartile Range (IQR) method to detect outliers.
- Investigated extreme values in numerical columns such as Sales, Quantity, Discount, and Profit.
- Applied the Keep and Flag approach to preserve potentially valid business information while identifying outliers.

### 4. Categorical Encoding
- Applied One-Hot Encoding to selected nominal categorical features.
- Used Ordinal Encoding for Ship Mode.

### 5. Feature Scaling
- Applied MinMaxScaler to normalize numerical features.
- Applied StandardScaler to standardize numerical features.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Project Deliverables
- Jupyter Notebook (`.ipynb`) containing the code, outputs, visualizations, and explanations.
- Original dataset.
- Cleaned dataset before model-specific encoding and scaling.

## Conclusion
This project demonstrates the importance of data cleaning and preprocessing in the data science workflow. It provides a structured approach to improving data quality and preparing datasets for reliable analysis and future machine learning applications.
