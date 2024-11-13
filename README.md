# Real-time-Vehicle-Telemetry-stream-processing-with-Azure-Stream-Analytics-Event-Hub-and-Synapse

Contoso Auto is collecting vehicle telemetry and wants to rapidly ingest and store the data in its raw form, then do some processing in near real-time. In the end, they want to create a dashboard that automatically updates with new data as it flows in after being processed. What they would like to see on the dashboard are various visualizations of detected anomalies, like engines overheating, abnormal oil pressure, and aggressive driving, using components such as a map to show anomalies related to cities, as well as various charts and graphs depicting this information in a clear way.

In this Scenario, we will use Azure Event Hubs to ingest streaming vehicle telemetry data as the entry point to a near real-time analytics pipeline built on Event Hubs, Azure Stream Analytics, and Azure Synapse Analytics. Azure Stream Analytics extracts the vehicle sensor data from Event Hubs, performs aggregations over windows of time, then sends the aggregated data to Azure Synapse Analytics for data analysis. A vehicle telemetry data generator will be used to send vehicle telemetry data to Event Hubs.

![image](https://github.com/user-attachments/assets/d01c4295-5f59-4e17-8a04-706dc9b350f4)

1.create a resource group.

2.inside resource group-create-event hub,stream analytics job,synapse

3.go to event hub-create

4.in synapse-manage-create dedicated pool

![image](https://github.com/user-attachments/assets/1e7edacb-f839-48c9-8705-d211dac65d70)

5.in synapse -develop-change connect to,use database

6.create dedicated sql table

![image](https://github.com/user-attachments/assets/dd60cb6c-1746-47fd-8191-e1cee93edfd9)

7.go tomstream analytics job,give input-event hub

![image](https://github.com/user-attachments/assets/a30185e2-40f2-4b78-b8bf-9c33e30db175)

8.output-synapse-give username and password of sql used in synapse

![image](https://github.com/user-attachments/assets/4d45452a-fc79-46dd-9cfc-0a85a5dcfb33)

9.go to eventhub namespace-event hub-shared access policies-add

![image](https://github.com/user-attachments/assets/bf0fb102-b0a2-4a09-970c-a2d55e3526a8)

10.after creating copy the primary connection string

![image](https://github.com/user-attachments/assets/ee659ab7-6def-4968-95f8-42d85ddd79af)



























