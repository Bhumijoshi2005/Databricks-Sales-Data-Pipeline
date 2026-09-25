# Sales Data Engineering Pipeline using Databricks

## Project Overview

This project is a **Sales Data Engineering Pipeline** built using **Databricks, PySpark, SQL, and Delta Lake**.

The project follows the **Medallion Architecture** to process sales data through **Bronze, Silver, and Gold layers**.

## Technologies Used

* Databricks
* PySpark
* Python
* SQL
* Delta Lake
* Medallion Architecture

## Bronze Layer

The Bronze layer is used to ingest the raw sales data into Databricks.

### Work completed

* Loaded the sales CSV file into Databricks.
* Defined the schema for the sales data.
* Read the CSV data using PySpark.
* Checked the structure and data types using the DataFrame schema.
* Displayed and verified the loaded data.
* Stored the raw sales data as a Delta table.

## Silver Layer

The Silver layer is used to clean and transform the Bronze data.

### Work completed

* Read the Bronze Delta table.
* Performed data cleaning and transformation.
* Removed duplicate records.
* Handled missing values.
* Validated sales values.
* Prepared the cleaned data for analytical processing.

## Gold Layer

The Gold layer is used to create business-ready sales data from the cleaned Silver data.

### Work completed

* Read the cleaned Silver data.
* Aggregated sales data.
* Calculated sales metrics such as total and average sales.
* Created analytical tables for further analysis.
* Used SQL/PySpark to analyze the processed sales data.

## Pipeline

The overall data flow is:

**Sales CSV → Bronze → Silver → Gold → Analytics**

## Key Concepts Learned

* Databricks notebooks
* PySpark DataFrames
* CSV data ingestion
* Schema definition
* Data cleaning
* Data transformation
* Delta tables
* SQL queries
* Data aggregation
* Medallion Architecture
