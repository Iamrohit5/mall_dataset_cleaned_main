Data Cleaning and Preprocessing – Task 1 📌 Objective

The purpose of this task is to clean and preprocess a raw dataset by handling missing values, duplicates, inconsistent column formats, and data type mismatches. The cleaned dataset can then be used for further analysis or modeling.

📊 Dataset

Name: Mall Customer Segmentation Data

Source: Kaggle

Shape (raw): 200 rows × 5 columns

🛠️ Tools Used

Python 3.12

Pandas Library

🔄 Cleaning Steps

Loaded dataset using Pandas.

Handled missing values by dropping null rows.

Removed duplicate entries to avoid redundancy.

Standardized column names to lowercase with underscores (e.g., Annual Income (k$) → annual_income_(k$)).

Cleaned text values in the gender column for consistency.

Converted data types:

age, annual_income_(k$), and spending_score_(1-100) → integers.

Exported cleaned dataset as Mall_Customers_Cleaned.csv.

✅ Final Output

The cleaned dataset contains 200 rows × 5 columns with the following structure:

customerid – Unique ID for each customer

gender – Male / Female

age – Age of the customer (integer)

annual_income_(k$) – Annual income in thousand dollars (integer)

spending_score_(1-100) – Spending score assigned by the mall (integer)

📂 Files Included

mall_customers.csv → Python script used for cleaning

Mall_Customers_Cleaned.csv → Final cleaned dataset

README.md → Documentation
