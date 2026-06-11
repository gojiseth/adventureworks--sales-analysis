# AdventureWorks Sales Analysis Dashboard 📊

An interactive Excel dashboard analyzing AdventureWorks sales data to uncover trends, top performers, and geographic insights. Built with VLOOKUP for data merging, PivotTables, Charts, Slicers, and Timeline filters.

## Project Overview
This dashboard transforms raw sales data into actionable business insights. Used VLOOKUP to merge customer + sales tables, then built interactive visualizations to analyze seasonal trends, product performance, and country profitability.

## Tools Used
- **Microsoft Excel**: PivotTables, PivotCharts, Slicers, Timeline
- **Data Cleaning**: Removed nulls, formatted dates/currency, VLOOKUP for data merging
- **Visualization**: Line charts, Bar charts, Interactive filters

## Key Insights

### 1. Q4 Seasonality Trend
Timeline filter reveals clear Q4 pattern: 27% sales drop from Oct to Nov, then 18% recovery in Dec. Q4 2017 Total: $296,920

![Monthly Sales Trend](screenshots/monthly_trend.png)  
*Line chart showing full year monthly sales trend with Q4 peak*

### 2. Top Products by order
Top 5 products drive majority of order. Product analysis shows clear winners vs underperformers.

![Top Products](screenshots/top_products.png)  
*Bar chart ranking products by total sales amount*

### 3. Geographic Performance  
Australia leads with 41.6% profit margin vs other regions. $84.5K sales from 201 orders proves profitability over volume.

![Country Performance](screenshots/country_performance.png)  
*Bar chart comparing sales, profit, and orders by country*

## Interactive Features

### Country Slicer
Filter dashboard by Country to isolate performance. Australia selected showing $84.5K sales, $35.2K profit, 201 orders.

![Interactive Country Filter](screenshots/country_slicer.png)  
*Slicer with Australia selected + chart updating in real-time*

### Timeline Slicer  
Filter by date range to analyze seasonal patterns. Q4 2017 selected: Nov dip $85.9K vs Oct $109.3K + Dec $101.8K.

![Timeline Filter Q4](screenshots/timeline_q4.png)  
*Timeline slicer isolating Oct-Dec 2017 to show seasonal spike*

## How to Use
1. Open `AdventureWorks_Dashboard.xlsx` in Excel
2. Use Country slicer on right to filter by region
3. Use Timeline slicer to select date ranges like Q4 2017
4. All charts update automatically

## Files
- `AdventureWorks_Dashboard.xlsx` - Interactive dashboard file
- `screenshots/` - Visual proof of dashboard + insights



---
Built by [Goji Seth] | Data Analyst Portfolio Project
