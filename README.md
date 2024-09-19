# Data Pipeline Project

## Overview

This project demonstrates how to build a data pipeline that ingests data from a source using Azure Data Factory, performs cleaning and transformations using Azure Databricks with PySpark, and stores the transformed data in Azure Data Lake Storage Gen2.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Architecture](#architecture)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- Ingest data from various sources (e.g., SQL Database, Blob Storage).
- Store raw data in Azure Data Lake Storage Gen2.
- Clean and transform data using PySpark on Azure Databricks.
- Store transformed data back into Azure Data Lake Storage Gen2.

## Technologies Used

- **Azure Data Factory**: For orchestrating data movement and transformation.
- **Azure Data Lake Storage Gen2**: For storing both raw and transformed data.
- **Azure Databricks**: For data processing using Apache Spark and PySpark.

## Architecture

The architecture of the data pipeline consists of the following components:

1. **Source**: Data is ingested from the defined source.
2. **Azure Data Factory**: Manages data movement from the source to Azure Data Lake Gen2.
3. **Azure Data Lake Storage Gen2**: Stores the raw data.
4. **Azure Databricks**: Performs data cleaning and transformation.
5. **Azure Data Lake Storage Gen2**: Stores the final transformed data.

![Architecture Diagram](path/to/architecture_diagram.png)
