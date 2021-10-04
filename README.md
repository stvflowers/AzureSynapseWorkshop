# Azure Synapse Analytics Enablement Workshop

## Summary

The goal of this repository is to provide the attendees with a 3-hour workshop to introduce Synapse. The schedule below outlines a strict schedule for delivering the workshop. The goal is to provide presentation materials as well as light hands-on work to introduce Synapse to the audience.


## Schedule

Task|Time|Goal
----|----|----
Introductions | 15 min | Introductions are important to understand the audience. Who is in attendance? What is their role? Do you need to increase or decrease the technical content of the session?
Presentation: Azure Synapse Analytics | 30 min | Presentation to introduce the high-level components of Synapse and how they are positioned in the Modern Data Architecture.
Hands on: Create workspace, analyze with Serverless Pools and Spark | 30 min | Work through creating a workspace and getting started with Serverless pools and Spark pools.
Break | 15 min
Hands on: Analyze using Dedicated SQL pools | 15 min | Create a dedicated SQL pool and begin working with the pool. For hosts of the workshop, make sure the audience is clear on the differences between Serverless and Dedicated at this point.
Hands on: Analyze data in a storage account | 15 min | This module is focused on interacting with files in ADLS.
Hands on: Integrate with pipelines and Power BI | 15 min | Introduction to the orchestration features of Synapse Pipelines
Challenges | 15 min | 3 tasks to complete to show and understanding of Synapse.
Open discussion | 30 min | This is reserved for Question and Answer. However, if the audience has experience with Synapse or big data analytics it would be best to get a list of questions the team may have in advance. This time can be used to tackle specific questions such as when to choose Synapse Spark or Databricks.

## Requirements

There are requirements to successfully deliver this workshop.

- Access to an Azure Subscription
- Owner or Contributor rights to a resource group
- An Azure Storage account
- Access to an administrator if issues arise
- Access to a Power BI workspace

## Hands On Exercises

[Create a Synapse Workspace](https://docs.microsoft.com/en-us/azure/synapse-analytics/get-started-create-workspace)

Module questions:
- What is the Data module used for?
- What is the Develop module used for?
- What is the Integrate module used for?

[Analyze data with a serverless SQL pool](https://docs.microsoft.com/en-us/azure/synapse-analytics/get-started-analyze-sql-on-demand)

Module Questions:
- What does OPENROWSET function do?
- What do you think the benefit is of accessing the data in the data lake rather than a traditional database?

[Analyze with Apache Spark](https://docs.microsoft.com/en-us/azure/synapse-analytics/get-started-analyze-spark)

Module Questions:
- What languages are supported in Synapse Spark pools?
- What is a data frame?

[Analyze data with dedicated SQL pools](https://docs.microsoft.com/en-us/azure/synapse-analytics/get-started-analyze-sql-pool)

Module Questions:
- How is a Dedicated pool different from a Serverless pool?
- What is a DWU?
- What is PolyBase?

[Analyze data in a storage account](https://docs.microsoft.com/en-us/azure/synapse-analytics/get-started-analyze-storage)

Module Questions:
- What is ABFS? WASB?
- What is Parquet?

[Integrate with pipelines](https://docs.microsoft.com/en-us/azure/synapse-analytics/get-started-pipelines)

Module Questions:
- What is ETL? ELT?
- How does this compare to orchestration?

[Visualize data with Power BI](https://docs.microsoft.com/en-us/azure/synapse-analytics/get-started-visualize-power-bi)

Module Questions:
- Which is more performant: to load data to a Power BI report from Synapse Dedicated or Synapse Serverless?


