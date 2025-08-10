# 🧹 Data Cleaning in SQL – Layoffs Dataset

This project showcases a **complete SQL-based data cleaning workflow** on a layoffs dataset, preparing it for analysis and visualization.

## 📌 Overview
The dataset includes details such as company name, location, industry, layoffs count, dates, stage, country, and funds raised.  
Using **MySQL**, the raw data was cleaned, standardized, and made analysis-ready.

## 🔹 Steps Performed
1. **Remove Duplicates** – Used `ROW_NUMBER()` to identify and delete duplicate rows.
2. **Standardize Data** – Trimmed spaces, unified industry names, fixed country formats, converted dates to `DATE` type.
3. **Handle Missing Values** – Set blank values to `NULL` and filled gaps using other company records.
4. **Remove Irrelevant Data** – Deleted rows with no layoff data and dropped helper columns.

## 🛠 Tools Used
- MySQL
- SQL Functions: `ROW_NUMBER()`, `TRIM()`, `STR_TO_DATE()`, `JOIN`, `UPDATE`, `DELETE`

## 🚀 Outcome
The result is a **clean, consistent, and analysis-ready dataset**.

---
📂 **File**: `Data cleaning.sql`
