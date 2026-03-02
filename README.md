# AWS Glue Visual ETL Workshop

## 📌 Project Overview
This project demonstrates the implementation of a serverless ETL (Extract, Transform, Load) pipeline using **AWS Glue**. The goal was to build a scalable data integration solution that automates data discovery, cleaning, and transformation without managing underlying infrastructure.

## 🛠️ Tech Stack & AWS Services
- **AWS Glue Studio**: Visual interface for authoring and monitoring ETL jobs.
- **AWS Glue Data Catalog**: Persistent metadata store for data assets.
- **AWS Glue Crawlers**: Automated schema discovery.
- **Amazon S3**: Data Lake storage for raw and processed datasets.
- **Amazon Athena**: Querying transformed data using standard SQL.

## 🚀 Key Learnings & Implementation
- **Visual ETL Authoring**: Designed complex data transformations (Joins, Filters, Mappings) using the "boxes-and-arrows" interface in Glue Studio.
- **Schema Management**: Used Crawlers to automatically infer schemas and populate the Glue Data Catalog.
- **Scalability**: Configured Worker Types and DPUs (Data Processing Units) to handle big data workloads efficiently.
- **AI-Powered Data Integration**: Leveraged AWS Glue’s built-in logic to handle schema drift and semi-structured data.

## 📈 Project Impact
By utilizing serverless components, this architecture:
1. **Reduces Operational Overhead**: No servers to manage.
2. **Accelerates Development**: Visual tools allow for faster pipeline creation compared to manual coding.
3. **Cost-Efficiency**: Pay-only-for-what-you-use pricing model via DPUs.

---
*Based on the [AWS Workshop: Visual ETL with Glue](https://catalog.us-east-1.prod.workshops.aws/workshops/0cba1e21-10d6-4e8e-b35f-a09338ee68d9/en-US)*
