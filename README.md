# 🧹 Sales Data Cleaning Project

Welcome to the **Sales Data Cleaning Project**! This repository showcases my ability to clean and preprocess real-world retail data using **Microsoft Excel**. The project is part of my internship learning journey to build confidence in handling raw datasets and prepare them for meaningful analysis.

---

## 🎯 Objective

The primary objective of this project was to:
- **Identify and handle missing values**, duplicates, and inconsistencies.
- **Clean, structure, and format** the dataset to make it ready for further analysis.
- Gain hands-on experience in **real-world data cleaning** using Excel techniques.

---

## 📊 Dataset Overview

The dataset contains transactional and outlet-level information for products sold in a retail chain.  
Here are the key columns:

- `Item_Identifier`
- `Item_Weight`
- `Item_Fat_Content`
- `Item_Visibility`
- `Item_Type`
- `Item_MRP`
- `Outlet_Identifier`
- `Outlet_Establishment_Year`
- `Outlet_Size`
- `Outlet_Location_Type`
- `Outlet_Type`

---

## 📈 Analysis & What I Did

### 🔍 1. **Missing Value Handling**
- Used filters in Excel to locate null values.
- Replaced:
  - Missing values in `Item_Weight` using the **mean** method.
  - Missing values in `Outlet_Size` using the **mode** approach (most frequent value).

### 🧽 2. **Duplicate Handling**
- Checked for duplicate entries using **Remove Duplicates** feature.
- Ensured no repeated rows remained.

### 🧹 3. **Standardization & Text Cleaning**
- Cleaned `Item_Fat_Content` values by replacing inconsistent entries:
  - e.g., "reg" → "Regular", "low fat", "LF" → "Low Fat".
- Applied:
  - `TRIM()` to remove extra spaces
  - `PROPER()` to maintain consistent casing

### ⚙️ 4. **Data Formatting**
- Verified correct data types:
  - Numeric columns like `Item_Weight`, `Item_MRP`, etc., were formatted as numbers.
  - Text columns standardized.
  - `Outlet_Establishment_Year` remained as integer type.

### 🧾 5. **Column Formatting**
- Ensured all column headers are clean, readable, and consistent.
- Renamed headers where necessary for clarity.

---

## 📂 Files Included

| File Name                     | Description                          |
|------------------------------|--------------------------------------|
| `test.xlsx`                  | Original dataset with issues         |
| `test_Task01.xlsx`           | Final cleaned version of the dataset |
| `Data_Cleaning_Report.pdf`   | Step-by-step cleaning process        |


---

## 💡 Key Learnings

- Practical experience in **data wrangling using Excel**.
- Tackled **real-world data issues** like inconsistency, duplication, and null handling.
- Improved my ability to **prepare clean, analysis-ready datasets**.

---

## 🛠️ Tools Used

- **Microsoft Excel**
  - Filters, conditional formatting
  - COUNTIF, MODE, AVERAGE functions
  - Remove Duplicates, Sort & Filter
  - TRIM, PROPER for text cleaning

---

## 📌 Contact

If you'd like to collaborate, review the project, or give feedback, feel free to reach out to me on GitHub!

---

> “Well-prepared data is the secret ingredient behind every great analysis.”
