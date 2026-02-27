# 🏬 Retail Chain Sales Analytics Platform  

An End-to-End Retail Data Engineering & Analytics Solution built using **Python, Apache Spark, Snowflake, Advanced SQL, and Power BI**.

This project demonstrates the complete lifecycle of building a scalable data platform — from raw CSV ingestion to enterprise-grade analytics dashboards with security, optimization, and governance.

---

# 📌 1️⃣ Problem Statement

Retail businesses generate large volumes of transactional sales data across multiple stores and regions. However:

- Data exists in raw CSV formats.
- No centralized data warehouse.
- Limited real-time KPI visibility.
- Manual reporting processes.
- No structured security or governance.

## 🎯 Objective

Design and implement a scalable Retail Analytics Platform that:

- Centralizes retail data into Snowflake  
- Implements an enterprise Star Schema  
- Supports Batch & Streaming processing  
- Enables Advanced SQL analytics  
- Ensures performance optimization  
- Implements RBAC & Data Masking  
- Delivers executive-level BI dashboards  

---

# 🏗 2️⃣ Architecture Overview

The system follows a layered enterprise architecture:

## 🔹 Data Sources
- Raw Retail Sales CSV Files  
- Simulated Streaming Input  
- External Operational Data  

## 🔹 Data Ingestion
- Python ETL Pipeline  
- Apache Spark Batch Processing  
- Apache Spark Structured Streaming  

## 🔹 Data Processing
- Data Cleaning  
- Column Standardization  
- Business Logic Transformations  
- KPI Aggregations  
- Window Function Calculations  

## 🔹 Data Warehouse (Snowflake)

Star Schema Design:

- FACT_SALES  
- DIM_CUSTOMER  
- DIM_PRODUCT  
- DIM_STORE  
- DIM_DATE  

## 🔹 Performance & Governance
- Clustering Keys  
- Time Travel  
- Role-Based Access Control (RBAC)  
- Dynamic Data Masking  
- Resource Monitoring  

## 🔹 Analytics Layer
- Power BI Executive Dashboard  
- Snowflake Dashboards  

---

# 📊 3️⃣ Data Warehouse Design

This project uses a **Star Schema** optimized for analytical workloads.

## ⭐ Fact Table

**FACT_SALES**

- Sales_Amount  
- Quantity  
- Discount  
- Profit  
- Product_ID  
- Customer_ID  
- Store_ID  
- Date_ID  

## ⭐ Dimension Tables

- DIM_CUSTOMER  
- DIM_PRODUCT  
- DIM_STORE  
- DIM_DATE  

### ✅ Why Star Schema?

- Faster aggregations  
- Simplified joins  
- Optimized for BI tools  
- Industry-standard analytics model  

---

# 🔎 4️⃣ Advanced SQL Implementation

Implemented advanced analytical SQL concepts:

- Common Table Expressions (CTE)  
- Window Functions:
  - ROW_NUMBER()  
  - RANK()  
  - LAG()  
  - LEAD()  
- Running Totals  
- Year-over-Year Growth  
- Partitioning  
- Performance tuning  

## 📌 Business Use Cases

- Top-selling products per year  
- YoY revenue growth  
- Monthly revenue trends  
- Customer revenue ranking  
- Sales decile segmentation  

---

# 🔄 5️⃣ ETL Pipeline

Developed a structured Python-based ETL pipeline:

## Extraction
- Read raw CSV files  
- Schema validation  
- Null value detection  

## Transformation
- Column standardization  
- Date conversion  
- Numeric validation  
- Deduplication  
- KPI preparation  

## Loading
- Incremental data loading into Snowflake  
- Batch ingestion support  

---

# ⚡ 6️⃣ Apache Spark (Batch + Streaming)

## Batch Processing
- Large-scale aggregations  
- Historical KPI computation  
- Monthly & yearly revenue calculations  

## Structured Streaming
- Simulated real-time ingestion  
- Incremental data updates  
- Near real-time analytics support  

Spark enables distributed processing, scalability, and fault tolerance.

---

# ❄ 7️⃣ Snowflake Optimization

Implemented Snowflake performance features:

- Clustering on ORDER_DATE & STORE_ID  
- Warehouse Auto-Suspend  
- Query Result Caching  
- Resource Monitoring  
- Time Travel Recovery  
- Semi-Structured Data Handling (VARIANT)  

---

# 🔐 8️⃣ Security & Governance

Enterprise-level controls implemented:

- Role-Based Access Control (RBAC)  
- Least Privilege Access Model  
- Dynamic Data Masking Policies  
- Secure warehouse usage  
- Audit monitoring  

---

# 📈 9️⃣ Executive Dashboard

Interactive BI dashboard includes:

- Total Revenue  
- Revenue Growth %  
- Average Order Value  
- Total Orders  
- Category-wise Revenue  
- Monthly Sales Trends  
- Top 5 Products  
- Customer Segmentation  

### Tools Used:
- Power BI  
- Snowflake Dashboard  

---

# 🗂 1️⃣0️⃣ Project Structure

```
Retail-Chain-Sales-Analytics-Platform/
│
├── Apache_Spark_batch + streaming/
├── Cleaned data/
├── Data Visualization (POWER BI)/
├── ETL Pipeline/
├── Raw data/
├── Star Schema SQL/
├── Warehouse/
│
├── Advanced_sql_analytics.sql
├── Project Presentation.pdf
├── README.md
├── Security_RBAC_Data Masking_ Governance.sql
├── snowflake_optimization.sql
```

This modular structure ensures:

- Clean separation of concerns  
- Maintainable codebase  
- Enterprise-ready organization  
- Easy project validation  

---

# 🛠 1️⃣1️⃣ Technology Stack

- Python  
- SQL  
- Apache Spark  
- Snowflake  
- Power BI  
- Git & GitHub  

---

# 🚀 1️⃣2️⃣ Execution Workflow

1. Setup Snowflake Warehouse  
2. Execute Star Schema SQL  
3. Run ETL Pipeline  
4. Execute Spark Batch & Streaming  
5. Load processed data into Snowflake  
6. Run Advanced SQL queries  
7. Connect Power BI to Snowflake  
8. Build Executive Dashboard  

---

# 🌟 1️⃣3️⃣ Key Highlights

✔ End-to-End Data Engineering Pipeline  
✔ Enterprise Star Schema Design  
✔ Advanced SQL Analytics  
✔ Distributed Processing with Spark  
✔ Snowflake Optimization & Governance  
✔ Secure RBAC Implementation  
✔ Executive-Level Dashboard  
✔ Scalable & Production-Ready Architecture  

---

# 👥 Team Members

- Shubhranshu Acharya  
- Aditya Prakash Acharya  
- Jyotirmaye Acharya  

---

# 📄 License

Developed for academic and professional portfolio demonstration purposes.