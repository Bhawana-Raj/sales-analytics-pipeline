# 📊 Sales Analytics Pipeline Using Python, PostgreSQL & Power BI


## 🚀 Project Overview

This project demonstrates an **end-to-end sales analytics pipeline** that transforms raw sales data into an interactive Power BI dashboard.

The complete workflow covers:

- Data extraction from Excel
- Data cleaning and transformation using Python
- Saving processed data as CSV
- Creating PostgreSQL database
- Loading cleaned data into PostgreSQL using Python
- Connecting PostgreSQL with Power BI
- Building an interactive dashboard for business insights


## 🔄 Project Workflow

```
📂 Raw Excel Dataset
          |
          ↓
🐍 Python ETL Pipeline
          |
          ↓
📄 Clean CSV Dataset
          |
          ↓
🐘 PostgreSQL Database
          |
          ↓
📊 Power BI Dashboard
          |
          ↓
💡 Business Insights
```


---

# 🎯 Objective

The objective of this project is to build a complete data pipeline that converts raw sales data into a structured database and creates meaningful business insights through interactive visualization.


---

# 🛠️ Tools & Technologies


| Technology | Purpose |
|------------|---------|
| 📗 Excel | Raw Dataset Source |
| 🐍 Python | Data Cleaning, Transformation & Database Loading |
| 🐼 Pandas | Data Processing |
| 📄 CSV | Clean Dataset Storage |
| 🐘 PostgreSQL | Database Storage |
| 🔗 SQLAlchemy | Python-PostgreSQL Connection |
| 🔌 Psycopg2 | Database Connectivity |
| 📊 Power BI | Dashboard Development |


---

# 📂 Dataset Description

The project started with a raw Excel sales dataset.

The dataset contains:

- 🆔 Order ID
- 📅 Order Date
- 👤 Customer
- 🌎 Region
- 📦 Product
- 💰 Sales
- 💵 Cost


The raw data was cleaned and transformed using Python before loading into the database.


---

# 🔄 ETL Process


## 1️⃣ Data Extraction

The raw sales data was extracted from an Excel file.

Input Dataset:

```
sales_raw_500.xlsx
```


---

## 2️⃣ Data Cleaning & Transformation Using Python 🐍

Python and Pandas were used for cleaning and preparing the dataset.

The following operations were performed:

✅ Removed duplicate records  
✅ Handled missing values  
✅ Converted date columns into proper format  
✅ Created Profit column  
✅ Extracted Year from Order Date  
✅ Extracted Month from Order Date  
✅ Standardized data format  


After transformation, the cleaned dataset was exported as a CSV file.

Output:

```
sales_cleaned_data.csv
```


---

# 🐘 PostgreSQL Database Integration


After generating the cleaned CSV file, a PostgreSQL database was created.

Python was used to connect with PostgreSQL and perform database operations.


Using Python:

✅ Established PostgreSQL connection  
✅ Created database table  
✅ Loaded cleaned CSV data into PostgreSQL table  


Database:

```
sales_db
```


Table:

```
sales_data
```


---

# 📊 Power BI Dashboard


The PostgreSQL database was connected with Power BI to create an interactive sales dashboard.


Dashboard includes:

📌 Total Sales KPI  
📌 Total Profit KPI  
📌 Profit Percentage KPI  
📈 Monthly Sales Trend  
🌎 Region-wise Profit Analysis  
📦 Product Sales Analysis  
📊 Sales Distribution  


---

# 🖼️ Dashboard Preview

<img width="1165" height="655" alt="Sales_Dashboard_Screenshot" src="https://github.com/user-attachments/assets/76d6745b-127e-406e-8eee-f3a5c09dc8a0" />






---

# 🏗️ Project Architecture


```text
                 📂 Raw Excel Dataset
                         |
                         ↓
                 🐍 Python ETL Pipeline
                         |
        -------------------------------------
        |                                   |
        ↓                                   ↓
 Data Cleaning                    Data Transformation
        |                                   |
        -------------------------------------
                         |
                         ↓
                📄 Clean CSV Dataset
                         |
                         ↓
             🐘 PostgreSQL Database Creation
                         |
                         ↓
          🔗 Python PostgreSQL Connection
              (SQLAlchemy + Psycopg2)
                         |
                         ↓
             Create Table & Load Data
                         |
                         ↓
                📊 Power BI Dashboard
                         |
                         ↓
                 💡 Business Insights
```


---




---

# 🎓 Skills Demonstrated


✅ Data Cleaning  
✅ Data Transformation  
✅ ETL Pipeline Development  
✅ Python Data Processing  
✅ Python Database Connectivity  
✅ PostgreSQL Integration  
✅ Power BI Dashboard Development  
✅ Business Intelligence Reporting  


---

# 🔮 Future Improvements


🚀 Automate ETL workflow  
☁️ Deploy database on cloud  
🔄 Schedule automatic data refresh  
📈 Add forecasting and advanced analytics  


---

# 👩‍💻 Author


## Bhawana Raj


Aspiring Data Analyst skilled in:


🐍 Python  
📊 Power BI  
🐘 PostgreSQL  
📈 Data Analytics  
🔄 ETL Pipeline Development  
