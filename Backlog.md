## Project Backlog: Real-Time Weather Streaming with Azure


| ID  | Epic                          | User Story                                                                 | Estimate Hours | Status |
|-----|-------------------------------|----------------------------------------------------------------------------|----------------|--------|
| 1   | Azure Environment Setup       | Create Azure Resource Group for centralized resource management            | 1              |        |
|     |                               | Set up Azure Key Vault for secure storage of API keys                      | 1              |        |
|     |                               | Enable Azure Cost Management for budgeting and tracking                    | 0.5            |        |
|     |                               | Configure access and role-based permissions                                | 1              |        |
| 2   | Data Source Integration       | Register and test connection to Live Weather API                           | 1              |        |
|     |                               | Set up scheduled Azure Function to call API and ingest weather data        | 2              |        |
| 3   | Data Ingestion                | Process raw weather data using Azure Databricks                            | 3              |        |
|     |                               | Output structured data to Azure Event Hub                                  | 1              |        |
| 4   | Real-Time Streaming           | Connect Event Hub to Microsoft Fabric Event Stream                         | 1              |        |
|     |                               | Parse and analyze incoming data streams                                    | 2              |        |
| 5   | Event Processing              | Load event stream data into Kusto DB (Eventhouse)                          | 2              |        |
|     |                               | Perform real-time analytics on incoming weather data                       | 2              |        |
| 6   | Reporting                     | Create Power BI dashboard to visualize real-time weather insights          | 3              |        |
|     |                               | Connect Power BI to Kusto DB                                               | 1              |        |
| 7   | Alerting & Automation         | Configure Microsoft Fabric Data Activator for extreme weather detection    | 2              |        |
|     |                               | Trigger real-time alerts via email (Outlook) for critical conditions       | 1              |        |
| 8   | Monitoring & Observability    | Set up health checks and pipeline metrics visualization                    | 2              |        |
|     |                               | Configure alert rules for pipeline failure or latency                      | 1              |        |
