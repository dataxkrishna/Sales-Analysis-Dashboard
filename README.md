# Sales-Analysis-Dashboard
Interactive Power BI dashboard analysing SuperStore sales, profit, and category performance, with a 15-day sales forecast and slicers for filtering by region, category, and segment.

# SuperStore Sales Dashboard

An interactive Power BI dashboard analysing SuperStore sales performance, with a 15-day sales forecast.
<img width="1290" height="752" alt="SalesForecassting" src="https://github.com/user-attachments/assets/18d0922b-6efb-4eb0-a511-7b8ac11951be" />

## Overview

This project turns SuperStore transaction data into a two-page report:

1. **Sales Dashboard**: KPI cards, category and region breakdowns, a map view, trend charts, and slicers for interactive filtering.
2. **Sales Forecast**: a 15-day forecast built on historical sales, shown as line charts with a breakdown by category.

## Pages

| Page | What it shows |
|------|---------------|
| Sales Dashboard | Headline KPIs (sales, profit, orders, quantity), bar and donut charts by category, sub-category and segment, stacked area trends over time, a geographic map, and slicers |
| Sales Forecast | 15-day sales forecast with line charts and a category-level bar chart |

## Dashboard Features

- **KPI cards** for key totals at a glance
- **Interactive slicers** to filter by date, region, category, and segment
- **Cross-filtering** between visuals
- **Map visual** for geographic sales distribution
- **Forecasting** for the next 15 days

## Data

- **Source:** SuperStore sales dataset (`[add source link or file name]`)
- **Date range:** `[e.g., Jan 2015 – Dec 2018]`
- **Main tables:** `[e.g., Orders, Returns, People]`

> The raw data is not included in this repository. Place your source file in a `data/` folder and refresh the model in Power BI, or update the connection string to match your environment.

## Key Measures

Document your DAX measures here, for example:

```dax
Total Sales = SUM(Orders[Sales])
Total Profit = SUM(Orders[Profit])
Profit Margin % = DIVIDE([Total Profit], [Total Sales])
```

## How to Use

1. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free).
2. Open `sales_dashboard.pbix`.
3. If prompted, update the data source path under **Transform data → Data source settings**.
4. Click **Refresh** to load the latest data.

## Tools

- Power BI Desktop
- DAX
- Power Query (M)

## Insights

- `[Add 3–5 key findings, e.g., "Technology has the highest profit margin, while Furniture has the lowest."]`

## Author

`[KrishnaPandith]` · [dataxkrishna](#) · [Email](#)

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
