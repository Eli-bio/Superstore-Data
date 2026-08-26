📊 Superstore Sales Data Analysis

End-to-end data cleaning and exploratory analysis of a 10,000-row retail sales dataset, using SQL to prepare the data for reporting.

Project Objectives
Clean and validate raw retail sales data
Analyze sales and profit trends across regions and product categories
Identify top-performing regions and products
Produce a query-ready dataset for downstream dashboarding (Power BI)
Tools Used
MySQL / SQL
Excel / CSV
Files in This Repository
Superstore.csv — Raw sales dataset (10,000 rows)
data_ cleaning. sql — SQL script for staging, transformation, deduplication, and validation of the raw dataset
README.md — Project overview (this file)
Process
Staging — Loaded the raw CSV into a staging table
Cleaning — Removed duplicate records, standardized formatting, handled missing values
Validation — Checked row counts and key fields to confirm zero data quality issues after cleaning
Analysis — Queried the cleaned data to surface revenue, profit, and customer behavior trends by region and category
Notes

This is a self-directed practice project used to apply SQL data-cleaning skills to a realistic retail dataset. Dashboard and visualization work built on this cleaned dataset is in progress and will be added as a separate file/repo update.
