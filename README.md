

# AWS Retail Sales Data Pipeline Project

## Overview
This project demonstrates a serverless data pipeline for retail sales data using AWS services. The goal is to ingest, transform, and analyze retail sales data to extract actionable business insights.

## Architecture
The pipeline is designed as follows:
1. **Data Ingestion:** Raw CSV files are uploaded to Amazon S3.
2. **ETL Processing:** AWS Glue (simulated here) cleans and transforms the data.
3. **Data Querying:** Transformed data is stored and queried via Amazon Athena.
4. **Visualization:** Dashboards can be created in Amazon QuickSight.

## Technologies Used
- Amazon S3
- AWS Glue
- Amazon Athena
- AWS Lambda
- Amazon QuickSight
- Python

## Project Structure
aws-retail-sales-pipeline/
├── data/
│   └── retail_sales.csv
├── src/
│   ├── etl.py
│   └── lambda_handler.py
└── README.md

## Instructions
- Run `etl.py` to simulate ETL processing.
- The transformed data is saved as `retail_sales_transformed.csv`.

## Future Enhancements
- Deploy ETL using AWS Glue
- Automate processing via AWS Lambda
- Visualize data in QuickSight
