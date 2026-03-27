# 🚀 Azure Data Engineering Project (Medallion Architecture)

## 📌 Project Overview
This project demonstrates an end-to-end data engineering pipeline using Azure services and Databricks. It follows the Medallion Architecture (Bronze, Silver, Gold) to process and transform data for analytics.

## 🏗️ Architecture
![Architecture](medallion.PNG)

## 🔄 Pipeline Workflow
1. Data is extracted from GitHub (CSV files)
2. Loaded into Azure Data Lake (Bronze layer)
3. Cleaned using Databricks (Silver layer)
4. Converted into business data (Gold layer)
5. Used in Power BI dashboard

## ⚙️ Key Features
- Incremental Data Load
- Data Cleaning
- SCD Type 1 (Upsert)
- Delta Lake

## 🛠️ Tools Used
- Azure Data Factory
- Azure Data Lake
- Databricks
- Power BI

## 📸 Screenshots
(Will add soon)

## 🎯 Learning
- Learned data pipeline
- Learned Azure tools
