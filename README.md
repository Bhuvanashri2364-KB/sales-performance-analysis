# Sales Performance Dashboard – Superstore Analysis

This project analyzes retail sales data using Python and Power BI to uncover insights related to sales performance, discounting, and profitability.

## Objective
To understand how discounting impacts profit and identify which product categories are performing efficiently.

## Tools Used
- Python (Pandas)
- Power BI
- DAX

## Project Workflow
- Loaded and explored the dataset using Python
- Cleaned and transformed data (dates, profit margin)
- Performed analysis on category, region, and segment
- Built interactive Power BI dashboard

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
