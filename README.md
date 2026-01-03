# MSSQL-Data-Warehouse-Project
MS SQL Data Warehouse Project

A collection of historical and non-volatile (subject-oriented) data from different source to support management's decision process.

Key words: Organize, Structure, Prepare

- Data Architecture
- Data Integration
- Data Modeling
- ELT / ETL Processing
- Data Load
- Data Cleansing

ETL Techniques / Methods
1 Extraction 
  1.1 Full
  1.2 Incremental

    Extraction Methods
    - Manual Extraction
    - Database Querying
    - File Parsing
    - API Calls
    - Event Based Streaming
    - CDC (Change Data Capture)
    - Web Scraping

2 Transformation
- Data Enrichment
- Data Integration
- Derived Column
- Data Normalization & Standardization
- Business Rules and Logic
- Data Aggregations
- Data Cleansing
  (a) Remove Duplicates
  (b) Data Filtering
  (c) Outlier Detection
  (d) Data Type Casting
  (e) Handling unwanted spaces or characters
  (f) Handling missing data
  (g) Handing invalid data

3 Load
Load processing types: (a) Batch (b) Streaming
  3.1 Full
    - Truncate & Insert
    - Upsert
    - Drop, Create, Insert
  3.2 Incremental
    - Upsert
    - Append
    - Merge

SCD (Slowly Changing Dimensions)
a. SCD0 - No historization
b. SCD1 - Overwrite
c. SCD2 - Histoization
