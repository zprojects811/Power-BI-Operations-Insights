# Operations Dashboard

## Overview
This Power BI project shows sales performance with cleaned data, relationships, and interactive dashboards.

## Data Cleaning
- Removed duplicates
- Fixed date formats
- Handled negative/zero values in Price & Quantity
- Trim & Clean text columns
- Standardized country names

## Data Model
- Orders ↔ Customers via CustomerName
- Orders ↔ Products via Product
- Calendar table for Time Intelligence

## Measures
- Total Sales, Total Orders
- Unique Customers
- Sales YTD, Sales LY
- Running Sales (Cumulative)

## Visualizations
- Summary/Executive page
- Trend charts
- Top Products by Sales
- Drill-through pages
