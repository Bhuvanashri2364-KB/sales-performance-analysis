# Sales Performance Analysis – Retail Superstore

This project analyzes retail sales data using Python and Power BI to uncover insights related to sales performance, discounting, and profitability.

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

## Key Insights
- Furniture category generates high sales but significantly lower profit, indicating inefficiency
- Higher discount levels are negatively correlated with profit, leading to margin reduction
- Technology category demonstrates strong profitability with relatively lower discount dependency
- Profitability varies across regions, suggesting potential geographic performance differences
- Certain high-sales products contribute low or negative profit, highlighting profit leakage

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

## Dashboard Preview
![Dashboard](dashboard_preview.png)

## Conclusion
Business profitability is not driven by sales alone. Discount strategy plays a major role, especially in underperforming categories like Furniture.
