# Data Eningeering Project on Azure - Payroll Data for NYC

## Background
The City of New York would like to develop a Data Analytics platform on Azure Synapse Analytics to accomplish two primary objectives:

Analyze how the City's financial resources are allocated and how much of the City's budget is being devoted to overtime.
Make the data available to the interested public to show how the City’s budget is being spent on salary and overtime pay for all municipal employees.
I have been hired as a Data Engineer to create high-quality data pipelines that are dynamic, can be automated, and monitored for efficient operation. The project team also includes the city’s quality assurance experts who will test the pipelines to find any errors and improve overall data quality.

The source data resides in Azure Data Lake and needs to be processed in a NYC data warehouse in Azure Synapse Analytics. The source datasets consist of CSV files with Employee master data and monthly payroll data entered by various City agencies.

## Objective
The overall objective of this project was to take source data, and create data flows in Azure Data Factory to extract, join, transform, and aggregate New York City’s payroll data, and land it in Azure Synapse Analytics in suitable schema to support analytics and insights

## Execution
This project was executed in the Azure Portal, using several Azure resources including:

+ Azure Data Lake Gen2
+ Azure SQL DB
+ Azure Data Factory
+ Azure Synapse Analytics

### Dataset
The dataset for this project is publicly available and can be downloaded from this [link](https://video.udacity-data.com/topher/2022/May/6283aff5_data-nyc-payroll/data-nyc-payroll.zip)
