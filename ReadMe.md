# Online Retail Customer Sales Analysis

## Project Overview

This project analyzes customer purchasing behavior using the Online Retail II dataset. The objective is to uncover sales trends, customer segments, product performance, and business insights through data analysis and interactive dashboards.

The project follows a complete data analytics workflow:

* Data Understanding
* Data Cleaning
* Exploratory Data Analysis (EDA)
* Customer Segmentation (RFM Analysis)
* Business Insights
* Interactive Dashboard Development

---

## Dataset

**Dataset:** Online Retail II

The dataset contains transactional records of an online retail store between December 2009 and December 2011.

### Features

* Invoice
* StockCode
* Description
* Quantity
* InvoiceDate
* Price
* Customer ID
* Country

---

## Project Structure

```text
online-retail-customer-sales-analysis/

│
├── data/
│   ├── raw/
│   │   └── online_retail_II.xlsx
│   │
│   └── processed/
│       └── cleaned_retail_data.csv
│
├── notebooks/
│   ├── 01_data_understanding.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_eda.ipynb
│   ├── 04_customer_analysis.ipynb
│
├── dashboards/
│   └── sales_dashboard.pbix
│
├── reports/
│
├── images/
│
├── README.md
│
└── requirements.txt
```

---

## Data Cleaning

The following cleaning steps were performed:

* Removed cancelled transactions
* Removed invalid records
* Handled missing values
* Removed negative quantities
* Removed negative prices
* Created Revenue feature
* Converted InvoiceDate to datetime format
* Generated time-based features for analysis

---

## Exploratory Data Analysis

Key analyses performed:

### Sales Analysis

* Monthly Revenue Trend
* Monthly Orders Trend
* Revenue Distribution
* Order Value Analysis

### Country Analysis

* Revenue by Country
* Orders by Country
* Customer Distribution by Country

### Product Analysis

* Top Selling Products
* Highest Revenue Products
* Quantity Analysis

---

## Customer Segmentation (RFM Analysis)

RFM analysis was used to segment customers based on:

* Recency
* Frequency
* Monetary Value

### Customer Segments

* Champions
* Loyal Customers
* Potential Loyalists
* At Risk Customers
* Others

### Key Findings

* Champions generated the highest revenue contribution.
* Loyal Customers formed the second most valuable segment.
* At Risk customers represented a significant retention opportunity.
* A small group of customers contributed a large percentage of total revenue.

---

## Dashboard Pages

### 1. Sales Overview Dashboard

Includes:

* Total Revenue
* Total Orders
* Total Customers
* Average Order Value
* Revenue by Month
* Revenue by Country
* Orders by Country

### 2. Customer Analysis Dashboard

Includes:

* Customer Segmentation Overview
* Champions Customers
* At Risk Customers
* Customer Distribution by Segment
* Revenue Contribution by Segment

### 3. Product Performance Dashboard

Includes:

* Total Products
* Top Product Revenue
* Total Quantity Sold
* Top Products by Quantity
* Revenue vs Quantity Analysis
* Revenue Share of Top Products

---

## Business Insights

### Sales Insights

* Revenue shows strong growth during the final quarter of the year.
* November generated the highest sales performance.

### Customer Insights

* Champions customers contribute the largest share of revenue.
* Customer retention programs can target At Risk customers.

### Product Insights

* A small number of products generate a large portion of revenue.
* Product demand is highly concentrated among top-selling items.

---

## Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook
* Power BI

---

## Author

Muhammad Bilal

Bachelor's Student – Data Science

Pakistan

GitHub Portfolio Project
