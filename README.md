# Kaggle-YouTube-Data-Analysis
## Overview
This project focuses on the secure management, efficient streamlining, and analysis of both structured and semi-structured YouTube video data, categorized by video types and trending metrics.

## Project Goals
- Data Ingestion: Establish a system to ingest data from various sources.
- ETL System: Transform raw data into a structured format.
- Data Lake: Create a centralized repository to store data from multiple sources.
- Scalability: Ensure the system scales with the increasing volume of data.
- Cloud Utilization: Utilize AWS to process large datasets that exceed local computer capacities.
- Reporting: Develop a dashboard to answer previously identified questions.

## Services Utilized
- Amazon S3: Object storage service providing scalability, data availability, security, and performance.
- AWS IAM: Identity and access management to securely handle AWS services and resources.
- QuickSight: Scalable, serverless, machine learning-powered business intelligence service.
- AWS Glue: Serverless data integration service for discovering, preparing, and combining data for analytics, machine learning, and application development.
- AWS Lambda: Compute service that runs code without server management.
- AWS Athena: Interactive query service for S3, allowing data queries without the need to load data into a separate system.

## Dataset Used
The dataset from Kaggle contains daily statistics (CSV files) on popular YouTube videos over several months, with up to 200 trending videos per day for various regions. Data includes video titles, channel titles, publication times, tags, views, likes, dislikes, descriptions, and comment counts. A category_id field is also included in the region-specific JSON files.

[Kaggle YouTube Dataset](https://www.kaggle.com/datasets/datasnaek/youtube-new)

## Architecture Diagram
Include your architecture diagram here
