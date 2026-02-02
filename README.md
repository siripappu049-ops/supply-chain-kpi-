# Supply Chain KPI Dashboard (Google Sheets)

A lightweight, portfolio-style dashboard built in Google Sheets to track key supply chain KPIs per SKU.

## What this dashboard shows
- Average Daily Sales (ADS)
- Average Lead Time (days)
- Reorder Point (simple: ADS × Lead Time)
- Fill Rate (simple proxy: % of days with On Hand > 0)

## How it works (Sheets tabs)
- **Raw_Data**: sample transaction-level data (sales, receipts, on-hand, lead time)
- **KPI_Calc**: formulas to compute KPIs per SKU
- **dashboard**: KPI table + charts for quick visualization

## Screenshots
### KPI Table
![KPI Table](kpi-table.png)

### Charts
![Charts](charts.png)

## Tools used
- Google Sheets (formulas + charts)
- GitHub (documentation)

## Notes / Future improvements
- Add Safety Stock and Service Level (Z-score based)
- Add stockout alerts (conditional formatting)
- Add weekly/monthly trends and slicers
