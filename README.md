# PySpark Employee ETL Pipeline

## Project Overview

This project demonstrates a basic data engineering ETL pipeline using PySpark.

The pipeline takes employee data, performs data cleaning and transformation, joins employee information with department information, creates department-level summaries, and stores the processed data in Parquet format.

## Technologies Used

- Python
- PySpark
- Spark SQL
- Parquet
- Git & GitHub

## ETL Process

The project follows these steps:

1. Create a SparkSession
2. Create an employee DataFrame
3. Inspect the schema and data
4. Identify and handle NULL values
5. Remove duplicate records
6. Filter employees based on salary
7. Select required columns
8. Create salary categories using conditional transformations
9. Join employee data with department data
10. Perform `groupBy()` and aggregations
11. Sort department-level results
12. Create a temporary Spark SQL view
13. Query the data using Spark SQL
14. Write processed data to Parquet
15. Read the saved Parquet data back

## PySpark Concepts Practiced

- DataFrames
- select()
- filter()
- withColumn()
- when() and otherwise()
- NULL handling
- dropDuplicates()
- unionByName()
- Joins
- \groupBy()
- Aggregations such as count(), avg(), and max()
- orderBy()
- Temporary SQL Views
- Spark SQL
- Parquet read and write

## Project Structure


pyspark-employee-etl-pipeline/
│
├── project.ipynb
└── README.md

## Execution Environment

The project was developed and practiced using PySpark in Google Colab and VS Code.

**Purpose**

The purpose of this project is to practice fundamental PySpark and data engineering concepts such as data cleaning, transformation, joining, aggregation, SQL processing, and data storage.
