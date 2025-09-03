# ETL Snowflake Pipeline

## Project Overview  
This project implements an **ETL (Extract, Transform, Load) pipeline** that integrates multiple raw datasets into a centralized **Snowflake data warehouse**.  
Data sources include purchase order CSV files, supplier transaction XML, a PostgreSQL schema, and U.S. Census ZIP code geography data.  

The pipeline automates ingestion, applies transformations, and produces **clean, analytics-ready tables** that support procurement and supplier reporting.  

---

## Goals Achieved  
- Consolidated 40+ purchase order CSV files into structured Snowflake tables  
- Parsed supplier transaction data from XML format  
- Integrated relational schema from PostgreSQL dump  
- Enriched records with U.S. Census ZIP code geography  
- Created calculated fields such as purchase order totals and supplier-level spend  
- Delivered a scalable Snowflake schema supporting downstream analytics  

---

## Outcomes  
- **Unified dataset** combining purchase orders, invoices, and supplier transactions  
- **Automated ingestion** reducing manual data processing  
- **Standardized transformations** ensuring data quality and consistency  
- **Analytics-ready warehouse** powering procurement and financial reporting  

---

## Tech Stack  
- **Python** → Automation, Snowflake connector, XML/CSV ingestion  
- **Snowflake** → Cloud data warehouse for storage, transformations, and queries  
- **SQL** → Joins, aggregations, and calculated fields   

---

## Repository Contents
- [Data](https://github.com/siddharthamysore27-creator/ETL-Snowflake-Pipeline/tree/main/Data) → Raw datasets (CSV purchase orders, supplier transactions XML, PostgreSQL schema, ZIP code geography)  
- [ETL_Project.ipynb](https://github.com/siddharthamysore27-creator/ETL-Snowflake-Pipeline/blob/main/ETL_Project.ipynb) → Jupyter notebook with ETL pipeline implementation  
- [LICENSE](https://github.com/siddharthamysore27-creator/ETL-Snowflake-Pipeline/blob/main/LICENSE) → MIT License for open use 
