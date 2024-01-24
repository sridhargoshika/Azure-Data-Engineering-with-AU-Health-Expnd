# Australia Health Expenditure Azure Data Engineering Project

This project demonstrates an end-to-end Azure ETL Data Engineering solution for analyzing Australia's Health Expenditure. The project utilises various Azure services, including Azure Data Factory, DataBricks, Data Lake, Key Vault, and Power BI.

## Project Overview

The goal of this ETL project is to showcase how to ingest, process, and analyse Australia's Health Expenditure data using Azure services. The ETL flow involves extracting data, transforming it using DataBricks, storing it in Data Lake, and creating visualizations in Power BI.

## Services Used

- **Azure Data Factory:** Orchestrates and automates ETL workflows, including data extraction.

- **DataBricks:** Performs advanced data transformations on the extracted data, using Python and SQL.

- **Data Lake:** Serves as the storage repository for raw, processed and presentation data.

- **Key Vault:** Safely stores and manages secrets used in ETL operations, ensuring secure access to resources.

- **Power BI:** Creates insightful visualisations for data analysis and reporting.

## Project Structure

The project is organised as follows:

- **/data-factory:** Contains Azure Data Factory pipeline configurations.

- **/databricks-notebooks:** Includes DataBricks notebooks in PySpark and SparkSQL for data processing.

- **/raw-data:** Store the source data in csv files.

- **/screenshots:** Captures visual documentation and screenshots.

- **/powerBI:** Holds Power BI report files.

## Getting Started

To reproduce this project, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Andy-Hoang/Azure-Data-Engineering-with-AU-Health-Expnd.git

