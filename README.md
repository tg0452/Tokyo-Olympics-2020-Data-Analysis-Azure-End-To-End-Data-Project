# Tokyo-Olympics-2020-Data-Analysis-Azure-End-To-End-Data-Project

Implementation of various Azure tools and techniques that includes Azure Data Factory for data import, Azure Synapse Analytics for data analysis, Azure Data Lake Gen2 for raw data storage and Azure Databricks for seamless data pipeline management which optimized the data processing efficiency.

Built the Tokyo Olympics 2020 data analysis project by leveraging Microsoft Azure platform to extract meaningful insights. This involved extraction of data from data source (Kaggle), data ingestion, transformation and visualization that enabled data-driven decision-making.


Technologies Utilized

- Programming Languages: Pyspark, SQL
- Azure Data Factory
- Azure Data Lake Gen2
- Azure Databricks 
- Azure Synapse Analytics
  

Workflow Overview

Data Extraction

- Retrieved data from GitHub via an HTTP connection.
- Leveraged Azure Data Factory (ADF) to transfer the data into the Raw folder within Azure Data Lake Gen2.


Data Transforamtion

- Established a mount point in Databricks to access the Raw folder in Azure Data Lake Gen2.
- Utilized Databricks with PySpark to transform the data and save the processed output to the Processed folder in Azure Data Lake Gen2.

Data Loading & Analytics

- Set up a database in Azure Synapse Analytics.
- Created tables within the Synapse database for structured data storage.
- Executed SQL scripts in Synapse Analytics to derive actionable insights.


