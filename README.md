# cost-optimization-sql-python
# 🧮 Operational Efficiency & Profit Optimization Analysis

## 📌 Overview

This project analyzes operational cost data using **Python** and **SQL (SQLite)** to uncover inefficiencies in product-level performance. It simulates real-world decision-making by calculating profitability metrics across categories and countries, with a focus on optimizing cost structures and identifying underperforming SKUs.

---

## 💡 Objectives

- Calculate Total Cost, Profit, and Profit Margin for each SKU
- Identify loss-making and low-margin products
- Analyze category-wise and country-wise performance
- Visualize cost-revenue dynamics using Seaborn and Matplotlib

---

## 📂 Dataset

Simulated operational data with the following columns:

- `Date`  
- `SKU_ID`  
- `Category`  
- `Country`  
- `Quantity`  
- `Unit_Cost`, `Distribution_Cost`, `Labor_Cost`, `Repair_Cost`, `Advertisement_Cost`  
- `Revenue`

---

## 🔍 KPIs Calculated (via SQL)

- **Total Cost** = Unit Cost × Quantity + All other costs  
- **Profit** = Revenue − Total Cost  
- **Profit Margin** = Profit / Revenue

---

## 📈 Key Insights

- **Average profit margin** across all SKUs was **-9.4%**, indicating operational inefficiencies.
- Categories like **Furniture** and **Electronics** showed consistent losses, while **Apparel** was profitable.
- Countries like **Germany** and **France** had the **lowest average margins**.
- Over **60% of high-revenue SKUs** had **negative profit margins**, revealing the need for SKU-level pricing and cost optimization.

---

## 📊 Visualizations

- **Scatter Plot:** Total Cost vs Revenue by Category  
- **Bar Chart:** Profit Margin by Country  
- **Scatter Plot:** Quantity vs Profit (highlighting low-performing SKUs)

---

## 🧠 Technologies Used

- **Python**: Data wrangling (Pandas), visualization (Matplotlib, Seaborn)
- **SQL (SQLite)**: Profit calculations and grouping logic
- **Jupyter Notebook** (recommended for step-by-step analysis)

---

## 🚀 How to Run

1. Clone the repository
2. Run the Python script or Jupyter Notebook
3. All SQL is executed using Python’s `sqlite3` module in-memory (no setup required)
4. Visuals are rendered using `matplotlib.pyplot` and `seaborn`

---

## 📌 Resume Highlights (Optional)

- Automated margin calculations across cost dimensions using SQL and Python  
- Reduced manual analysis time by 70%  
- Identified 3 low-performing categories and optimized SKU-level cost insights

---

## 📁 Repository Structure

