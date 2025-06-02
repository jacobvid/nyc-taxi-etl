# NYC Taxi ETL and SQL Analysis Project 🚖

This project builds a simple ETL pipeline and performs SQL-based analysis on NYC Yellow Taxi trip data using Databricks and Apache Spark.

## Project Structure

- `00_setup.ipynb`: Set up files for project.
- `01_ingest_bronze.ipynb`: Ingest raw `.parquet` file and write it as a Delta table (Bronze layer).
- `02_transform_silver.ipynb`: Clean column names, filter bad records, and store a refined Delta table (Silver layer).
- `03_aggregate_gold.ipynb`: Aggregate trip distances by passenger count and output Gold layer summary table.
- `04_data_analysis.ipynb`: Run SQL queries to explore trip trends by hour, vendor, and location.

## Dataset

Source: [NYC Taxi & Limousine Commission](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)  
File used: `yellow_tripdata_2023-01.parquet`

## Features

- PySpark-based ETL using Delta Lake
- Column name sanitization
- SQL analysis with Databricks SQL
- Built for readability and modularity

## Visualizations

Visuals created using Databricks' built-in visualization tools.

## Tools

- Databricks Community Edition
- PySpark
- Delta Lake
- SQL

## Author

Jacob Vidergar  
MS Biostatistics | University of Michigan  
[LinkedIn](www.linkedin.com/in/jacobvidergar)

