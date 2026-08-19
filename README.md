# Healthcare Commercial & Patient Access Analytics

## Overview

An interactive healthcare analytics dashboard built using Power BI and SQL to analyze commercial performance and patient-access metrics across regions, products, and time periods.

## Objective

The project focuses on transforming structured healthcare data into actionable business insights through KPI analysis, interactive visualization, and SQL-based analysis.

## Tools & Technologies

- Power BI
- DAX
- SQL
- SQLite
- Excel

## Key Metrics

- Total Sales: $1.858M
- Total Patients: 2,870
- Claim Approval Rate: 87.0%
- Average Access Days: 9.2

## Dashboard

The Power BI dashboard provides interactive analysis of:

- Regional sales performance
- Monthly sales trends
- Claim approval rates by region
- Product-level sales performance
- Patient volume
- Average access time

![Dashboard](screenshots/dashboard.png)

## Key Insights

- West generated the highest regional sales at $800K, followed by North at $645K and South at $413K.
- West recorded the highest claim approval rate at 89.7%, while South had the lowest at 81.1%.
- Product A slightly outperformed Product B, generating $938K compared with $920K.
- Monthly sales increased consistently from $418K in January to $523K in April.
- South had both the lowest sales and lowest claim approval rate, making it an area for further investigation into potential access-related factors.

## SQL Analysis

SQL was used to perform:

1. Sales analysis by region
2. Sales analysis by product
3. Claim approval rate analysis by region
4. Monthly sales analysis
5. Identification of the top-performing region

The SQL queries are available in:

`sql/analysis.sql`

## Data Analysis Approach

The analysis involved:

1. Loading and reviewing the structured healthcare dataset
2. Validating and organizing the data
3. Creating DAX measures for key performance indicators
4. Building interactive Power BI visualizations
5. Using slicers to analyze results by region, product, and month
6. Performing SQL-based aggregation and comparison
7. Interpreting business-relevant patterns from the results

## Dataset

This project uses a synthetic healthcare dataset created for educational and portfolio purposes.

No proprietary, confidential, or patient data was used.

