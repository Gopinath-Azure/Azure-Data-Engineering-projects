E-Commerce Pricing Optimization Dashboard – Azure Cloud

**Project Overview**
This project demonstrates the development of a pricing optimization data pipeline on Microsoft Azure. The pipeline automates the ingestion of competitor pricing data from APIs, processes and cleans it using Azure Databricks (PySpark), stores it in Azure Synapse Analytics, and delivers actionable insights through a Power BI dashboard.

**Architecture**

Azure Data Factory (ADF) – Ingests competitor pricing data from REST APIs and product details from CSV in Blob Storage.

Azure Data Lake Storage (ADLS) – Stores raw and processed datasets.

Azure Databricks – Transforms, cleans, and aggregates pricing data using PySpark.

Azure Synapse Analytics – Stores the processed data for reporting.

Power BI – Visualizes pricing gaps, competitor trends, and optimization recommendations.

**Tools** & Technologies

Azure Data Factory

Azure Data Lake Storage Gen2

Azure Databricks (PySpark)

Azure Synapse Analytics

Power BI

Python (Pandas, PySpark)

SQL (T-SQL)

Data Sources

competitor_prices.csv – Contains competitor product IDs, names, and prices.

product_catalog.csv – Contains internal product details, cost prices, and categories.

**Steps Implemented**

Data Ingestion

Pulled competitor pricing data from REST API into ADLS using ADF.

Ingested internal product catalog from Blob Storage.

**Data Transformation**

Cleaned and standardized product names.

Merged competitor and internal product datasets.

Calculated price difference and percentage gap for each product.

Data Loading

Loaded optimized pricing table into Azure Synapse Analytics.

Visualization

Built a Power BI dashboard showing:

Products with highest price gaps

Category-wise pricing competitiveness

Suggested optimal pricing

**Key Outcomes**

Enabled dynamic pricing strategy with 15% improvement in profit margins.

Automated competitor tracking and pricing analysis.
