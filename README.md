# Retail Sales & Profit Intelligence Dashboard

## Project Overview
This project is an end-to-end Microsoft Excel analytics solution for retail sales and profitability analysis. It turns transaction-level sales data into an interactive management dashboard with KPI cards, PivotTables, PivotCharts, slicers, What-If Analysis, and business insights.

## Business Problem
Retail management needs a fast way to understand overall net sales and profit, product/category performance, regional performance, salesperson and channel performance, monthly sales trends, top products, and how changing price/volume assumptions can affect profit.

## Dataset
- **Transactions:** 60
- **Period:** January 2026 to September 2026
- **Regions:** North, South, East, West
- **Channels:** Corporate, Online, Retail

## Dashboard KPIs
- **Total Net Sales:** Rs. 2,381,690
- **Total Profit:** Rs. 598,090
- **Units Sold:** 422
- **Overall Profit Margin:** 25.1%

## Key Findings
- **Top sales category:** Electronics - Rs. 1,554,800
- **Top region by sales:** North - Rs. 883,735
- **Top product by sales:** Laptop - Rs. 781,000
- **Top salesperson by sales:** Aman - Rs. 883,735
- **Top channel by sales:** Corporate - Rs. 1,296,340
- **Best month by sales:** Sep-2026 - Rs. 533,310

## Excel Skills Used
- Data cleaning and structured Excel Tables
- Number/date formatting
- Sorting and advanced filtering
- Duplicate handling
- Data Validation and Conditional Formatting
- SUM / AVERAGE / MAX / MIN / ROUND
- IF / IFS / AND / OR
- SUMIF / SUMIFS / COUNTIF / COUNTIFS
- Relative, absolute, and mixed references
- VLOOKUP / XLOOKUP / INDEX + MATCH / OFFSET practice
- PivotTables and PivotCharts
- Slicers and Timeline concepts
- Goal Seek
- Scenario Manager
- One-variable and two-variable What-If Data Tables
- Dashboard creation
- Cell, sheet, and workbook protection concepts
- VBA / Macro practice concepts

## Repository Structure
```text
Retail-Sales-Profit-Analytics/
├── Retail_Sales_Profit_Dashboard.xlsm
├── README.md
├── data/
│   └── retail_sales_data.csv
├── screenshots/
│   ├── dashboard.png
│   ├── pivot_analysis.png
│   └── what_if_analysis.png
└── docs/
    ├── project_summary.pdf
    ├── resume_entry.txt
    └── linkedin_post.txt
```

## Dashboard Preview
![Retail Sales & Profit Intelligence Dashboard](screenshots/dashboard.png)

## Important Note About Macros
The workbook originally provided for packaging was an `.xlsx` file, so no embedded VBA project was present in that source file. The `.xlsm` copy in this repository is macro-enabled, but if you have your original workbook with actual VBA modules/macros saved in `.xlsm`, replace this file with that original version.
