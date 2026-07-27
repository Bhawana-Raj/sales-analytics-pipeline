# Sales Analytics Pipeline Using Python, PostgreSQL & Power BI


## Project Overview

This project demonstrates an end-to-end sales analytics pipeline that transforms raw sales data into an interactive Power BI dashboard.

The complete workflow includes data extraction, cleaning, transformation, database loading, and visualization.


## Project Workflow


Raw Excel Dataset

↓

Python Data Cleaning & Transformation

↓

Clean CSV Dataset

↓

Create PostgreSQL Database

↓

Connect PostgreSQL with Python

↓

Create Table & Load Clean Data into PostgreSQL

↓

Connect PostgreSQL with Power BI

↓

Interactive Dashboard



---

# Objective

The objective of this project is to build a complete data pipeline that converts raw sales data into meaningful business insights using Python, PostgreSQL, and Power BI.


---

# Tools & Technologies


| Technology | Purpose |
|------------|---------|
| Excel | Raw Data Source |
| Python | ETL Process & Database Loading |
| Pandas | Data Cleaning & Transformation |
| CSV | Intermediate Clean Data Storage |
| PostgreSQL | Database Storage |
| SQLAlchemy | Database Connection |
| Psycopg2 | PostgreSQL Integration |
| Power BI | Dashboard Visualization |


---

# Dataset

The project started with a raw Excel sales dataset.

Dataset fields include:

- Order ID
- Order Date
- Customer
- Region
- Product
- Sales
- Cost


---

# Data Cleaning & Transformation

Python and Pandas were used to prepare the raw dataset.

Steps performed:

- Removed duplicate records
- Handled missing values
- Converted date columns
- Created Profit column
- Extracted Year information
- Extracted Month information
- Standardized data format


After transformation, the cleaned dataset was exported as a CSV file.


---

# PostgreSQL Database Integration

A PostgreSQL database was created for storing the cleaned sales data.

The database connection was established using Python.

Using Python:

- PostgreSQL connection was created
- Table was created
- Clean CSV data was loaded into the PostgreSQL table


---

# Power BI Dashboard

The PostgreSQL database was connected with Power BI.

An interactive dashboard was created to analyze sales performance.


Dashboard contains:

- Total Sales KPI
- Total Profit KPI
- Profit Percentage KPI
- Monthly Sales Trend
- Region-wise Profit Analysis
- Product Sales Analysis
- Sales Distribution


---

## Project Architecture

The project follows an end-to-end data pipeline architecture:

```text
                    Raw Excel Dataset
                           |
                           |
                           v
              Python ETL Pipeline (Pandas)
                           |
                           |
        -----------------------------------------
        |                                       |
        v                                       v
 Data Cleaning                         Data Transformation
        |                                       |
        -----------------------------------------
                           |
                           v
                 Clean CSV Dataset
                           |
                           |
                           v
              PostgreSQL Database Creation
                           |
                           |
                           v
          Python - PostgreSQL Connection
          (SQLAlchemy + Psycopg2)
                           |
                           |
                           v
          Create Table & Load Clean Data
                into PostgreSQL
                           |
                           |
                           v
                Power BI Data Connection
                           |
                           |
                           v
              Interactive Sales Dashboard
                           |
                           |
                           v
                 Business Insights
```



---

# Skills Demonstrated

- Data Cleaning
- Data Transformation
- ETL Pipeline Development
- Python Database Connectivity
- PostgreSQL Integration
- Data Visualization
- Power BI Dashboard Development


---

---

# Author

## Bhawana Raj

Skills:

- Python
- Pandas
- PostgreSQL
- Power BI
- Data Analytics
- ETL Pipeline Development
