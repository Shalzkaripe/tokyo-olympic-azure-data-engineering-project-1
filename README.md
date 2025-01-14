# Data Engineering 2021 Tokyo Olympics Project
 
## Overview

This project aims to analyze Olympic data using various tools and technologies, including Azure Data Factory, Data Lake Gen 2, Synapse Analytics, and Azure Databricks.

## Project Goals

Data Ingestion — Build a mechanism to ingest data from different sources
ETL System — We are getting data in raw format, transforming this data into the proper format
Data lake — We will be getting data from multiple sources so we need centralized repo to store them
Scalability — As the size of our data increases, we need to make sure our system scales with it
Cloud — We can’t process vast amounts of data on our local computer so we need to use the cloud, in this case, we will use AWS
Reporting — Build a dashboard to get answers to the question we asked earlier

# Services we will be using

Amazon S3: Amazon S3 is an object storage service that provides manufacturing scalability, data availability, security, and performance.
AWS IAM: This is nothing but identity and access management which enables us to manage access to AWS services and resources securely.
QuickSight: Amazon QuickSight is a scalable, serverless, embeddable, machine learning-powered business intelligence (BI) service built for the cloud.
AWS Glue: A serverless data integration service that makes it easy to discover, prepare, and combine data for analytics, machine learning, and application development.
AWS Lambda: Lambda is a computing service that allows programmers to run code without creating or managing servers.
AWS Athena: Athena is an interactive query service for S3 in which there is no need to load data it stays in S3.

# Dataset Used

This Kaggle dataset contains details (CSV files) of over 11,000 athletes, with 47 disciplines, along with 743 Teams taking part in the 2021(2020) Tokyo Olympics. This dataset contains the details of the Athletes, Coaches, Teams participating as well as the Entries by gender. It contains their names, countries represented, discipline, gender of competitors, name of the coaches.

https://www.kaggle.com/datasets/arjunprasadsarkhel/2021-olympics-in-tokyo

# Architecture Diagram

![image](https://github.com/user-attachments/assets/091d0c2e-4674-479b-b9a8-4360d6552314)
