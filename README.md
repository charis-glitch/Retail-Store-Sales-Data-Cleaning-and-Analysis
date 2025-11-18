# Retail Store Sales Data Cleaning & Analysis

This project demonstrates **professional data cleaning, analysis, and reporting** using **Python (Pandas, NumPy, Matplotlib, Seaborn)** on a **multi-sheet Excel dataset**.  
It’s designed as a portfolio example to showcase my **data wrangling, visualization, and Excel automation** skills for **freelance projects**.

---

## Overview

The dataset was sourced from [Kaggle – Retail Store Sales (Dirty for Data Cleaning)](https://www.kaggle.com/datasets/ahmedmohamed2003/retail-store-sales-dirty-for-data-cleaning).  
It contained inconsistent formatting, missing values, and duplicated rows, making it a great case for practical data cleaning.

I converted the raw CSV file into a **multi-sheet Excel workbook** and used **Python** to:
- Clean and structure the data,
- Handle missing or incorrect values,
- Perform exploratory summaries,
- Export cleaned results and insights back into the same Excel file.

This project mimics a **real-world client request** — transforming raw business data into clean, analyzable, and visualized outputs.

---

## Key Steps

1. **Data Import & Inspection**
   - Converted the original CSV file into a multi_sheet Excel workbook
   - Loaded the Excel file in Jupyter Notebook using `pandas.read_excel()`.
   - Reviewed data types, missing values, and duplicates.

2. **Data Cleaning**
   - Removed duplicates.
   - Stripped whitespace and normalized string values.
   - Converted `Transaction Date` to datetime format.
   - Repaired numeric columns using derived logic (e.g., recalculating `Price Per Unit` when missing).
   - Filled missing categorical values logically.

3. **Exploratory Analysis**
   - Identified **top 5 selling items** by quantity.
   - Calculated **sales by category** to reveal top-performing product groups.

4. **Visualization**
   - Created **bar charts** for:
     - Top 5 items by total quantity sold.
     - Total sales by category.

5. **Excel Integration**
   - Exported cleaned data and summary results back to the same Excel file.
   - Added two new sheets:  
     `Clean Data` and `Analysis & Summary`.

---

## Project Structure
- retail_store_sales 
  - retail_store_sales.csv (Raw dataset)
  - retail_store_sales_cleaning.ipynb (Jupyter notebook with code & analysis)
  - retail_store_sales.xlsx (cleaned data)
  - outputs (Folder containing plots)
    - top_items.png
    - sales_by_category.png
  - README.md (Project documentation)

---

## Insights

- The dataset contained multiple formatting issues that mimic **real business data challenges**.
- Some transactions were missing unit prices but could be derived mathematically.
- After cleaning:
  - Data integrity improved significantly.
  - Category-level and item-level sales patterns became visible.
- The results provide a clean base for **dashboarding, forecasting, or sales strategy analysis**.

---

## Tools & Technologies

| Tool | Purpose |
|------|----------|
| **Python** | Main programming language |
| **Pandas** | Data manipulation and cleaning |
| **NumPy** | Numerical handling |
| **Matplotlib / Seaborn** | Data visualization |
| **OpenPyXL** | Writing cleaned results back into Excel |
| **Jupyter Notebook** | Interactive data cleaning and exploration |

---

## Outputs

| File | Description |
|------|--------------|
| `Clean Data` (Excel Sheet) | Fully cleaned and standardized dataset |
| `Analysis & Summary` (Excel Sheet) | Key insights: Top items & category sales |
| `top_items.png` | Visualization of top-selling items |
| `sales_by_category.png` | Visualization of total category sales |

---

## Skills Demonstrated

✅ Data Cleaning (handling missing, inconsistent, and incorrect values)  
✅ Exploratory Data Analysis (EDA)  
✅ Excel Automation with Python  
✅ Visualization and Reporting  
✅ Reproducible & Readable Jupyter Notebook Workflow  



