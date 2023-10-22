# Azure Data Factory Project Documentation
![ProjectArch](https://github.com/Abdullah28-gheyad/AzurePipeLine-Student-Teacher-/assets/68871710/e6d6b9c9-80b2-42b4-984e-df601beae47a)

![PipeLine Running](https://github.com/Abdullah28-gheyad/AzurePipeLine-Student-Teacher-/assets/68871710/ef8a2734-a126-45f5-82ed-4eaaeb948b6f)

![pipeline2](https://github.com/Abdullah28-gheyad/AzurePipeLine-Student-Teacher-/assets/68871710/2f34a2a1-8cb7-4a48-8343-2cbc2e5f4353)

![pipeline1](https://github.com/Abdullah28-gheyad/AzurePipeLine-Student-Teacher-/assets/68871710/9aa40ccb-fbd9-4338-a42d-932b41e5d156)


## Overview
This documentation outlines the steps taken to create an Azure Data Factory project for processing two Excel files (student details and teacher details). The project leverages Azure Blob Storage, data sets, data flows, and a full outer join operation to combine the data, ultimately saving the result in Parquet format.

**Project Components**
-  Data Sources: Student Details Excel, Teacher Details Excel
-  Data Storage: Azure Blob Storage
-  Data Factory: Azure Data Factory  
-  Data Sets: Student Data Set, Teacher Data Set
-  Data Flow: Data Flow Activity
-  Data Pipeline: Pipeline Activity
***Step-by-Step Guide***
1. Data Preparation
1.1. Data Upload:

Upload the Student Details and Teacher Details Excel files to Azure Blob Storage. Ensure proper organization within your storage containers.
2. Data Factory Setup
2.1. Azure Data Factory:

Create an Azure Data Factory in the Azure Portal if you haven't already.
2.2. Data Sets:

Configure data sets for Student Details and Teacher Details.
Specify the data source connection to the respective Excel files in Azure Blob Storage.
Ensure schema mapping and data structure compatibility.
3. Data Flow Configuration
3.1. Data Flow Creation:

Create a Data Flow within Azure Data Factory to process and transform the data.
Add appropriate source and sink transformations.
3.2. Join Operation:

Utilize the full outer join operation within the Data Flow to combine data from both student and teacher data sets.
Define join conditions as required.
3.3. Sink Configuration:

Configure the sink transformation to save the result in Azure Blob Storage.
Specify the output format as Parquet.
4. Pipeline Creation
4.1. Pipeline Activity:

Create a data pipeline within Azure Data Factory to orchestrate the data flow activity.
5. GitHub Integration
5.1. GitHub Repository:

Create a GitHub repository to host your Azure Data Factory project.
5.2. Upload to GitHub:

Using Git, upload your Azure Data Factory project to the GitHub repository. This can be done from your local development environment or directly from Azure DevOps.
Conclusion
Your Azure Data Factory project is successfully configured to process Excel data, perform a full outer join, and store the results in Parquet format. Users can access and utilize this project from the GitHub repository, which should include detailed documentation for reference.

Please provide thorough documentation in your GitHub repository, including any specific configuration settings, parameters, and considerations for users who may want to work with your project.

Thank you for using this documentation to showcase your project, and best of luck with your data processing endeavors.

