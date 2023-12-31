# AzureFunctions Create Function In VSCode

Install the VSCode extensions for "Azure" and for "Azure Functions":

![image](https://github.com/luiscoco/AzureFunctions_CreateFunctionInVSCode/assets/32194879/26903ecf-fa5c-46e2-b0f6-11403d3147a3)

![image](https://github.com/luiscoco/AzureFunctions_CreateFunctionInVSCode/assets/32194879/37d53163-c220-4a66-97cb-6f5008f23a14)

Press the "Azure" button in the left toolbar:

![image](https://github.com/luiscoco/AzureFunctions_CreateFunctionInVSCode/assets/32194879/27162851-9437-484b-af30-09258d8f877e)

Press the "Azure Functions" button to create a new "Function" in VSCode:

![image](https://github.com/luiscoco/AzureFunctions_CreateFunctionInVSCode/assets/32194879/6cec63de-8ab6-4078-9cc5-d99d62a2a11d)

![image](https://github.com/luiscoco/AzureFunctions_CreateFunctionInVSCode/assets/32194879/2e161f1c-1634-48a2-bd73-7dc00c3d3dd2)

Select the folder that will contain the Azure Function project:

![image](https://github.com/luiscoco/AzureFunctions_CreateFunctionInVSCode/assets/32194879/77614227-9963-48ac-a75a-6e3f56785f52)

Select the C# language for writing the Azure Function source code:

![image](https://github.com/luiscoco/AzureFunctions_CreateFunctionInVSCode/assets/32194879/4a99f68e-c32e-4423-a48c-5471fdfde022)

Select the .NET 7 as Framework:

![image](https://github.com/luiscoco/AzureFunctions_CreateFunctionInVSCode/assets/32194879/8373193e-e33f-4604-a414-be88cd2873c9)

Select the "Http Trigger" for the Azure Function template:

![image](https://github.com/luiscoco/AzureFunctions_CreateFunctionInVSCode/assets/32194879/83de5f25-81d9-4215-88d9-fff70d3bef78)

Provide the Azure Function name:

![image](https://github.com/luiscoco/AzureFunctions_CreateFunctionInVSCode/assets/32194879/952e4cf8-881f-4610-9d7e-824eeb3102ae)

Provide the namespace for the Azure Function:

![image](https://github.com/luiscoco/AzureFunctions_CreateFunctionInVSCode/assets/32194879/3e384db5-6c36-473c-89e6-2babe27f00cf)

Select the access rights (Function):

![image](https://github.com/luiscoco/AzureFunctions_CreateFunctionInVSCode/assets/32194879/79b9114f-a418-4de7-835e-1e3e483e2a84)

We can see the Function C# source code in the "HttpTrigger1.cs" and "Program.cs" files:

![image](https://github.com/luiscoco/AzureFunctions_CreateFunctionInVSCode/assets/32194879/5d827390-bacb-4415-a2a0-bd809268376c)

![image](https://github.com/luiscoco/AzureFunctions_CreateFunctionInVSCode/assets/32194879/09daecca-66c4-45b5-8571-8f3eb828ca28)

After pressing the option "Run Without Debugging" we can see the URL: "http://localhost:7071/api/HttpTrigger1"

![image](https://github.com/luiscoco/AzureFunctions_CreateFunctionInVSCode/assets/32194879/14fbca6d-0ed0-425f-8d77-6ec3fe2622d5)

When you enter in the URL: "http://localhost:7071/api/HttpTrigger1"

![image](https://github.com/luiscoco/AzureFunctions_CreateFunctionInVSCode/assets/32194879/7c55b474-ee5d-4fb5-997d-4f06178ea220)

## Azure Functions Triggers

These are the trigger for the Azure Functions:

![image](https://github.com/luiscoco/AzureFunctions_CreateFunctionInVSCode/assets/32194879/f06bcf0b-8354-4e87-afac-64e522d77337)

Azure Functions supports various triggers that can initiate the execution of your serverless functions. 

Here's a brief explanation for some of the common triggers:

**HTTP Trigger**: This trigger allows your function to be invoked via HTTP requests. It's great for building RESTful APIs or handling webhooks.

**Timer Trigger**: With this trigger, your function runs on a predefined schedule, like a cron job. Useful for tasks that need to be executed at regular intervals.

**Blob Trigger**: This trigger responds to changes in Azure Storage blobs. It can be used to process or react to new or modified blobs in your storage account.

**Queue Trigger**: This trigger processes messages from Azure Storage Queues. When a new message arrives, the function is invoked to handle the message.

**Event Hub Trigger**: It responds to events from Azure Event Hubs, which is a scalable data streaming platform. Useful for processing large volumes of data in real-time.

**Service Bus Queue/Topic Trigger**: Similar to Queue Trigger, it processes messages from Azure Service Bus Queues or Topics, providing reliable message delivery.

**Cosmos DB Trigger**: This trigger monitors changes to documents within a Cosmos DB collection. When a document is inserted or modified, the function is triggered.

**Event Grid Trigger**: It responds to events from Azure Event Grid, a fully managed event routing service. This allows you to react to events from various Azure services or custom sources.

These triggers enable you to build event-driven, scalable, and efficient serverless applications on Azure. Depending on your use case, you can choose the appropriate trigger for your Azure Function.



