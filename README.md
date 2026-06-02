# Retail Data Processing and Business Insights Generation

## Project Overview

This project implements an end-to-end retail analytics pipeline designed to ingest, clean, transform, model, and visualize retail transaction data. The solution addresses common data quality challenges including missing values, duplicate records, inconsistent product information, invalid transactions, and protection of personally identifiable information (PII).

The project was developed using Python for data processing, MySQL for dimensional modeling, and Power BI for business intelligence reporting and visualization.

---

## Business Objective

ABC Retail Solutions receives retail transaction data from multiple source systems. Due to inconsistencies and data quality issues, generating accurate business insights becomes challenging. The objective of this project is to create a reliable analytics pipeline that transforms raw transactional data into a validated and analytics-ready dataset for reporting and decision-making.

---

## Tech Stack

* Python
* Pandas
* MySQL
* Power BI
* Jupyter Notebook
* Git & GitHub

---

## Project Architecture

```text
Raw Retail Datasets
        │
        ▼
Data Ingestion
        │
        ▼
Data Cleaning & Validation
        │
        ▼
Data Transformation
        │
        ▼
MySQL Star Schema Data Model
        │
        ▼
Power BI Dashboard
        │
        ▼
Business Insights
```

---

## Star Schema Data Model

The analytical layer was designed using a Star Schema to improve query performance and simplify reporting.

### Fact Table

* Fact_Sales

### Dimension Tables

* Dim_Customer
* Dim_Product
* Dim_Category
* Dim_Location
* Dim_Date

### Data Model Screenshot


<img width="1048" height="736" alt="WhatsApp Image 2026-06-01 at 8 30 59 PM" src="https://github.com/user-attachments/assets/655d8aae-e167-4584-bbdc-522a7fa65093" />




## Power BI Dashboard

The dashboard was designed to provide business stakeholders with interactive insights into sales performance, customer behavior, category trends, product performance, and regional analysis.

### Dashboard 1 – Executive Sales Overview
<img width="1264" height="712" alt="WhatsApp Image 2026-06-02 at 6 06 03 AM" src="https://github.com/user-attachments/assets/3236360c-aa2f-42cb-9e5d-23132bbc8ed6" />


### Dashboard 2 – Product & Category Performance


<img width="1264" height="711" alt="image" src="https://github.com/user-attachments/assets/5921ce5a-afae-4155-b801-94e4883a4c99" />

### Dashboard 3 – Regional & Customer Insights


<img width="1279" height="721" alt="WhatsApp Image 2026-06-02 at 6 05 01 AM" src="https://github.com/user-attachments/assets/c01ef129-80cf-4713-a159-4a378cb1c555" />


## Key Features

* Multi-source retail data ingestion
* Data cleaning and preprocessing
* Duplicate record handling
* Missing value treatment
* Product and category standardization
* PII masking
* Revenue and KPI calculations
* Star schema dimensional modeling
* Interactive Power BI dashboards

---

## Key Business Insights

* Generated approximately 1.16 Billion in total revenue.
* Processed over 8,000 retail transactions.
* Electronics emerged as the highest revenue-generating category.
* Laptop was identified as the top-performing product.
* Revenue distribution remained balanced across Online and Offline channels.
* Chennai contributed the highest city-level revenue.
* UPI emerged as the most preferred payment method.

---

## Dashboard KPIs

* Total Revenue
* Total Orders
* Units Sold
* Average Order Value (AOV)
* Revenue by Category
* Revenue by City
* Revenue by Sales Channel
* Monthly Revenue Trends


---

## Outcome

The project successfully delivers a scalable retail analytics solution that improves data quality, enables business intelligence reporting, and supports data-driven decision-making through interactive dashboards and actionable insights.
