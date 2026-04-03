# 🏢 Real Estate ETL Pipeline

## Overview
A scalable Data Engineering project utilizing Apache Spark (PySpark) to process and analyze real estate data. This repository demonstrates an end-to-end Extract, Transform, Load (ETL) pipeline designed for high efficiency and consistency.

## Key Highlights
* **Big Data Processing:** Efficiently processed **10,000+** real estate records using the PySpark framework.
* **Pipeline Architecture:** Designed and implemented a highly scalable ETL pipeline for robust data cleaning, missing value imputation, and transformation.
* **Performance:** Significantly improved data processing speed and consistency, preparing a clean, structured dataset ready for downstream machine learning and dashboarding tasks.

## Tech Stack
* **Framework:** Apache Spark (PySpark), Spark SQL
* **Language:** Python
* **Environment:** Databricks / Local Spark Session

## ETL Workflow
1. **Extract:** Ingested raw real estate datasets (CSV/JSON formats).
2. **Transform:** * Standardized data schemas and data types.
   * Handled null values and outliers in property prices and square footage.
   * Created new derived features (e.g., price_per_sqft).
3. **Load:** Exported the cleaned, partitioned dataset into Parquet format for optimized querying.
<img width="576" height="455" alt="download" src="https://github.com/user-attachments/assets/45e580fb-68da-4a0f-a0c7-f39fd2a9a568" />
<img width="669" height="548" alt="download" src="https://github.com/user-attachments/assets/a6b83280-1025-4516-988e-fc68a3c07915" />
<img width="573" height="457" alt="download" src="https://github.com/user-attachments/assets/4c11ab2f-2465-4346-9867-30de9543e242" />

## How to Run
```bash
# Initialize Spark Session and run the ETL script
spark-submit src/etl_pipeline.py
