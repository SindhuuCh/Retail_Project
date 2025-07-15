# Retail Project - Sales and Store Data Analysis

This project uses PySpark on Databricks to analyze retail sales and store data.

## What it does
- Reads two CSV files: sales data and store data from Databricks FileStore.
- Cleans and filters missing or invalid data.
- Joins sales data with store data.
- Calculates total sales, total quantity sold, and sales per square foot.
- Finds top-selling products and top-performing stores.
- Saves the final results as Parquet files.

## Technologies used
- PySpark
- Databricks notebook environment

## Project files
- RetailProject-DataCleaning.ipynb : Jupyter notebook with data cleaning and analysis steps.
- dagetl.py (optional): Python ETL script for extracting tweets using Tweepy.

## How to run
1. Upload your CSV files to `/FileStore/tables/` in Databricks:
   - sales_data.csv
   - store_data.csv
2. Open and run the notebook step by step.
3. View the saved Parquet files in `/FileStore/tables/top_products` and `/FileStore/tables/top_store`.


