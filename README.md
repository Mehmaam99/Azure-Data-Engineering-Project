# Azure-Data-Engineering-Project

Create a real-time Azure Cloud Data Engineering Project using the Olympics Dataset.

## Architecture Diagram
![Azure Architecture Diagram](https://github.com/Mehmaam99/Azure-Data-Engineering-Project/assets/45142408/b1d95d82-7cd1-42f4-97c6-4a39100b9bb4)

## Data Source
Download the dataset from Kaggle and store it on GitHub. Access the dataset using Azure Data Factory.

Dataset link: [Olympics Dataset](https://www.kaggle.com/datasets/arjunprasadsarkhel/2021-olympics-in-tokyo)

## Azure Data Factory
Create a pipeline using Azure Data Factory (ADF) to extract data via HTTP and store it in Azure Data Lake Storage Gen 2.

## Azure Databricks
Retrieve data from Azure Data Lake Storage Gen 2, perform necessary transformations using Azure Databricks, and then store the transformed data back in Azure Data Lake Storage Gen 2.

## Azure Synapse Analytics
Utilize Azure Synapse Analytics for data warehousing. Execute SQL commands to uncover insights within the data. Establish a linked service to connect to Power BI for data visualization.

# Important Notes
Encountering issues? Here's where to find solutions:
- Data source and Data Factory components are functioning smoothly.
- Integrating with Databricks is presenting some challenges.
- If you encounter an error while creating an account for the Synapse Analytics service, you can refer to this link for assistance: [Azure Synapse Analytics Account Creation Error](https://learn.microsoft.com/en-us/answers/questions/739391/permission-on-subscription-when-creating-azure-syn)
- Connecting with Power BI requires a workspace name. To obtain this, you need an organizational account and a Power BI Pro version.
