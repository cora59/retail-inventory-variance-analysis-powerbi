# 📊 Retail Inventory Variance & Shrinkage Analysis (Power BI)

![Dashboard Preview](dashboard.png)

---

## 📌 Overview
This project analyzes inventory performance across multiple retail stores, focusing on stock discrepancies, shrinkage, and product-level variance.

The dashboard provides visibility into:
- Differences between expected and physical stock
- Shrinkage patterns (known vs unknown)
- High-risk products contributing to inventory loss

---

## 🧩 Business Problem
Retail businesses often face inventory inconsistencies due to:
- Stock counting errors  
- Transfer mismatches between warehouse and stores  
- Theft or unrecorded damages  

These issues lead to inaccurate reporting and financial losses.

This dashboard helps identify and quantify these discrepancies.

---

## ⚙️ Data Preparation (Power Query)
To ensure data privacy and portfolio safety:

- Store names anonymized → `Store 001, Store 002...`
- Product names anonymized → `Product 001, Product 002...`
- Financial values scaled to protect sensitive business data
- Data cleaned using Power Query transformations:
  - Removed blank columns
  - Created mapping tables for stores and products
  - Standardized formats for analysis

---

## 📐 Key Metrics & Calculations

- **Expected Stock**  
  = Opening Stock + Transfers – Sales – Damages  

- **Variance (Units)**  
  = Physical Count – Expected Stock  

- **Shrinkage Value**  
  = Variance × Unit Cost  

- **Inventory Turnover**  
  = Sales ÷ Average Inventory  

- **Shrinkage %**  
  = Total Shrinkage ÷ Total Inventory Value  

---

## 📊 Dashboard Features

- Inventory overview KPIs (Revenue, Inventory Value, Orders, Margin)
- Shrinkage breakdown (Known vs Unknown)
- Top 5 products with highest variance
- Product-level variance analysis
- Store filtering and time-based slicing
- Inventory turnover insights

---

## 🔍 Key Insights

- A shrinkage rate of approximately **0.29%** was observed  
- A small number of products drive the majority of inventory variance  
- High-value items contribute disproportionately to shrinkage risk  
- Variance patterns indicate potential operational inefficiencies in stock handling  

---

## 🛠 Tools Used

- Power BI  
- Power Query  
- Excel  

---

## 📁 Files Included

- `Portfolio_Inventory_Project.pbix`
- `Portfolio_Inventory_Project.xlsx`
- `dashboard.png`

---

## ⚠️ Disclaimer

This project uses **anonymized and modified data** for demonstration purposes.  
All sensitive business information has been removed while preserving the analytical structure.
