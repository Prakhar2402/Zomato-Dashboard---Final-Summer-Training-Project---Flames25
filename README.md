# Zomato-Dashboard---Final-Summer-Training-Project---Flames25
# 🍽️ Zomato Dashboard Project

This project aims to explore, clean, and analyze restaurant data from Zomato across different countries and cities — transforming it into meaningful insights and visual reports using modern data tools.

---

## 🔧 Tools & Technologies Used

- **Excel** – Data cleaning and preprocessing  
- **Python** – EDA, feature engineering, function creation, and outlier handling  
- **MySQL** – Querying, grouping, filtering, and joining data  
- **Power BI** – Final dashboard creation and visualization  

---

## 📂 Dataset Overview

The project is based on the **Zomato restaurant dataset**, merged with the `Country-Code.xlsx` file to get proper country names.

---

## ✅ Project Workflow

### 1️⃣ Excel – Data Cleaning

- Removed duplicates, handled blanks, fixed data types
- Standardized categorical values (like `Yes/No`, `Currency`, etc.)
- Created helper columns (e.g., `Votes values are nos`, `Rating Category`)
- Saved cleaned file for use in Python

---

### 2️⃣ Python – Data Analysis & Feature Enhancement

- Loaded the cleaned Excel file
- Performed Exploratory Data Analysis (EDA)
- Built custom functions for filtering and insights
- Handled outliers and corrected invalid data (e.g., negative votes)
- Saved the final Python-processed file as CSV for SQL use

---

### 3️⃣ SQL – Query-Based Analysis

- Imported the cleaned dataset into **MySQL**
- Created appropriate table with all text-compatible data types
- Performed grouping, joins, and filtering using SQL queries
- Identified important segments, aggregated values, and filtered scenarios
- Final SQL queries helped refine the dataset used in Power BI

---

### 4️⃣ Power BI – Dashboard Creation

- Imported the final SQL output into Power BI
- Built an interactive dashboard with dynamic visuals and slicers
- Created KPI cards and charts for business-ready presentation
- Published the dashboard for exploration and presentation

---

## 🙌 Acknowledgement

This project is a part of my **Summer Training** under the **Angaar Batch – Flames 25**.

Special thanks to my mentor **Ms.Gaurika Dhingra Mam** for her continuous support and guidance throughout the training journey.

---

## If you like this project, don't forget to give ⭐.

> *“Transforming raw restaurant data into decision-ready insights – one tool at a time.”*
