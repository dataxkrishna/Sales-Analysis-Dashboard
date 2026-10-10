# Sales-Analysis-Dashboard
Interactive Power BI dashboard analysing SuperStore sales, profit, and category performance, with a 15-day sales forecast and slicers for filtering by region, category, and segment.

<img width="1301" height="748" alt="Sales_Dashobard" src="https://github.com/user-attachments/assets/8b71b322-f991-4435-bc17-a39243aa567f" />

## Problem Statement

Sales teams often have data spread across transaction records, but no quick way to see which products, regions, and customer segments are driving profit and which are losing money. This dashboard answers questions such as:

- Which categories and sub-categories generate the most sales and profit?
- Which regions or states underperform, and by how much?
- How do sales trend over time, and are there seasonal patterns?
- What sales can we reasonably expect over the next 15 days?

## Objectives

- Provide a single-page view of core sales KPIs.
- Enable self-service filtering by date, region, category, and segment.
- Identify high-margin and low-margin areas of the business.
- Offer a short-term sales forecast to support planning.

## Project Workflow

1. **Data sourcing:** Loaded the SuperStore sales dataset into Power BI Desktop.
2. **Data cleaning (Power Query):** Checked data types, removed duplicates, and standardised date fields.
3. **Data modelling:** Created relationships between fact and dimension tables and set up a date table.
4. **Measures (DAX):** Built reusable calculations for sales, profit, margin, and order counts.
5. **Visualisation:** Designed the Sales Dashboard and Sales Forecast pages with a consistent layout and colour scheme.
6. **Forecasting:** Applied Power BI's forecast feature to the time series to project the next 15 days.
7. **Validation:** Cross-checked totals against the source data to confirm accuracy.

## Skills Demonstrated

- Data cleaning and transformation with Power Query (M)
- Data modelling and relationship design in Power BI
- DAX measure creation and time intelligence
- Dashboard design and storytelling
- Time-series forecasting
- Communicating insights to non-technical audiences

## Limitations

- The forecast is based only on historical sales patterns. It does not account for promotions, holidays, or external events.
- The dataset is a sample and may not reflect current market conditions.
- The map visual depends on the accuracy of location fields in the source data.

## Future Improvements

- Add a profitability page focused on discount impact and returns.
- Include a customer-level analysis (repeat purchases, segment behaviour).
- Compare forecast accuracy against actual results once new data is available.
- Publish the report to the Power BI Service for online sharing.

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
## Tools

- Power BI Desktop
- DAX
- Power Query (M)

## Insights

- `[Add 3–5 key findings, e.g., "Technology has the highest profit margin, while Furniture has the lowest."]`

## Author

`[KrishnaPandith]` · [dataxkrishna](#) · [krishnapandith18@gmail.com](#)

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
