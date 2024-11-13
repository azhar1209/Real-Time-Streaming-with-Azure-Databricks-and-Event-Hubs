# Real-Time-Streaming-with-Azure-Databricks-and-Event-Hubs

**Project Overview:**
This project demonstrates an end-to-end solution for real-time data streaming and analysis using Azure Databricks and Azure Event Hubs, with visualization in Power BI. It's an in-depth guide covering the setup, configuration, and implementation of a streaming data pipeline following the medallion architecture.



****Repository Contents:**
Real-time Data Processing with Azure Databricks (and Event Hubs).ipynb: The Databricks notebook used for data processing at each layer of the medallion architecture.
data.txt: Contains sample data and JSON structures for streaming simulation.
Azure Solution Architecture.png: High level solution architecture.


**Prerequisites****
Active Azure subscription with access to Azure Databricks and Event Hubs.
Databricks Workspace with Unity Catalog Enabled.
Azure Event Hubs Service.
Power BI Desktop (Windows).


In this project i have started by creating real time data in Azure Event Hubs and then store and process the data in our Databricks Lakehouse, implementing the Bronze, Silver, and Gold layers of the Medallion Architecture. The final step involves creating a near real-time report on Power BI, showcasing the power of streaming analytics.
