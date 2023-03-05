# Overview

This project aims to convert relational data model into dimensional data model using Python and SQL and create datawarehouse in Redshift

# Project Steps

1. Visualize relational data model
2. Upload data to S3
3. Crawl data 
4. Connect to Athena and query data
5. Visualize dimensional data model 
6. Set up config file
7. ETL job in Python and SQL
8. Save results to S3
9. Build tables on Redshift
10. Copy data to Redshift

# Services we will be using

1. Amazon S3: Amazon S3 is an object storage service that provides manufacturing scalability, data availability, security, and performance.
2. AWS IAM: This is nothing but identity and access management which enables us to manage access to AWS services and resources securely.
3. AWS Glue: A serverless data integration service that makes it easy to discover, prepare, and combine data for analytics, machine learning, and application development.
4. AWS Athena: Athena is an interactive query service for S3 in which there is no need to load data it stays in S3.
5. Amazon Redshift Serverless provides data warehouse capacity and intelligent scaling with simple configuration and management.
6. Diagrams.net free online diagram software for making flowcharts

# Dataset Used

This sample database is originally used for learning and practicing PostgreSQL. 
For simple demonstration we use this data set in my project. The DVD rental database represents the business processes of a DVD rental store. 
https://www.postgresqltutorial.com/postgresql-getting-started/postgresql-sample-database/

# Architecture Diagram
![Cloud AWS drawio](https://user-images.githubusercontent.com/82080180/222929693-13e2701b-dcc6-4746-b85b-354eab7b3b4d.png)
