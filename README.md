# Power BI Performance Report Dashboard

This Power BI project presents a detailed performance report using a dataset covering the years 2022, 2023, and 2024. The report focuses on analyzing and comparing key business metrics across time, helping stakeholders make informed, data-driven decisions.

---

## Key Features

### Time-Based Metrics
- Year-To-Date (YTD) and Prior-Year-To-Date (PYTD) comparisons
- Month-wise breakdown for each year to observe performance trends
- Dynamic comparison between current and previous year performance

### Key Measures Tracked
- Sales
- Quantity
- Gross Profit

---

## Visuals and Insights

### YTD vs PYTD Comparison (2022–2024)
- Line and stacked column charts are used to compare YTD and PYTD for Sales, Quantity, and Gross Profit.
- The charts display performance on a month-by-month basis to highlight seasonal trends.

### Scatter Plot Analysis
- An interactive scatter plot shows Gross Profit Percentage in relation to:
  - Quantity
  - Sales
  - Gross Profit
- Users can switch between these metrics for comparative analysis.

### Drill-Down Capabilities
- Visuals allow drill-down from:
  - Year → Country → Product Type → Product Name
- This enables detailed performance insights at different hierarchy levels.

### Treemap Visualization
- A treemap shows the bottom 10 countries based on the difference between YTD and PYTD.
- Helps identify underperforming regions.

### KPI Cards
- Summary cards display:
  - YTD values
  - PYTD values
  - Change between YTD and PYTD
  - Gross Profit Percentage

---

## Dataset Information

- Time period: 2022 to 2024
- Fields include: Year, Month, Country, Product Type, Product Name, Quantity, Sales, Gross Profit, etc.

---

## Purpose

This dashboard provides both high-level summaries and detailed insights to:
- Track year-over-year business performance
- Understand profitability and volume trends
- Support data-driven decision-making across regions and product lines

---

## Tools Used

- Power BI Desktop
- DAX (Data Analysis Expressions)
- Visual interactions with slicers, drill-throughs, and hierarchical navigation

---

## How to Use

1. Open the `.pbix` file using Power BI Desktop.
2. Use the slicers to filter data by year, country, product type, etc.
3. Use the drill-down feature in charts to explore lower levels of detail.
4. View the KPI cards and visuals to analyze year-to-date and prior-year-to-date comparisons.

---

## License

This project is licensed under the [MIT License](LICENSE).
