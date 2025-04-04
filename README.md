# Weather Data Processing Pipeline

This project implements a real-time weather data processing pipeline using Azure services. It ingests live weather data from an API, processes it using Azure Databricks and Azure Functions, streams it through Event Hub, stores it in Eventhouse (Kusto DB), and visualizes it in Power BI.

API Source [https://www.weatherapi.com]
## Architecture
![Architecture Diagram] in docs folder

## Components
- **Data Ingestion:** Azure Databricks and Azure Functions ingest weather data from a live API.
- **Data Streaming:** Event Hub and Event Stream handle real-time data flow.
- **Storage & Querying:** Eventhouse (Kusto DB) stores and queries data using KQL.
- **Visualization:** Power BI provides real-time dashboards.
- **Security & Management:** Key Vault and Cost Management ensure secure and cost-effective operations.
- **Monitoring:** Real-time alerts are set up for monitoring.

## Repository Structure
- `databricks/`: Databricks notebooks and scripts for data processing.
- `azure-weather-functions/`: Azure Functions script for event-driven processing.
- `kql-queries/`: KQL queries for Eventhouse.
- `docs/`: Documentation and architecture diagram
- 'docs/': Also have screenshot of project
-`assets/`: Contains PowerBi dashboard



## Technologies Used
- Azure Databricks
- Azure Functions
- Azure Event Hub
- Eventhouse (Kusto DB)
- Power BI
- KQL (Kusto Query Language)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Link to Project Demo [youtube.com] 
