# 🏬 Retail Chain Sales Analytics Platform

An end-to-end Retail Data Engineering and Analytics Platform built using Python, Apache Spark, Snowflake, Advanced SQL, and Power BI.

This project demonstrates the design and implementation of a scalable data warehouse architecture, ETL/ELT pipelines, distributed data processing, performance optimization, and interactive business dashboards.

---

## 📌 Project Overview

The Retail Chain Sales Analytics Platform centralizes retail sales data and transforms it into actionable business insights through:

- Data Warehouse Design (Star Schema)
- Advanced SQL Analytics
- Python-based ETL/ELT Pipelines
- Apache Spark (Batch & Streaming)
- Snowflake Optimization
- Security & Governance (RBAC, Masking)
- Performance Tuning
- Interactive BI Dashboards

---

## 🏗 Architecture Overview

The system follows a layered enterprise architecture:

### 1️⃣ Data Sources
- Historical Retail Sales (CSV)
- Simulated Real-Time Streaming Data
- External APIs / Operational Systems

### 2️⃣ Data Ingestion
- Python ETL Pipelines
- Apache Spark Batch Processing
- Apache Spark Structured Streaming

### 3️⃣ Data Processing
- Data Validation
- Schema Standardization
- KPI Aggregations
- Business Logic Transformations
- Window Function Calculations

### 4️⃣ Data Warehouse (Snowflake)
- Centralized Snowflake Storage
- Star Schema Design:
  - FACT_SALES
  - DIM_CUSTOMER
  - DIM_PRODUCT
  - DIM_STORE
  - DIM_DATE

### 5️⃣ Performance & Governance
- Clustering Keys (ORDER_DATE, STORE_ID)
- Time Travel & Recovery
- Role-Based Access Control (RBAC)
- Dynamic Data Masking
- Resource Monitoring

### 6️⃣ Analytics & BI Layer
- Executive KPI Dashboard
- Total Revenue
- YoY Growth
- Average Order Value
- Top-Selling Products
- Customer Segmentation
- Power BI / Snowflake Dashboards

---

## 📊 Data Warehouse Design

The project uses a **Star Schema** for optimized analytical performance.

### Fact Table
- FACT_SALES
  - Sales_Amount
  - Quantity
  - Discount
  - Profit
  - Foreign Keys (Product_ID, Customer_ID, Store_ID, Date_ID)

### Dimension Tables
- DIM_CUSTOMER
- DIM_PRODUCT
- DIM_STORE
- DIM_DATE

Why Star Schema?
- Faster query performance
- Simplified joins
- Optimized for BI tools
- Industry standard for analytics

---

## 🔎 Advanced SQL Implementation

Implemented SQL Concepts:

- Common Table Expressions (CTE)
- Window Functions:
  - ROW_NUMBER()
  - LAG()
  - LEAD()
  - RANK()
- Aggregations
- Partitioning
- Indexing

### Sample Analytics Use Cases:
- Top-selling products per region
- Year-over-Year revenue comparison
- Customer retention analysis
- Running revenue totals

---

## 🔄 ETL / ELT Pipelines

Developed Python-based ETL pipelines for:

- Data Cleaning
- Null Handling
- Schema Validation
- Deduplication
- Incremental Data Loading

Spark is used for:
- Large-scale aggregations
- Real-time streaming simulation
- Distributed data processing

---

## ❄ Snowflake Optimization

- Clustering Keys
- Query Result Caching
- Warehouse Auto-Suspend
- Resource Monitors
- Time Travel for data recovery
- Semi-structured data handling (VARIANT)

---

## 🔐 Security & Governance

- Role-Based Access Control (RBAC)
- Data Masking Policies
- Least Privilege Access Model
- Audit Monitoring

---

## 📈 Dashboard & Business Insights

Interactive dashboard includes:

- Total Revenue KPI
- Revenue Growth %
- Average Order Value
- Category-wise Sales
- Monthly Revenue Trend
- Top 5 Products
- Customer Segmentation

Tools Used:
- Power BI
- Snowflake Dashboard

---

## 🛠 Technology Stack

- Python
- SQL
- Apache Spark
- Snowflake
- Power BI
- Git & GitHub

---

## 🚀 How to Run the Project

1. Clone the repository
2. Install required dependencies
3. Run ETL pipeline
4. Execute Spark jobs
5. Load data into Snowflake
6. Connect BI tool to Snowflake

---

## 📌 Key Highlights

✔ End-to-End Data Engineering Pipeline  
✔ Enterprise-Level Data Warehouse  
✔ Advanced SQL Analytics  
✔ Real-Time Processing Simulation  
✔ Secure & Governed Architecture  
✔ Performance Optimized  
✔ Executive Dashboard  

---

## 👨‍💻 Team Members

- Shubhranshu Acharya – Data Warehouse & Advanced SQL
- Aditya Prakash Acharya – ETL & Spark Processing
- Jyotirmaye Acharya – Snowflake Optimization & Dashboard

---

## 📄 License

This project is developed for academic and portfolio demonstration purposes.

---

## ⭐ If You Like This Project

Give it a star ⭐ on GitHub and feel free to connect!
