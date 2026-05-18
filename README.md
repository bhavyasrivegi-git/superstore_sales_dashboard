# Superstore Sales Performance Dashboard

## Problem Statement
Analyze 4 years of Superstore sales data to identify 
regional performance gaps, profitable product categories, 
and monthly sales trends to drive business decisions.

## Dataset
- Source: Kaggle — Superstore Sales Dataset
- Size: 9,994 rows, 21 columns
- Period: 2014 to 2017

## Tools Used
- Python (Pandas) — data cleaning and preprocessing
- Power BI — interactive dashboard creation
- Excel — data verification

## Steps Followed
1. Loaded raw CSV data into Python
2. Fixed date columns and extracted Year and Month
3. Created Profit Margin column using formula
4. Saved clean data and loaded into Power BI
5. Built interactive dashboard with KPI cards and charts
6. Added slicers for Year and Region filtering

## Key Insights
1. West region leads in both Sales (725K) and Profit (108K)
2. Central region has lowest profit margin (7.9%) despite 
   being second highest in sales (501K) — indicating 
   excessive discounting
3. Technology is the most profitable category (145K profit) 
   while Furniture has lowest profit (18K) despite high sales

## Dashboard Preview
![Dashboard](Dashboard_analaysis_full.png)

## How to Run
1. Clone this repository
2. Open superstore_cleaning.ipynb in Jupyter Notebook
3. Run all cells to generate clean data
4. Open superstore_sales_dashboard.pbix in Power BI Desktop
