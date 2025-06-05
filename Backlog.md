## Project Backlog: Real-Time Weather Streaming with Azure


| ID  | Epic                          | User Story                                                                 | Estimate Hours | Status          |
|-----|-------------------------------|----------------------------------------------------------------------------|----------------|-----------------|
| 1   | Azure Environment Setup       | Create Azure Resource Group for centralized resource management            | 1              |Completed        |
|     |                               | Set up Azure Key Vault for secure storage of API keys                      | 0.5            |Completed        |
|     |                               | Configure access and role-based permissions                                | 0.5            |Completed        |
| 2   | Data Ingestion with Databricks| Register and test connection to Live Weather API                           | 1              |Completed        |
|     |                               | Send a test data to Event Hub                                              | 1              |Completed        |
|     |                               | Set up structured streaming to semd evemts to Event Hub every 30 seconds           | 2              |Completed        |
| 3   | Data Ingestion with Azure Functions | Connect Visual Studio Code to Azure                                  | 0.5            |Completed        |
|     |                               | Create a new function with Timer Trigger to send events to Event Hub every 30 seconds| 3              |Completed        |
|     |                               | Deploy Function App to Azure                                               | 0.5            |Completed        |
|     |                               | Test if the Function App is working properly                               | 0.5            |Completed        |
| 4   |Price Calculation              | Compare cost for Databricks and Azure Functions to determine the cost efficient resource| 0.5            |Completed        |
| 5   | Real-Time Streaming           | Create a Event House KQL database                                          | 0.5            |Completed        |
|     |                               | Use Event Stream to continuously load incoming data into KQL database      | 1              |Completed        |
|     |                               | Perform real-time analytics on incoming weather data                       | 1              |Completed        |
| 6   | Reporting                     | Connect Power BI to Kusto DB                                               | 0.5            |Completed        |
|     |                               | Create Power BI dashboard to visualize real-time weather insights          | 4              |Completed        |
|     |                               |Set up Auto/Scheduled Refresh                                               | 0.5            |Completed        |
| 7   | Alerting & Automation         | Configure Microsoft Fabric Data Activator for extreme weather detection    | 2              |Completed        |
|     |                               | Trigger real-time alerts via email (Outlook) for critical conditions       | 1              |Completed        |
|     |                               | Test if an alert email is received by sending a test event                 | 0.4            |Completed        |
