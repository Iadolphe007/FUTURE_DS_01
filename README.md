# Superstore Sales Analysis Dashboard

An interactive sales analytics project developed during the **Future Intern Data Analytics Internship**. The project uses the Superstore dataset to explore sales performance, profitability, geographical trends, and performance over time through an interactive Power BI dashboard.

## Project Overview

The dashboard is designed to turn sales data into useful business insights. It brings key performance indicators and interactive visualizations together so users can explore performance at different levels of detail and identify areas that may need attention.

## Objectives

- Monitor key business performance indicators.
- Explore sales performance across regions, states, and cities.
- Analyze profit across product categories, sub-categories, and products.
- Examine sales trends by year and month.
- Present findings in a clear, interactive dashboard to support business decisions.

## Technology Stack

- **Microsoft Power BI Desktop** — data modeling, DAX measures, visualizations, drill-downs, and dashboard design.
- **Microsoft Excel** — data file handling and spreadsheet-based data review/preparation.
- **DAX (Data Analysis Expressions)** — calculations for key performance indicators.
- **Superstore dataset** — source data for sales, quantity, profit, geography, products, and dates.

> The technologies listed above reflect the tools used in this project. Add Power Query or other tools here only if they were used in your workflow.

## Key Performance Indicators

The dashboard includes KPI cards for:

- **Total Revenue** — sum of sales.
- **Units Sold** — total quantity sold.
- **Profit Margin** — total profit divided by total revenue.
- **Total Profit** — used to calculate and evaluate profitability.

### Example DAX Measures

```DAX
Total Revenue = SUM('Sample - Superstore'[Sales])

Units Sold = SUM('Sample - Superstore'[Quantity])

Total Profit = SUM('Sample - Superstore'[Profit])

Profit Margin = DIVIDE([Total Profit], [Total Revenue], 0)
```

*Note: The table name in these formulas is `Sample - Superstore`. Update it if your model uses a different table name.*

## Dashboard Features

- **KPI cards** for a quick view of revenue, units sold, and profit margin.
- **Geographical sales drill-down:** Region → State → City.
- **Profitability drill-down:** Category → Sub-Category → Product.
- **Sales trend drill-down:** Year → Month.
- **Consistent visual design** using a navy, teal, white, and light grey-blue color palette.
- **Interactive exploration** to inspect performance at different levels.

## Business Insights and Recommendations

The dashboard supports analysis of:

- Differences in sales performance between geographical markets.
- Products and categories that contribute more or less to profit.
- Monthly and yearly changes in sales.
- The relationship between revenue and profitability.

Recommended business actions include reviewing low-profit or loss-making products, assessing pricing and discount strategies, using sales trends to improve inventory and campaign planning, and monitoring revenue and profit margin together. Specific conclusions should be based on the values and patterns confirmed in the dashboard.

## How to Use

1. Open the Power BI report file (`.pbix`) in **Power BI Desktop**.
2. Ensure the source dataset is available and refresh the data if needed.
3. Review the KPI cards for an overview of performance.
4. Use the chart drill-down controls to explore geographical, product, and time-based results.
5. Select chart elements or slicers, if present, to explore filtered results.
6. Review the insights and recommendations alongside the visual evidence.

## Project Structure

A suggested structure for sharing the project:

```text
superstore-sales-analysis/
├── README.md
├── data/
│   └── superstore_dataset.xlsx
├── report/
│   └── superstore_dashboard.pbix
└── screenshots/
    └── dashboard_overview.png
```

This is a suggested layout. Rename folders and files to match the actual files you include. Do not publish the dataset if its licence or sharing terms do not allow redistribution.

## Validation and Testing

Before presenting the dashboard, check that:

- KPI values match the source data.
- Currency, whole-number, and percentage formats are correct.
- Each drill-down hierarchy works in the intended order.
- Filters and visual interactions behave as expected.
- The report contains no unexpected blank visuals or errors.
- The report file is saved and opens correctly.

## Limitations

The dashboard describes patterns in the supplied dataset. It does not, by itself, establish why a trend occurred or guarantee future results. Business recommendations should be reviewed against the underlying data and any additional operational context.

## Future Improvements

- Add date, region, and category slicers if useful.
- Include additional customer-focused metrics.
- Add a more detailed executive summary with verified findings.
- Publish the report to Power BI Service if required and permitted.
- Refresh the analysis when new data becomes available.

## Author

**Project:** Superstore Sales Analysis Dashboard  
**Program:** Future Intern — Data Analytics Internship  
**Tools:** Microsoft Power BI Desktop, Microsoft Excel, DAX

---

*This project demonstrates the use of data analysis and interactive visualization to communicate business performance and support evidence-based decisions.*
