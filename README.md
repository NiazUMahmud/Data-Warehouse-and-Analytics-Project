# Data Warehouse and Analytics Project
This repository is for the Data Warehousing ETL process in SQL. A comprehensive, portfolio-ready solution demonstrating end-to-end data warehousing and analytics. This project showcases industry best practices in the ETL process, from extracting the data from multiple sources, transforming it, and finally loading it into the Data Warehouse. I have followed the Medallion Architecture, which encompasses **Bronze,Silver,** and **Gold** layers

<img width="792" height="412" alt="image" src="https://github.com/user-attachments/assets/8fc145d0-9d1c-4453-a318-f1804a4bdb90" />

**Bronze Layer**: Extract raw data from the source systems and store it. The Source file is in CSV format and is ingested into the SQL Server Database.
**Silver Layer**: Data cleansing, standardization, and normalization are the major steps in this layer.
**Gold Layer**: This layer has the business-ready data that is modeled into a star schema. Business users can use the data for reporting and analytics.

## Project Overview
The entire project includes:
  1. **Data Architecture**: A data warehouse that is designed using the Medallion Architecture.
  2. **ETL Pipeline**: The entire ETL pipeline: Extracting the data from the source, transforming   it, and finally loading it into the Data Warehouse.
  3. **Data Modeling**: Creating data models using the Fact and Dimension tables.
  4. **Analytics and Reporting**: Created a SQL-based report and dashboards for insights.

🎯 This repository is an excellent resource for professionals and data enthusiasts who are looking to showcase expertise in:

-SQL Development
-Data Architect
-Data Engineering
-ETL Pipeline Developer
-Data Modeling
-Data Analytics


# Project Requirements

### Building a Data Warehouse
Develop a Data Warehouse using SQL Server to consolidate the business (Sales) data that can be supplied to the reporting/dashboard developers. 

**Project Specifications**
Data Sources: Import data from two source systems (ERP and CRM) provided as CSV files.
Data Quality: Cleanse and resolve data quality issues before analysis.
Integration: Combine both sources into a single, user-friendly data model designed for analytical queries.
Scope: Focus on the latest dataset only; historization of data is not required.
Documentation: Provide clear documentation of the data model to support both business stakeholders and analytics teams.

**Repository Structure**
```
data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── etl.drawio                      # Draw.io file shows all different techniquies and methods of ETL
│   ├── data_architecture.drawio        # Draw.io file shows the project's architecture
│   ├── data_catalog.md                 # Catalog of datasets, including field descriptions and metadata
│   ├── data_flow.drawio                # Draw.io file for the data flow diagram
│   ├── data_models.drawio              # Draw.io file for data models (star schema)
│   ├── naming-conventions.md           # Consistent naming guidelines for tables, columns, and files
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
│
├── tests/                              # Test scripts and quality files
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information for the repository
├── .gitignore                          # Files and directories to be ignored by Git
└── requirements.txt                    # Dependencies and requirements for the project
```
---
