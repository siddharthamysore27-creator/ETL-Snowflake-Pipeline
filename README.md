# ETL-Snowflake-Pipeline

## Project Overview
This project implements an **ETL pipeline** that consolidates and transforms purchasing and supplier data into a centralized Snowflake data warehouse.  
By automating the ingestion and processing of 40+ purchase order files and supplier invoices, the pipeline creates a **single source of truth** for procurement analysis and financial reporting.

---

## Project Goals
- Design and deploy a **reliable ETL pipeline** for purchase orders and invoices.  
- Automate repetitive data ingestion tasks using Python.    
- Deliver a **structured warehouse schema** to support business reporting.  

---

## Key Outcomes
- **Automated Data Ingestion**: Loaded 40+ CSV purchase files and supplier invoices into Snowflake.  
- **Data Transformation**: Standardized formats, created calculated fields (e.g., total purchase order value), and validated records.  
- **Integrated Dataset**: Joined purchases with supplier invoices to support reconciliation and reporting.  
- **Centralized Warehouse**: Delivered a scalable Snowflake schema ready for analytics.  

---

## Tech Stack
- **Python** → File ingestion, Snowflake connector, automation  
- **Snowflake** → Data warehouse for staging, transformation, and storage  
- **SQL** → Joins, aggregations, and calculated fields    

---

## Repository Structure
- `notebooks/ETL_Project_Group_2_9.ipynb` → Jupyter notebook with pipeline code and queries.  
- `slides/ETL.pptm` → Presentation summarizing methodology and results.  
- `requirements.txt` → Python dependencies.  
- `LICENSE` → MIT License for open use.   

