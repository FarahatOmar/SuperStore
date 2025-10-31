# 🧠 Superstore Sales & Profit Analysis

**Goal:**  
Analyze the Superstore dataset to uncover key business insights — which regions, products, and strategies drive revenue and profitability, and where performance suffers.

---

## 📊 Project Overview

This project explores a retail dataset using **Python (Pandas, Seaborn, Matplotlib)**.  
It demonstrates the workflow of a data analyst — from basic KPI summaries to advanced insight generation.

**Key Questions Answered:**

1. What are the total sales, total profit, and overall profit margin?
2. Which regions and customer segments perform best?
3. Which product categories and sub-categories drive profit or losses?
4. How do discounts affect profitability?
5. Does shipping mode influence margin or quantity?
6. How do sales and profit trend over time?

---

## 🧩 Dataset

- **Source:** [Superstore Dataset - Kaggle](https://www.kaggle.com/datasets/tsarina/superstore)
- **Size:** ~10,000 records
- **Columns:** Order Date, Sales, Profit, Discount, Region, Category, Ship Mode, etc.

---

## 🧮 Methods Used

- **Data Cleaning:** handled datetimes, missing values, and type conversions
- **Aggregation:** `groupby`, `agg`, and custom summary functions
- **Exploratory Analysis:** descriptive KPIs, profit margin calculations
- **Visualization:** bar charts, scatter plots, and time-series trends using Seaborn

---

## 🖼️ Visual Insights

| Insight                             | Visualization        |
| :---------------------------------- | :------------------- |
| Regional profit margin              | Bar chart            |
| Category & Sub-category performance | Horizontal bar chart |
| Discount vs Profit                  | Scatter plot         |
| Shipping mode comparison            | Bar chart            |
| Monthly sales & profit              | Line chart           |

---

## 💡 Key Findings

- **West Region** drives the highest sales, while **South** achieves the best efficiency.
- **Technology** dominates in both sales and profit; **Furniture (Tables, Bookcases)** drags performance.
- **High discounts** destroy profit margins beyond ~30%.
- **Standard shipping** provides the best cost-profit balance.
- Clear **year-end spikes** show strong seasonal demand.

---

## ⚙️ Tech Stack

- **Python**
- **Pandas** for data analysis
- **Seaborn & Matplotlib** for visualization
- **Jupyter Notebook** for workflow and presentation

---
