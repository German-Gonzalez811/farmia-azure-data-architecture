# FarmIA Azure Data Architecture Case Study

## Project Overview

This project is an academic case study developed as part of my master's coursework in Data Engineering.

The objective was to design a scalable, flexible, and efficient data architecture for FarmIA, 
a fictional agricultural products company planning to expand its data capabilities using Azure.

The proposed solution is based on an Azure Data Lakehouse architecture with batch and streaming ingestion, 
organized using the Medallion Architecture approach: Bronze, Silver, and Gold layers.

## Business Context

FarmIA needs to integrate multiple data sources, including:

- Online sales platform
- Local inventory system
- Agricultural field sensors
- Real-time customer events
- Mobile applications
- Third-party sales channels

The architecture was designed to support scalability, integration of new data sources, real-time analytics, and business intelligence consumption.

## Proposed Architecture

The proposed architecture includes the following layers:

1. Data Sources
2. Ingestion Layer
3. Storage Layer
4. Processing Layer
5. Serving Layer
6. Consumption Layer

## Technologies Included

- Azure Data Lake Storage
- Azure Data Factory
- Azure Event Hubs
- Azure IoT Hub
- Azure Databricks
- Azure SQL Database
- Azure Cosmos DB
- Power BI
- Medallion Architecture
- Batch and Streaming Data Processing

## Repository Structure

text
farmia-azure-data-architecture/
├── README.md
├── docs/
│   └── farmia_data_architecture_report.pdf
└── diagrams/
    └── farmia_architecture_diagram.png
