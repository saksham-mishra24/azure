# Azure Data Platform End2End (V2)


* We will learn about the main concepts related to advanced analytics and Big Data processing and how Azure Data Services can be used to implement a modern data warehouse architecture. 
* You will learn what Azure services you can leverage to establish a solid data platform to quickly ingest, process and visualise data from a large variety of data sources.
* The reference architecture you will build as part of this exercise has been proven to give you the flexibility and scalability to grow and handle large volumes of data and keep an optimal level of performance.

* We will build data pipelines using data related to New York City. 

* The workshop was designed to progressively implement an extended modern data platform architecture starting from a traditional relational data pipeline. 
* Then we introduce big data scenarios with large data files and distributed computing. 
* We add non-structured data and AI into the mix and finish off with real-time stream analytics. You will have done all of that by the end of the workshop.

## Workshop Proposed Agenda
The workshop can be completed on your own pace depending on your previous experince with the Azure DP tools. Supporting slides are available for each format.

### **1-Day Format**

#### Slides: [Azure Data Platform End2End - 1 Day](Slides/Azure%20Data%20Platform%20End2End%20-%201Day.pptx)

Activity | Duration
-------- | ---------
Workshop Overview | 15 minutes
Modern Data Platform Concepts: Part I | 15 minutes
**Modern Data Warehousing** |
Lab 1: Load Data into Azure Synapse Analytics using Azure Data Factory Pipelines    | 45 minutes
Modern Data Platform Concepts: Part II | 15 minutes
Lab 2: Transform Big Data using Azure Data Factory Mapping Data Flows    | 60 minutes
**Advanced Analytics** |
Modern Data Platform Concepts: Part III | 15 minutes
Lab 3: Explore Big Data using Azure Databricks    | 45 minutes
Modern Data Platform Concepts: Part IV | 15 minutes
Lab 4: Add AI to your Big Data Pipeline with Cognitive Services    | 75 minutes
**Real-time Analytics** |
Modern Data Platform Concepts: Part V | 15 minutes
Lab 5: Ingest and Analyse real-time data with Event Hubs and Stream Analytics   | 45 minutes

### **2-Day Format**

The workshop content will be delivered over the course of two days with the following agenda:

#### Slides: [Azure Data Platform End2End - 2 Day](./Slides/Azure%20Data%20Platform%20End2End%20-%202Day.pptx)

* ![image](https://user-images.githubusercontent.com/120908587/224524684-21427f3d-3976-4b60-baed-40a9984c5b6c.png)

### STREAM DATASET AND REALTIME DASHBOARDS-
* [THIS IS HOT PATH i.e., Real-time Analysis- ]
* streams,iot devices, sensory gadgets -- EVENT HUBS (Load & Ingest) - by lamda archietrure TO STREAM ANALYTICS (for process) - POWER BI 

* Event Hubs is a fully managed, real-time data ingestion service that's simple, trusted, and scalable. Stream millions of events per second from any source to build dynamic data pipelines and immediately respond to business challenges.

* Azure Stream Analytics is a fully managed stream processing engine that is designed to analyze and process large volumes of streaming data with sub-millisecond latencies.

* In summary, Azure Data Lake Storage Gen2 is ideal for big data analytics workloads, while Blob storage is ideal for storing and accessing unstructured data. Both solutions offer strong security features and are cost-effective compared to traditional data storage solutions.

* Azure Synapse SQL is a big data analytic service that enables you to query and analyze your data using the T-SQL language. You can use standard ANSI-compliant dialect of SQL language used on SQL Server and Azure SQL Database for data analysis.

* Azure Cosmos DB is a fully managed NoSQL and relational database for modern app development. Azure Cosmos DB offers single-digit millisecond response times, automatic and instant scalability, along with guarantee speed at any scale.

# AZURE VOCABOLARY

𝘼𝙯𝙪𝙧𝙚 𝙑𝙤𝙘𝙖𝙗𝙪𝙡𝙖𝙧𝙮 𝙁𝙤𝙧 𝙮𝙤𝙪:


* 𝗥𝗲𝘀𝗼𝘂𝗿𝗰𝗲: An entity that's managed by Azure. Examples include Azure Virtual Machines, virtual networks, and storage accounts.

* 𝗦𝘂𝗯𝘀𝗰𝗿𝗶𝗽𝘁𝗶𝗼𝗻: A logical container for your resources. Each Azure resource is associated with only one subscription. Creating a subscription is the first step in adopting Azure.

* 𝗔𝘇𝘂𝗿𝗲 𝗮𝗰𝗰𝗼𝘂𝗻𝘁: The email address that you provide when you create an Azure subscription is the Azure account for the subscription.

* 𝗔𝘇𝘂𝗿𝗲 𝗔𝗰𝘁𝗶𝘃𝗲 𝗗𝗶𝗿𝗲𝗰𝘁𝗼𝗿𝘆 (𝗔𝘇𝘂𝗿𝗲 𝗔𝗗): The Microsoft cloud-based identity and access management service. Azure AD lets your employees sign in and access resources.

* 𝗔𝘇𝘂𝗿𝗲 𝗔𝗗 𝘁𝗲𝗻𝗮𝗻𝘁: A dedicated and trusted instance of Azure AD. When your organization signs up for a Microsoft cloud service subscription, it automatically creates an Azure AD tenant.

* 𝗥𝗲𝘀𝗼𝘂𝗿𝗰𝗲 𝗴𝗿𝗼𝘂𝗽𝘀: Logical containers that you use to group related resources in a subscription.

* 𝗠𝗮𝗻𝗮𝗴𝗲𝗺𝗲𝗻𝘁 𝗴𝗿𝗼𝘂𝗽𝘀: Logical containers that you use for one or more subscriptions.

* 𝗥𝗲𝗴𝗶𝗼𝗻: A set of Azure datacenters that deploy inside a latency-defined perimeter.

* 𝗔𝘇𝘂𝗿𝗲 𝗣𝗼𝘄𝗲𝗿𝗦𝗵𝗲𝗹𝗹: A command-line interface to manage Azure services via a command line from Windows PCs.

* 𝗔𝘇𝘂𝗿𝗲 𝗖𝗟𝗜: A command-line interface for managing Azure resources from Windows, macOS, and Linux environments.

* 𝘀𝗵𝗮𝗿𝗲𝗱 𝗮𝗰𝗰𝗲𝘀𝘀 𝘀𝗶𝗴𝗻𝗮𝘁𝘂𝗿𝗲 (𝗦𝗔𝗦): A signature that enables you to grant limited access to a resource, without exposing your account key.

* 𝗦𝘁𝗼𝗿𝗮𝗴𝗲 𝗮𝗰𝗰𝗼𝘂𝗻𝘁: An account that gives you access to the Azure Blob, Queue, Table, and File services in Azure Storage.

* 𝗚𝗲𝗼-𝗿𝗲𝗽𝗹𝗶𝗰𝗮𝘁𝗶𝗼𝗻: The process of automatically replicating content such as blobs, tables, and queues within a regional pair.

* 𝗟𝗼𝗮𝗱 𝗯𝗮𝗹𝗮𝗻𝗰𝗲𝗿: A resource that distributes incoming traffic among computers in a network.

* 𝗧𝗮𝗴: An indexing term that enables you to categorize resources according to your requirements for managing or billing.


