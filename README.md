# DATA WAREHOUSE AND ANALYTICS PROJECT
This project demonstrates a comprehensive data warehousing and analytical solution, from building a data warehouse to generate actionable insights.
Designed as a Portfolio Project and it highlights Industry best practices in data engineering and analytics.

---
## Data Architecture
The data architecture for this project follows Medallion Architecture **Bronze**, **Silver** and **Gold** Layers.

 **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV files to SQL Server Database.
 **Silver Layer**: This Layer includes data cleansing, standardization and Normalization processes to prepare for Analysis.
 **Gold Layer**  : Business-ready data modelled into a Star Schema required for Reporting and Analytics.

 ---
 ## PROJECT OVERVIEW
 This Project involves:
 1.**Data Architecture**    : Designing a Modern Warehouse using Medallion Architecture.
 2.**ETL Pipelines**        : Extrating, Transforming and Loading data from source systems into the warehouse.
 3.**Data Modelling**       : Developing fact and dimention tables optimized for analytical queries.
 4.**Analytics & Reporting**: Creating SQL-based Reports and Dashboards for actionalble Insights

 ## Preject Requirements

 #### Objective
 Develop a Modern Warehouse using SQL Server to cinsolidate sales data, enabling analytical reporing and informed decision-making.

 #### Specification
 - **Data Sources** : Import data from two source systems(ERP & CRM) provided as CSV files.
 - **Data Quality** : Clean and resolve data quality issues prior to analysis.
 - **Integration**  : Combine both sources into a single, user-friendly data model designed for analytical queries.
 - **Scope**        : Focus on the latest dataset only,historization pf data is not required.
 - **Documentation**: Provide clear documentation of the data model to support both business stakeholderss and analytics teams.

---
### BI: Analytics & Reporting (Data Analysis)

#### Objective
Develop SQL-based analytics to deliver detailed insights into:

- **Customer Behaviour**
- **Product Performance**
- **Sales Trends**
These insights empower stakeholders with key business metrics, enabling decision-making


## License
This Project is licensed under the [MIT License].


