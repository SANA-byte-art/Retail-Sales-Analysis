# Retail Sales Analysis Dashboard

An interactive Microsoft Excel dashboard built to explore retail sales performance across products, stores, customer segments, payment methods, and promotions.

## Dashboard Preview

![Retail Sales Dashboard](Retail_Sales_Dashboard.png)

## Project Overview

This project analyses a retail sales dataset containing **100 records** from **1 January 2025 to 30 June 2025**. The Excel workbook uses PivotTables, PivotCharts, slicers, and formulas to summarise sales performance and make key patterns easier to explore.

## Key Performance Indicators

| Metric | Result |
|---|---:|
| Total Sales | ₹46,32,95,677 |
| Total Units Sold | 15,968 |
| Unique Products | 30 |
| Unique Stores | 4 |
| Date Range | 1 Jan 2025 – 30 Jun 2025 |

## Dashboard Features

The dashboard includes **7 charts** and **4 slicers**.

### Charts

- Sales Trend Over Time
- Sales by Region
- Sales by Product Category
- Sales by Product Name
- Payment Method Usage
- Customer Segment Performance
- Promotion Effectiveness

### Interactive Filters

- Store Region
- Customer Segment
- Product Category
- Promotion Applied

The slicers update the PivotCharts connected to them. The **Sales Trend Over Time** chart is currently not connected to the slicers and remains unchanged when those filters are applied.

## Tools and Excel Features Used

- Microsoft Excel
- PivotTables and PivotCharts
- Slicers and report connections
- Excel formulas, including `SUM`, `SUMPRODUCT`, and `COUNTIF`
- Dashboard layout and chart formatting

## Files in This Repository

| File | Description |
|---|---|
| `Sales2_Final.xlsx` | Excel workbook containing the source data, PivotTables, and dashboard |
| `Retail_Sales_Dashboard.png` | Full dashboard screenshot |

## Data Notes and Limitations

- The dataset contains 100 records, so findings describe this dataset and should not automatically be generalised to a larger retail business.
- The same Store IDs appear under multiple regions in the dataset. The Store ID-to-region mapping should be verified before using regional comparisons for business decisions.
- Promotion comparisons show observed sales values; they do not establish that a promotion caused a change in sales.
- The Sales Trend Over Time chart is not currently connected to the dashboard slicers.

## Purpose

This project demonstrates the use of Excel for retail sales analysis, KPI reporting, PivotTable-based summaries, and dashboard visualisation.
