# Sales Performance Analysis – Retail Superstore

## 📊 Dashboard Preview

![Dashboard](dashboard.png)

## 📌 Executive Summary

This project analyzes retail sales data to identify revenue drivers, profit leakage, and category-level performance trends. The goal is to uncover inefficiencies in discounting strategies and optimize profitability across product categories.

Key findings:

• Furniture category generates high sales but significantly lower profit, indicating margin inefficiency  
• Higher discount levels are negatively correlated with profit, leading to revenue loss  
• Technology category shows strong profitability with lower dependency on discounts  
• Certain high-sales products contribute low or negative profit, highlighting profit leakage  

Business impact:

• Helps optimize discount strategies to improve margins  
• Identifies underperforming categories and products  
• Supports data-driven pricing and promotion decisions  

## 💼 Business Problem

Retail businesses often focus on increasing sales volume without fully understanding profitability drivers. High discounts and poor pricing strategies can lead to revenue growth but reduced margins.

This project aims to:

• Identify which categories and products drive profit vs loss  
• Analyze the impact of discounting on profitability  
• Detect inefficiencies in pricing and sales strategy  

## 🚀 Project Overview

This is an end-to-end retail sales analysis project using Python, SQL, and Power BI.

The analysis focuses on understanding category-level performance, discount impact, and profit distribution across products and regions.

The goal is to move beyond sales tracking and enable profitability-driven decision making.

## Objective

Retail businesses often struggle with balancing sales growth and profitability, especially when heavy discounting is involved.

This project analyzes sales data to identify profit leakage, evaluate the impact of discounts, and uncover category-level performance trends that can support better pricing and inventory decisions.

## Key Business Questions

* Which product categories generate high sales but low profit?
* How do discounts impact profitability?
* Which regions contribute most to profit and revenue?
* Are there products driving revenue but causing losses?

## Tools Used
- Python (Pandas)
- Power BI
- DAX

## Technical Highlights

* Performed data cleaning and preprocessing using Pandas (handling missing values, type conversions)
* Engineered features such as profit margin and time-based attributes (month, year)
* Conducted exploratory data analysis (EDA) to identify trends and anomalies
* Built calculated measures in Power BI using DAX for KPIs
* Designed an interactive dashboard with filters and drill-down capabilities

## Project Workflow
1. Data Loading  
   Loaded the Superstore dataset using Pandas for analysis

2. Data Understanding  
   Explored dataset structure, checked data types, missing values, and duplicates

3. Data Cleaning  
   Converted Order Date to datetime format for time-based analysis

4. Feature Engineering  
   Created Month, Year, and Profit Margin columns to enhance analysis

5. Exploratory Data Analysis  
   Analyzed sales and profit across categories, regions, and segments

6. Profitability Analysis  
   Identified high-sales but low-profit products to detect profit leakage

7. Discount Impact Analysis  
   Evaluated how discount levels affect profitability

8. Visualization  
   Built an interactive Power BI dashboard with KPIs, charts, and filters

## Key Insights & Recommendations
* **Furniture category generates high sales (~30% of total revenue) but contributes minimal profit (~5%)**, indicating inefficient pricing or excessive discounting.
  → Recommendation: Reduce discount levels or revise pricing strategy for this category.

* **Discounts above ~15% significantly reduce profit margins**, showing a strong negative correlation between discount and profitability.
  → Recommendation: Introduce discount caps and monitor margin impact.

* **Technology category maintains strong profitability with lower discount dependency**, making it a high-value segment.
  → Recommendation: Focus marketing and inventory investments on high-margin categories.

* **Regional profitability varies significantly**, suggesting uneven market performance.
  → Recommendation: Investigate underperforming regions and adjust pricing or logistics strategies.

* **Some high-sales products generate little or negative profit**, highlighting profit leakage.
  → Recommendation: Identify and re-evaluate pricing or discontinue low-margin products.

## Dashboard Features
- KPI Cards (Sales, Profit, Discount, Margin)
- Bar chart (Sales vs Profit by Category)
- Scatter plot (Discount vs Profit)
- Filters (Category, Region, Date)

## Files Included
- python/sales_analysis.py
- data/superstore.csv
- Sales_Performance_Dashboard.pbix
- dashboard_preview.png

## 📊 Visualization Summary

The Power BI dashboard highlights key performance metrics including sales, profit, and discount impact across categories and regions.

Key visuals include:

• Sales vs Profit by Category  
• Discount vs Profit relationship  
• Regional performance comparison  
• Product-level profitability analysis  

## 💡 Business Impact

• Enables optimization of discount strategies to protect margins  
• Helps identify loss-making products and categories  
• Supports better pricing decisions based on profitability  
• Improves overall revenue quality, not just revenue quantity  

## 🧠 Recommendations

• Reduce excessive discounting in low-margin categories like Furniture  
• Focus on expanding high-profit categories such as Technology  
• Identify and reprice loss-making products  
• Implement controlled discount strategies based on profitability thresholds  
• Standardize pricing strategies across regions to reduce inconsistencies  

## Conclusion
Business profitability is not driven by sales alone. Discount strategy plays a major role, especially in underperforming categories like Furniture.

## Key Learnings

* Sales growth does not always translate to profitability
* Discount strategies must be optimized to protect margins
* Data visualization plays a crucial role in uncovering business insights
* End-to-end analytics involves data cleaning, analysis, and storytelling

