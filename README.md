# Retail Sales & Profit Intelligence Dashboard

## Project Overview
This project is an end-to-end Microsoft Excel analytics solution for retail sales and profitability analysis. It transforms transaction-level sales data into an interactive management dashboard using KPI cards, PivotTables, PivotCharts, slicers, What-If Analysis, and business insights.

## Business Problem
Retail management needs a fast way to understand:
- overall net sales and profit,
- product and category performance,
- regional performance,
- salesperson and channel performance,
- monthly sales trends,
- top products,
- and how changing price/volume assumptions can affect profit.

## Dataset
- **Transactions:** 60
- **Period:** January 2026 to September 2026
- **Regions:** North, South, East, West
- **Channels:** Corporate, Online, Retail
- Key fields include Order ID, Order Date, Product, Category, Region, City, Salesperson, Channel, Units, Unit Price, Unit Cost, Discount, Net Sales, Profit, Profit Margin, Month, and Performance Status.

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
- Electronics also generated the highest category profit at Rs. 285,800.

## Excel Skills Used
- Data cleaning and structured Excel Tables
- Number and date formatting
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

## Workbook Structure
- `Sales_Data` - cleaned transaction-level dataset and calculated fields
- `Pivot_Analysis` - PivotTable-based business analysis
- `Dashboards` - KPI cards, charts, and slicers
- `Project_Notes` - formula practice and analysis notes
- `Scenario Summary` - Scenario Manager output
- `What-If Analysis` - Goal Seek / Scenario / Data Table model

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
    ├── project_summary.md
    ├── resume_entry.txt
    └── linkedin_post.txt
```

## How to Use
1. Open `Retail_Sales_Profit_Dashboard.xlsm` in Microsoft Excel.
2. Review the `Sales_Data` sheet for transaction-level details.
3. Use the dashboard slicers to explore categories, regions, salespeople, and channels.
4. Review the `Pivot_Analysis` sheet for summarized analysis.
5. Explore `What-If Analysis` and `Scenario Summary` for profitability scenarios.

## Dashboard Preview
Once `screenshots/dashboard.png` is present in the repository, GitHub will render it here automatically:

![Retail Sales & Profit Intelligence Dashboard](screenshots/dashboard.png)

## Important Note About Macros
The workbook originally provided for packaging was an `.xlsx` file, so no embedded VBA project was present in that source file. The packaged `.xlsm` copy is macro-enabled, but no VBA code could be recovered from the uploaded `.xlsx`. If you have the original workbook with actual VBA modules/macros saved in `.xlsm`, use that version for the strongest portfolio submission.

## Portfolio Use
This project is suitable for:
- GitHub portfolio
- LinkedIn project showcase
- Data Analyst resume project section
- Excel/Data Analyst interview discussion
