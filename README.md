# My_projects
# 🚗 Used Car Data Cleaning Project

This project focuses on cleaning a dataset of used cars to prepare it for further data analysis and machine learning tasks.

## 📁 Dataset
The dataset contains information about used cars such as:
- Brand and Model
- Year
- Fuel Type
- Transmission
- Ownership
- Kilometers Driven
- Asking Price

## 🧹 Data Cleaning Steps

The following steps were performed during data cleaning:

1. **Removed Duplicates** – Eliminated duplicate rows to avoid data redundancy.
2. **Handled Missing Values** – Dropped rows with missing entries for consistency.
3. **Cleaned Text Columns** – Processed `kmDriven` and `Price` to remove units and convert them into numeric values.
4. **Converted Data Types** – Converted columns like `Price` and `kmDriven` to float for numerical operations.
5. **Handled Outliers** – Removed extreme values from the `Price` column using the IQR method.
6. **Renamed Columns** – Renamed `AskPrice` to `Price` for simplicity.
7. **Reset Index** – Reindexed the cleaned dataset after removing outliers.
8. **Saved Cleaned Dataset** – Exported final cleaned data to `filter_used_car.csv`.

## 📊 Tools Used
- Python 🐍
- Pandas
- NumPy
- Jupyter Notebook

## 📌 File Structure

## ✍️ Author
**Amr Khaled**  
Computer Science Student | Aspiring Data Analyst  
[LinkedIn](www.linkedin.com/in/amr-khaled-1a30b9364) | [GitHub](https://github.com/AmrKhaled880)
