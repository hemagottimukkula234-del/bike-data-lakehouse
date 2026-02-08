# bike-data-lakehouse
End-to-end Databricks Lakehouse project using the Medallion Architecture (Bronze, Silver, Gold) with CSV ingestion and Unity Catalog governance.
## **Project Overview**
This project demonstrates how to build a production-style Data Lakehouse using Databricks and the Medallion Architecture (Bronze, Silver, Gold).
Raw data is ingested, cleaned, transformed, and modeled into analytics-ready datasets using PySpark and Delta Lake, following best practices used in real-world data engineering projects.
## **Architecture Overview**
Bronze Layer – Raw data ingestion (as-is, minimal transformation)
Silver Layer – Data cleansing, standardization, deduplication
Gold Layer – Business-ready dimensional and fact tables
ech Stack & Tools
## 🧰 Tech Stack & Tools
• **Cloud Platform:** Databricks (Community / Standard Edition)  
• **Programming Languages:** Python (PySpark), SQL  
• **Data Storage Format:** Delta Lake (open-source storage layer)  
• **Orchestration:** Databricks Workflows (Jobs)  
• **Version Control:** GitHub (Databricks Git integration)
## ⭐ Key Features
• Implemented an end-to-end Databricks Lakehouse using the Medallion Architecture (Bronze, Silver, Gold)  
• Ingested raw source data into Delta Lake Bronze tables  
• Performed data cleansing, standardization, and validation in the Silver layer  
• Handled null values, invalid records, and duplicate data  
• Standardized date formats and business keys for reliable joins  
• Built analytics-ready Gold layer with fact and dimension tables  
• Applied surrogate keys to support dimensional modeling  
• Used SQL to validate data and verify transformations  
• Organized code using a modular, production-style folder structure  
• Integrated GitHub for version control and code management


