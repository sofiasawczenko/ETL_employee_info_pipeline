# ETL Project with Data Fusion, Airflow, and BigQuery

This repository contains code and configuration files for an Extract, Transform, Load (ETL) project using Google Cloud Data Fusion for data extraction, Apache Airflow/Composer for orchestration, and Google BigQuery for data loading.

---
## Problem Statement

You are tasked with creating a data pipeline to extract employee data from various sources, mask sensitive information within the data, and load it into BigQuery. Additionally, you are required to develop a dashboard to visualize the employee data securely.

## Requirements:

- **Data Extraction:** Extract employee data from multiple sources such as databases, CSV files, or APIs.
- **Data masking:** Identify sensitive information within the employee data, such as social security numbers, salary details, and personal contact information.
- **Data Loading into BigQuery:** Design a process to securely load extracted and masked employee data into Google BigQuery.
- **Dashboard Visualization:** Develop a web-based dashboard using visualization tools (e.g., Google Data Studio, Tableau, or custom dashboards).
---
## Overview

The project aims to perform the following tasks:

1. **Data Extraction**: Extract data using python.
2. **Data Masking**: Apply data masking & encoding techniques to sensitive information in Cloud Data Fusion before loading it into BigQuery.
3. **Data Loading**: Load transformed data into Google BigQuery tables.
4. **Orchestration**: Automate complete Data pipeline using Airflow ( Cloud Composer )

![image](https://github.com/vishal-bulbule/etl-pipeline-datafusion-airflow/assets/143475073/755818fe-1cd3-4e1c-827d-35b963d6f414)

## Architecture

![image](https://github.com/vishal-bulbule/etl-pipeline-datafusion-airflow/assets/143475073/0ea51bdb-99cc-4abf-8ccc-8be721462fc3)
