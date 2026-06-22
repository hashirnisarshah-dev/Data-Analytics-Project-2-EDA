# Data Cleaning and Preparation Project

## Project Overview

This project was completed as part of the DecodeLabs Data Analytics Internship. The objective of the project was to clean and prepare a retail sales dataset by identifying and resolving data quality issues, ensuring the dataset is accurate, consistent, and ready for analysis.

## Objectives

* Identify data quality issues in the dataset.
* Handle missing values appropriately.
* Detect and remove duplicate records.
* Standardize text and date formats.
* Validate the cleaned dataset.
* Prepare the dataset for further analysis and reporting.

## Dataset Description

The dataset contains retail sales transaction records. It includes information such as Order IDs, Customer IDs, dates, product details, and other transaction-related attributes.

## Data Cleaning Tasks Performed

### 1. Data Inspection

* Examined dataset structure and column information.
* Identified missing values and duplicate records.

### 2. Missing Value Treatment

* Analyzed missing values in the dataset.
* Replaced missing CouponCode values with "No Coupon".

### 3. Duplicate Handling

* Checked for duplicate rows.
* Verified uniqueness of Order IDs.
* Reviewed Customer ID repetitions and validated them as legitimate multiple purchases.

### 4. Data Standardization

* Removed unnecessary spaces.
* Standardized text formatting for consistency.

### 5. Date and Data Type Validation

* Converted date columns into proper date format.
* Verified numerical and categorical data types.

### 6. Final Validation

* Confirmed data consistency after cleaning.
* Generated final cleaned dataset for future analysis.

## Files Included

### Data_Cleaning_Project.ipynb

Google Colab notebook containing the complete data cleaning workflow.

### raw_dataset.csv

Original dataset before cleaning.

### cleaned_dataset.csv

Final cleaned dataset after preprocessing and validation.

## Tools Used

* Python
* Pandas
* NumPy
* Google Colab

## Outcome

The dataset was successfully cleaned, validated, and prepared for analysis. Data quality issues such as missing values and duplicates were addressed, resulting in a reliable dataset suitable for further analytical tasks.

## Author

Hashir Nisar

Data Analytics Intern – DecodeLabs
