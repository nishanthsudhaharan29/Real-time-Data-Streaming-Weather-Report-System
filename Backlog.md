## Project Backlog: Real-Time Weather Streaming with Azure


| ID  | Epic                          | User Story                                                                 | Estimate Hours | Status          |
|-----|-------------------------------|----------------------------------------------------------------------------|----------------|-----------------|
| 1   | Azure Environment Setup       | Create Azure Resource Group for centralized resource management            | 1              |Completed        |
|     |                               | Set up Azure Key Vault for secure storage of API keys                      | 0.5            |Completed        |
|     |                               | Configure access and role-based permissions                                | 0.5            |Completed        |
| 2   | Data Ingestion with Databricks| Register and test connection to Live Weather API                           | 1              |Completed        |
|     |                               | Send a test data to Event Hub                                              | 1              |Completed        |
|     |                               | Set up structured streaming to call API and ingest weather data            | 2              |Completed        |
| 3   | Data Ingestion with Azure Functions | Connect Visual Studio Code to Azure                                  | 0.5            |Completed        |
|     |                               | Xreate a new function with Timer Trigger to send events to Event Hub       | 3              |Completed        |
|     |                               | Deploy Function App to Azure                                               | 0.5            |Completed        |
|     |                               | Test if the Function App is working properly                               | 0.5            |Completed        |
| 4   |Price Calculation              | Compare cost for Databricks and Azure Functions to determine the cost efficient resource| 0.5            |Completed        |
| 5   | Real-Time Streaming           | Create a Event House KQL database                                          | 0.5            |Completed        |
|     |                               | Use Event Stream to continuously load incoming data into KQL database      | 1              |Completed        |
|     |                               | Perform real-time analytics on incoming weather data                       | 1              |Completed        |
| 6   | Reporting                     | Create Power BI dashboard to visualize real-time weather insights          | 3              |        |
|     |                               | Connect Power BI to Kusto DB                                               | 1              |        |
| 7   | Alerting & Automation         | Configure Microsoft Fabric Data Activator for extreme weather detection    | 2              |        |
|     |                               | Trigger real-time alerts via email (Outlook) for critical conditions       | 1              |        |
| 8   | Monitoring & Observability    | Set up health checks and pipeline metrics visualization                    | 2              |        |
|     |                               | Configure alert rules for pipeline failure or latency                      | 1              |        |
