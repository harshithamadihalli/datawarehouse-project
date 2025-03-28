# Building Datawarehouse

This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. 

🏗️ Data Architecture
The data architecture for this project follows Medallion Architecture Bronze, Silver, and Gold layers:

![image](https://github.com/user-attachments/assets/ee3c8527-ae4b-4f40-bdf3-b5a3a2ba8e49)

Bronze Layer: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.

Silver Layer: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.

Gold Layer: Houses business-ready data modeled into a star schema required for reporting and analytics.

## 📖 Project Overview

This project involves:

Data Architecture: Designing a Modern Data Warehouse Using Medallion Architecture Bronze, Silver, and Gold layers.

ETL Pipelines: Extracting, transforming, and loading data from source systems into the warehouse.

Data Modeling: Developing fact and dimension tables optimized for analytical queries.

Analytics & Reporting: Creating SQL-based reports and dashboards for actionable insights.

## 🚀 Project Requirements

Objective: Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

## Specifications

Data Sources: Import data from two source systems (ERP and CRM) provided as CSV files.

Data Quality: Cleanse and resolve data quality issues prior to analysis.

Integration: Combine both sources into a single, user-friendly data model designed for analytical queries.


## BI: Analytics & Reporting

Objective: Develop SQL-based analytics to deliver detailed insights into:

Customer Behavior
Product Performance
Sales Trends

These insights empower stakeholders with key business metrics, enabling strategic decision-making.
