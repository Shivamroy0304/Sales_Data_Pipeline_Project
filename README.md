# Sales Data Pipeline Project

This repository contains an end-to-end data engineering pipeline designed to process and analyze Amazon's mobile phone sales data. The data encompasses a year's worth of sales from three regions: India, USA, and France. The pipeline employs modern data engineering practices and tools to handle data ingestion, transformation, and visualization effectively.

## Project Overview

The Amazon Sales Data Pipeline Project integrates various data engineering components to transform raw sales data into insightful analytical reports. The pipeline processes data in multiple formats, including CSV, JSON, and Parquet, using Apache Airflow for orchestration and Snowflake for storage and computation. The final output is a dashboard that visualizes key metrics and trends.

## Architecture

The architecture has several zones, each responsible for different aspects of the data lifecycle:

- **Data Pipeline Architecture:** ![Data Pipeline Architecture](https://github.com/Shivamroy0304/Sales_Data_Pipeline_Project/blob/main/data_pipeline.jpg)
- **Airflow DAGs:** ![Airflow DAGs](https://github.com/Shivamroy0304/Sales_Data_Pipeline_Project/blob/main/DAG_graph.png)

## Pipeline Stages

- **Ingestion:** Data files are ingested into Snowflake's internal staging area.
- **Source Zone:** Initial storage categorizes data by item, customer, and sales.
- **Curated Zone:** Data is cleaned and transformed.
- **Consumption Zone:** Data is modeled for efficient querying.

## Tools and Technologies

- **Apache Airflow:** Orchestrates and schedules data pipeline tasks.
- **Snowflake:** Stores and processes data.
- **Snowpark:** Manages data transformations.
- **Visualization Tool:** Displays dashboard metrics.

## Dashboard Features

- **Yearly Data Overview**
- **Country-wise Payment Analysis**
- **Sales Metrics** ![Dashboard](https://github.com/Shivamroy0304/Sales_Data_Pipeline_Project/blob/main/dashboards/Screenshot.png)

## Contact
For any queries, feel free to contact Shivam Roy.
