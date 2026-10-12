# Power BI Dashboards

Two Power BI reports built on sample datasets: a retail finance report (sales, margin and P&L) and a sales performance report (employees, products and territories). Open the `.pbix` files in Power BI Desktop to explore them.

## 1. Retail finance dashboard

File: `retail-finance-dashboard.pbix`

| Page | Contents |
|---|---|
| High Level View | Sales timeline against prior year, P&L breakdown by period, KPI cards for sales, gross margin, EBIT margin and YoY growth, sales map by state, sales against target |
| Store View | Department and product-group treemap, department sales table with margin and YoY growth, YoY growth waterfall, store, department and state slicers |
| Top Sellers | Top-performing product groups over time (ribbon chart), sales share and YoY growth by group, store type and state slicers |

Measures include sales, prior-year sales, YoY growth % and $, cost of sales, gross margin $ and %, EBIT %, rent, and growth in gross margin and EBIT year on year.

Headline view (2019): $1.39bn sales against a $1.22bn target, gross margin 55.18%, EBIT margin 17.62%.

## 2. Sales performance dashboard

File: `sales-performance-dashboard.pbix`

| Page | Contents |
|---|---|
| Home | Employee table with photo, sales group, country and total lifetime sales; slicers for sales group, order year and country |
| Employee Dashboard | Employee profile card, yearly sales summary with prior year, YoY % and YTD, sales by product category and subcategory, sales by territory and reseller, YTD against prior-year YTD |

Measures include total sales, prior-year sales, YoY %, YTD, prior-year YTD and lifetime sales. Data is the Adventure Works sample dataset.

## Skills shown

- Data modelling across fact and dimension tables
- DAX measures for time intelligence (prior year, YoY, YTD)
- P&L and KPI reporting
- Interactive report design: slicers, drill-down, buttons and navigation
- Custom visuals (sunburst, image viewer, timeline)

## Tools

Power BI Desktop, DAX.