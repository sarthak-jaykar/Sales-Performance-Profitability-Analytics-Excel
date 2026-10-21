# Sales Performance & Profitability Analytics Dashboard — Excel

## Project Overview

An Excel-based retail analytics project built to evaluate sales performance, profitability, product and regional contribution, and order fulfilment lead times. The workbook combines a transaction-level dataset, cleaned and enriched data, lookup tables, summary analysis, and an interactive executive dashboard.

**Dataset:** Superstore retail transactions  
**Records:** 9,994 transaction rows  
**Tools:** Microsoft Excel, Excel Tables, formulas, PivotTables/PivotCharts, slicers, data validation, and lookup tables

> **Data note:** This is a portfolio analysis of a sample retail dataset, not a live business system. Monetary values are reported in USD to match the dataset.

## Business Questions

- How much sales and profit does the business generate overall?
- Which regions, product categories, and customer segments contribute most to sales and profit?
- Where do sales and profit performance diverge, including products with weak or negative margins?
- How long do orders take to ship, and how does fulfilment lead time vary?
- What actions could improve profitability and operational monitoring?

## Key Results

| KPI | Result |
|---|---:|
| Sales | $2,297,200.86 |
| Profit | $286,397.02 |
| Transaction rows | 9,994 |
| Units sold | 37,873 |
| Aggregate profit margin | 12.47% |
| Average shipping lead time | 3.96 days |

**KPI definitions**
- **Sales:** Sum of the transaction-level Sales field.
- **Profit:** Sum of the transaction-level Profit field.
- **Aggregate profit margin:** Total Profit ÷ Total Sales.
- **Average shipping lead time:** Average of Ship Date minus Order Date.
- **Transaction rows:** Number of rows in the dataset; this is not the same as the number of distinct order IDs.

## Analytical Findings

- The West region contributes the largest share of sales, with the East region also a major contributor.
- Technology is a leading profit-contributing category.
- Some furniture product lines show weak or negative profitability, highlighting the need to review discounting and margin performance rather than relying on sales volume alone.
- Average shipping lead time is approximately four days across the observed transactions.

## Recommendations

1. Review discount levels and profitability for product lines with weak or negative margins.
2. Monitor sales and profit together by region, category, and customer segment.
3. Investigate orders with unusually long shipping lead times and compare patterns across shipping modes.
4. Use the dashboard filters to focus reviews on specific regions and product categories before making decisions.

These are analytical recommendations based on the sample dataset; they are not evidence of changes implemented in a real company.

## Workbook Contents

The workbook `Sales_Performance_Profitability_Analytics.xlsx` contains:

| Worksheet | Purpose |
|---|---|
| `Dashboard` | Executive KPI view, charts, and interactive filters |
| `Executive_Summary` | Key observations and recommended actions |
| `Pivot_Data` | Summary tables supporting dashboard visuals |
| `Cleaned_Data` | Structured transaction table with calculated fields |
| `Lookups` | Customer, product, and location lookup tables |
| `Raw_Data` | Source transaction records |
| `Data_Dictionary` | Field descriptions and definitions |
| `Methodology_QA` | Methodology notes and reconciliation guidance |

## Screenshots

### Executive dashboard
![Executive dashboard](Screenshots/01_Executive_Dashboard_Overview.png)

### Executive summary and insights
![Executive summary](Screenshots/02_Executive_Summary_Insights.png)

### Filtered summary view
![Filtered summary view](Screenshots/03_Pivot_Data_Filtered_View.png)

### Cleaned transaction data
![Cleaned transaction data](Screenshots/04_Cleaned_Data_Fact_Table.png)

### Lookup tables
![Lookup tables](Screenshots/05_Dimension_Lookup_Tables.png)

## Repository Structure

```text
sales-performance-profitability-analytics-excel/
├── Dataset/
│   └── sales_data.csv
├── Excel Workbook/
│   └── Sales_Performance_Profitability_Analytics.xlsx
├── Screenshots/
│   ├── 01_Executive_Dashboard_Overview.png
│   ├── 02_Executive_Summary_Insights.png
│   ├── 03_Pivot_Data_Filtered_View.png
│   ├── 04_Cleaned_Data_Fact_Table.png
│   └── 05_Dimension_Lookup_Tables.png
└── README.md
```

## Skills Demonstrated

- Data preparation and structured Excel tables
- Formula-driven calculated fields and KPI analysis
- Pivot-based summaries and interactive dashboard filtering
- Profitability, regional, category, and customer-segment analysis
- Data dictionary and documented business definitions
- Converting analysis into practical business recommendations

## How to Review

1. Open the workbook in Microsoft Excel.
2. Start with the `Dashboard` worksheet.
3. Use the available filters/slicers to explore regions and categories.
4. Review `Executive_Summary` for the main findings and recommendations.
5. Inspect `Cleaned_Data`, `Lookups`, and `Data_Dictionary` for the underlying structure.

## Author
**Sarthak Jaykar**
- LinkedIn: www.linkedin.com/in/sarthak-jaykar
- GitHub: https://github.com/sarthak-jaykar
