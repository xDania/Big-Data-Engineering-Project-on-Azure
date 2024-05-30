# Overview
Led end-to-end execution of a Big Data project on Azure using data from StackOverflow. The project involves data ingestion, transformation, machine learning, and visualization to classify and analyze post topics.

# Data Sources
1. **RDS (Postgres Database)**:
   - Users and PostTypes tables (updated weekly)
   
2. **Azure Storage Blob**:
   - Posts data in parquet format (updated daily)

# Purpose
- Ingest StackOverflow data into an Azure Data Lake
- Transform and analyze data using a Machine Learning model
- Classify posts by topic and generate daily insights
- Visualize the top 10 topics using Azure Synapse

# Infrastructure
- **Azure Data Lake**: Store ingested data and ML output
- **Azure Data Factory (ADF)**: Manage data ingestion and processing
- **Databricks**: Process data and execute machine learning
- **Azure Synapse**: Analyze data and create visualizations

# Key Steps
1. **Data Ingestion**:
   - Weekly ingest Users and PostTypes from RDS
   - Daily ingest Posts from Azure Storage Blob

2. **Data Transformation**:
   - Use Databricks for data cleaning and transformation
   - Run a Machine Learning model to classify post topics

3. **Data Visualization**:
   - Use Synapse to generate a chart of the top 10 topics

# Achievements
- Established a Data Lake on Azure
- Implemented efficient ADF pipelines
- Developed Databricks notebooks for ML processing
- Utilized Spark for data analysis
- Created interactive visualizations with Azure Synapse and Power BI

