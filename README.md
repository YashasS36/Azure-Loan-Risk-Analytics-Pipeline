# Azure Loan Risk Analytics Pipeline

An end-to-end Loan Risk Analytics project built using Azure Data Factory, Azure Databricks, PySpark, Delta Lake, and Power BI.

## Project Overview

This project demonstrates a cloud-based data pipeline for analyzing loan customer data and identifying risk categories based on credit scores.

## Architecture

Azure Data Factory
→ Azure Storage
→ Azure Databricks (PySpark)
→ Delta Lake (Gold Layer)
→ Power BI Dashboard

## Technologies Used

- Azure Data Factory
- Azure Storage
- Azure Databricks
- PySpark
- Delta Lake
- SQL
- Power BI

## Key Features

- Automated loan data ingestion using Azure Data Factory
- Data cleaning and transformation with PySpark
- Risk classification using customer credit scores
- Delta table creation for analytics-ready data
- Business insights and visualization in Power BI

## Analytics Performed

- Loan Status Analysis
- Risk Category Segmentation
- Average Loan Amount by Region
- Credit Score Analysis
- Customer Repayment Insights

## Sample Screenshots


### ADF Pipeline
![ADF Pipeline](screenshots/01_ADF_Pipeline.png)

### Gold Layer Risk Analytics
![Gold Layer](screenshots/05_Gold_Layer_RiskCategory.png)

### Delta Tables
![Delta Tables](screenshots/06_Delta_Tables.png)

## Outcome

Successfully built an end-to-end Azure data pipeline that transforms raw loan data into analytics-ready datasets for risk assessment and business reporting.

---
**Skills Demonstrated:** Azure Data Factory, Databricks, PySpark, ETL, Delta Lake, SQL, Power BI, Data Analytics
