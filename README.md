# 📊 Sales Data Warehouse & SSIS ETL Pipeline

## 🚀 Project Overview

This project demonstrates the design and implementation of a complete **Data Warehouse solution** using **SQL Server Integration Services (SSIS)**.

The main objective is to transform raw transactional data (OLTP) into a structured **analytical data warehouse (OLAP)** to support business intelligence and reporting.

---

## 🧠 Key Concepts Applied

* Data Warehousing
* ETL (Extract, Transform, Load)
* Star Schema Design
* Data Cleaning & Transformation
* Lookup & Data Integration

---

## 🏗️ Architecture

### 🔹 Source System (OLTP)

* Raw transactional sales data
* Stored in relational database

### 🔹 Data Warehouse (OLAP)

* Designed using **Star Schema**
* Optimized for querying and analytics

---

## 🧩 Data Model

### 📌 Dimension Tables

* 🧍 Customer Dimension
* 📦 Product Dimension
* 🧑‍💼 Salesman Dimension
* 📅 Date Dimension
* ⏰ Time Dimension

### 📌 Fact Table

* 💰 Sales Fact Table

  * Measures: Sales Amount, Quantity
  * Foreign Keys referencing all dimensions

---

## ⚙️ ETL Pipeline (SSIS)

The ETL process is implemented using SSIS packages:

### 🔄 Extract

* Data loaded from OLTP database backups

### 🔧 Transform

* Data cleaning and formatting
* Handling missing values
* Data type conversions

### 🔗 Load

* Loading into Dimension Tables
* Populating Fact Table using:

  * Lookup transformations
  * Surrogate keys mapping

---

## 🛠️ Technologies Used

* Microsoft SQL Server
* SSIS (SQL Server Integration Services)
* T-SQL

---

## 📈 Project Outcome

* Built a complete ETL pipeline
* Designed a scalable Data Warehouse
* Enabled efficient analytical reporting
* Ensured data consistency using lookups

---

## 📸 Screenshots 

![SSIS Package](/Screenshot 2026-04-21 104823.png)
![Data Flow](/Screenshot 2026-04-21 104144.png)
![Star Schema](/Screenshot 2026-04-21 104746.png)

---

## 💡 Future Improvements

* Add Power BI dashboard for visualization
* Automate ETL scheduling using SQL Server Agent
* Implement incremental loading

---

## 👩‍💻 Author

**Martina Soliman**
**Data Engineer**

---

## ⭐ Notes

This project is part of my journey in **Data Engineering & Data Warehousing**, focusing on building real-world ETL pipelines and scalable data systems.
