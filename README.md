# 📊 Sales & Profitability Analysis — Identifying Revenue Leakage in Retail

## 📊 Dashboard Preview

![Dashboard](images/dashboard.png)

---

## 📌 Executive Summary

This project analyzes retail sales data to identify revenue drivers, profit leakage, and category-level performance trends. The goal is to uncover inefficiencies in discounting strategies and optimize profitability across product categories.

Key findings reveal that certain high-revenue categories contribute disproportionately low profit due to excessive discounting and poor pricing strategies.

This analysis shifts focus from revenue growth to profitability optimization, enabling more sustainable business decisions.

---

## 📈 Why This Project Matters

Many businesses focus on increasing sales without understanding profitability drivers.
This project highlights how discounting strategies can silently reduce margins despite strong revenue growth.

---

## 💼 Business Problem

Retail businesses often prioritize sales volume without fully understanding profit drivers. High discounting and inconsistent pricing strategies can lead to strong revenue growth but poor margins.

This project aims to:

* Identify which categories and products drive profit vs loss
* Analyze the impact of discounting on profitability
* Detect inefficiencies in pricing and sales strategy

---

## ❓ Key Business Questions

* Which product categories generate high sales but low profit?
* How do discounts impact profitability?
* Which regions contribute most to profit and revenue?
* Are there products driving revenue but causing losses?

---

## 🚀 Project Overview

This is an end-to-end retail sales analysis project using Python (Pandas) and Power BI.

The analysis focuses on understanding category-level performance, discount impact, and profit distribution across products and regions.

The goal is to move beyond sales tracking and enable profitability-driven decision-making.

---

## 📊 Visualization Summary

The Power BI dashboard highlights key performance metrics including sales, profit, and discount impact across categories and regions.

Key visuals include:

* Sales vs Profit by Category
* Discount vs Profit relationship
* Regional performance comparison
* Product-level profitability analysis

---

## 🎯 Key Insights

* Furniture category contributes ~30% of total revenue but only ~5% of total profit, indicating severe margin inefficiency
* Discounts above ~15% significantly reduce profit margins, showing strong negative correlation
* Technology category maintains high profitability with lower dependency on discounts
* Regional profitability varies significantly, indicating inconsistent market performance
* Several high-sales products generate little or negative profit, highlighting revenue leakage

---

## 💡 Business Impact

* Enables optimization of discount strategies to protect margins
* Identifies loss-making products and categories
* Supports data-driven pricing and promotion decisions
* Improves overall revenue quality, not just revenue quantity

---

## 🧠 Recommendations

* Reduce excessive discounting in low-margin categories like Furniture
* Focus on expanding high-profit categories such as Technology
* Identify and reprice or remove loss-making products
* Implement discount thresholds based on profitability
* Standardize pricing strategies across regions

---

## 🛠️ Tools Used

* Python (Pandas)
* Power BI
* DAX

---

## ⚙️ Technical Highlights

* Performed data cleaning and preprocessing (missing values, type conversions)
* Engineered features such as profit margin and time-based attributes
* Conducted exploratory data analysis to identify trends and anomalies
* Built calculated measures in Power BI using DAX
* Designed an interactive dashboard with filters and drill-down capability

---

## 🔄 Project Workflow

1. Data Loading
   Loaded dataset using Pandas

2. Data Understanding
   Explored structure, missing values, and duplicates

3. Data Cleaning
   Converted date formats and handled inconsistencies

4. Feature Engineering
   Created Month, Year, and Profit Margin

5. Exploratory Data Analysis
   Analyzed trends across categories, regions, and segments

6. Profitability Analysis
   Identified high-sales but low-profit products

7. Discount Impact Analysis
   Evaluated how discount levels affect profitability

8. Visualization
   Built Power BI dashboard with KPIs and filters

---

## 📂 Files Included

* `python/sales_analysis.py`
* `data/superstore.csv`
* `Sales_Performance_Dashboard.pbix`
* `images/dashboard.png`

---

## 📌 Conclusion

Business profitability is not driven by sales alone. Discount strategy plays a major role, especially in underperforming categories like Furniture.

---

## 📚 Key Learnings

* Sales growth does not always translate to profitability
* Discount strategies must be optimized to protect margins
* Data visualization plays a crucial role in uncovering insights
* End-to-end analytics involves data cleaning, analysis, and storytelling
