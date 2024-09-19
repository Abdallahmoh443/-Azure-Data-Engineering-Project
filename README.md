# Data Pipeline Project for E-Commerce Platform

## Overview

This project demonstrates how to build a data pipeline specifically for an e-commerce platform. It ingests data from various sources using Azure Data Factory, performs cleaning and transformations using Azure Databricks with PySpark, and stores the transformed data in Azure Data Lake Storage Gen2.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Architecture](#architecture)


## Features

- Ingest data from various e-commerce sources (e.g., sales records, customer data, product information,target sales).
- Store raw data in Azure Data Lake Storage Gen2.
- Clean and transform data to enhance analysis (e.g., filtering, aggregating).
- Store transformed data in Azure Data Lake Storage Gen2 for downstream analytics and reporting.

## Technologies Used

- **Azure Data Factory**: For orchestrating data movement and transformation.
- **Azure Data Lake Storage Gen2**: For storing both raw and transformed data.
- **Azure Databricks**: For data processing using Apache Spark and PySpark.

## Architecture

The architecture of the data pipeline consists of the following components:

1. **Source**: Data is ingested from various e-commerce sources (e.g., databases, APIs).
2. **Azure Data Factory**: Manages data movement from the source to Azure Data Lake Gen2.
3. **Azure Data Lake Storage Gen2**: Stores the raw data.
4. **Azure Databricks**: Performs data cleaning and transformation, including operations like filtering out duplicates, handling missing values, and restructuring data for analysis.
5. **Azure Data Lake Storage Gen2**: Stores the final transformed data for easy access by analytics tools.


![Architecture Diagram](images/project%20overview.png)
![Architecture Diagram](images/Azure%20data%20factory%20pipline.png)

