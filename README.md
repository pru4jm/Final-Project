# Final Project – Capstone
This repository contains a Databricks notebook used to build a dimensional data lakehouse using the Northwind dataset.

# Contents
- Final_Project_.ipynb: Main notebook with ETL code, comments, and architecture layers (Bronze, Silver, Gold) as required. 
- .csv and .json: Raw source files used in project.

- Demonstrates ETL pipeline using Databricks.
- Uses Delta tables across Bronze, Silver, and Gold layers.
- Includes dimension tables for employees, products, customers, and date.
- Aggregates fact data for reporting purposes (e.g. total revenue per product and employee).
- ...

# To Run
1. Upload all files to a Databricks workspace (or open the notebook directly in Databricks).
2. File paths should match that in the notebook (e.g., /Volumes/workspace/default/northwind_schema/...).
