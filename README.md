# Snowflake_ADLS_DataPipeline
Project demonstrating integration between Azure Data Lake Storage and Snowflake using external stages and structured database layers (bronze, silver, gold).

🌩️ Azure Data Lake to Snowflake Data Pipeline

📘 Project Overview

This project demonstrates how to integrate Azure Data Lake Storage (ADLS) with Snowflake to build a scalable data pipeline.
It establishes a secure connection using storage integration and external stages, and organizes data into the Bronze–Silver–Gold data architecture model for efficient data processing and analytics.

🧩 Key Objectives

Connect Azure Data Lake Storage to Snowflake using secure authentication.

Create and configure a Snowflake database with layered schemas (Bronze, Silver, Gold).

Verify access to ADLS containers through an external stage.

Prepare the environment for future data loading and transformation steps.

🧱 Data Architecture

Bronze → Silver → Gold

Bronze: Raw data directly from source (ADLS).

Silver: Cleaned and standardized data.

Gold: Curated, analytics-ready data.

💡 Future Enhancements

Add data loading scripts for the customer, order, and product datasets.

Create transformation layers (Silver and Gold).

Integrate Snowpipe for automated data ingestion.
