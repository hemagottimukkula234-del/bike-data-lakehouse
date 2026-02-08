# bike-data-lakehouse
End-to-end Databricks Lakehouse project using the Medallion Architecture (Bronze, Silver, Gold) with CSV ingestion and Unity Catalog governance.
## **Project Overview**
This project demonstrates how to build a production-style Data Lakehouse using Databricks and the Medallion Architecture (Bronze, Silver, Gold).
Raw data is ingested, cleaned, transformed, and modeled into analytics-ready datasets using PySpark and Delta Lake, following best practices used in real-world data engineering projects.
## **Architecture Overview**
• **Bronze Layer:** Raw data ingestion with minimal transformations  
• **Silver Layer:** Data cleansing, standardization, validation, and deduplication  
• **Gold Layer:** Business-ready dimensional and fact tables optimized for analytics and reporting
## 🧰 Tech Stack & Tools
• **Cloud Platform:** Databricks (Community / Standard Edition)  
• **Programming Languages:** Python (PySpark), SQL  
• **Data Storage Format:** Delta Lake (open-source storage layer)  
• **Orchestration:** Databricks Workflows (Jobs)  
• **Version Control:** GitHub (Databricks Git integration)



