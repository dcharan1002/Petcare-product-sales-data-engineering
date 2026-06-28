# 🐾 PetCare Product Sales Data Engineering Pipeline

An end-to-end **Data Engineering** project built using **Databricks**,
**PySpark**, **Delta Lake**, and **Databricks SQL** following the
**Medallion Architecture (Bronze → Silver → Gold)**.

This project demonstrates production-style ETL development, data quality
validation, incremental loading, SQL analytics, workflow orchestration,
audit logging, and interactive business dashboards.

------------------------------------------------------------------------

# 🚀 Project Overview

This project simulates a real-world retail analytics platform for a pet
care company. Raw sales data is ingested into a Bronze layer, validated
and transformed into Silver, aggregated into Gold business tables, and
visualized through Databricks SQL Dashboards.

The pipeline includes:

-   Bronze → Silver → Gold Medallion Architecture
-   Data Quality Framework
-   Delta Lake Tables
-   Incremental Loading using Delta MERGE
-   SQL Analytics Views
-   Databricks SQL Dashboard
-   Workflow Orchestration
-   Audit Logging

------------------------------------------------------------------------

# 🛠 Tech Stack

-   Databricks Free Edition
-   Apache Spark (PySpark)
-   Delta Lake
-   Databricks SQL
-   Unity Catalog
-   Databricks Workflows
-   Python
-   SQL
-   Git & GitHub

------------------------------------------------------------------------

# 🏗 Architecture

``` text
Raw Data
   │
   ▼
Bronze Layer (Raw Ingestion)
   │
   ▼
Data Quality Checks
   │
   ▼
Silver Layer (Cleaned & Enriched Data)
   │
   ▼
Gold Business Layer
   │
   ▼
SQL Analytics Views
   │
   ▼
Databricks SQL Dashboard
```

------------------------------------------------------------------------

# 📂 Project Structure

``` text
01_Bronze_Ingestion
02_Data_Quality_Checks
03_Silver_Transformation
04_Gold_Business_Layer
05_Pipeline_Audit_Log
06_SQL_Analytics_Views
07_Incremental_Loading_Merge
```

------------------------------------------------------------------------

# ⚙️ Pipeline Components

## 1. Bronze Layer

-   Ingest raw sales data
-   Add ingestion metadata
-   Store as Delta table

## 2. Data Quality Checks

-   Null validation
-   Duplicate detection
-   Invalid sales/price/rating checks
-   Data quality summary table

## 3. Silver Layer

-   Clean and standardize data
-   Calculate `estimated_revenue`
-   Add transformation metadata
-   Store curated Delta table

## 4. Gold Layer

Business-ready aggregate tables: - Product Category Revenue - Vendor
Performance - Country Revenue - Customer Re-buy Analysis - Pet Type
Revenue

## 5. Audit Logging

Track: - Pipeline name - Layer - Status - Record count - Execution
timestamp

## 6. SQL Analytics Views

Reusable SQL views for dashboards and reporting.

## 7. Incremental Loading

Implemented Delta Lake `MERGE` for incremental data ingestion and
updates.

------------------------------------------------------------------------

# 📊 Dashboard

Interactive Databricks SQL Dashboard includes: - Total Revenue KPI -
Total Sales KPI - Revenue by Product Category - Country Revenue - Vendor
Performance - Re-buy Analysis - Pet Type Revenue

------------------------------------------------------------------------

# 🎯 Skills Demonstrated

-   Data Engineering
-   ETL Development
-   Apache Spark
-   PySpark
-   Delta Lake
-   Medallion Architecture
-   Data Quality Framework
-   Incremental Loading
-   SQL Analytics
-   Workflow Automation
-   Dashboard Development
-   Data Modeling

------------------------------------------------------------------------

# 📁 Dataset

**Pet Store Records 2020**

Fields include: - Product Information - Product Category - Vendor
Details - Country - Pet Type - Sales - Price - Ratings - Customer Re-buy
Status

------------------------------------------------------------------------

# 🔮 Future Enhancements

-   Azure Data Lake Storage integration
-   Azure Data Factory orchestration
-   dbt transformations
-   Great Expectations for data quality
-   MLflow integration
-   Auto Loader for streaming ingestion
-   GitHub Actions CI/CD

------------------------------------------------------------------------

# 👨‍💻 Author

**Charan Kumar Domalapati**

Master's in Data Analytics Engineering

Data Engineer \| Databricks \| PySpark \| SQL \| Azure \| Snowflake \|
Airflow \| AWS \| Power BI
