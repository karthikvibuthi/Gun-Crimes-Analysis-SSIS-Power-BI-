# Gun Crimes Data Analysis Project

## Overview:
This project focuses on the analysis of gun crimes data sourced from Open Baltimore Data. The data is ingested, transformed, and stored using SQL Server Integration Services (SSIS) and SQL Server. The transformed data is then visualized and analyzed using Power BI.

## Project Components:

### 1. Data Ingestion:
The gun crimes data is sourced from Open Baltimore Data using the SSIS tool. SSIS provides a robust platform for extracting, transforming, and loading (ETL) data from various sources. In this project, we've utilized SSIS to extract the data and prepare it for further processing.

ETL Pipeline:
<img width="460" alt="image" src="https://github.com/karthikvibuthi/Gun-Crimes-Analysis-SSIS-Power-BI-/assets/141452458/31e9fe31-e842-4bec-b9b8-6d160714a453">

### 2. Data Storage:
After ingestion, the data is stored in SQL Server. SQL Server offers a reliable and scalable solution for storing structured data. We've leveraged SQL Server as our database management system to store the gun crimes data efficiently.

### 3. Data Transformation:
Once the data is stored in SQL Server, T-SQL queries are used to perform necessary transformations. T-SQL (Transact-SQL) is a powerful extension of SQL that enables us to manipulate and transform data within SQL Server. We've applied T-SQL queries to clean, preprocess, and reshape the data as required for analysis.

Data Flow:
<img width="483" alt="image" src="https://github.com/karthikvibuthi/Gun-Crimes-Analysis-SSIS-Power-BI-/assets/141452458/bc3ee5ea-7224-4d8e-adda-369b8b3bd3b1">

### 4. Data Analysis:
The transformed data is then visualized and analyzed using Power BI. Power BI is a business analytics tool that provides interactive data visualization capabilities. We've created insightful visualizations and dashboards in Power BI to explore trends, patterns, and insights within the gun crimes data.

Report:

<img width="387" alt="image" src="https://github.com/karthikvibuthi/Gun-Crimes-Analysis-SSIS-Power-BI-/assets/141452458/b979d027-4093-49f7-aabe-fb15f89820b8">

## How to Use:

### Prerequisites:
- Install SQL Server and SQL Server Management Studio (SSMS) for data storage and T-SQL queries.
- Install Power BI Desktop for data analysis and visualization.
- Ensure SSIS is installed if you plan to replicate the data ingestion process.

### Steps:
1. **Data Ingestion:**
   - Open the SSIS package provided in the repository.
   - Configure the data source connection to fetch gun crimes data from Open Baltimore Data.
   - Execute the SSIS package to ingest the data into SQL Server.

2. **Data Storage:**
   - Use SQL Server Management Studio to create a database for storing the gun crimes data.
   - Execute the T-SQL scripts provided in the repository to create tables and define schema.
   - Load the ingested data into the SQL Server database.

3. **Data Transformation:**
   - Utilize SSMS to run T-SQL queries for data transformations.
   - Modify the queries as per specific transformation requirements.

4. **Data Analysis:**
   - Open the Power BI file provided in the repository.
   - Connect Power BI to the SQL Server database containing the transformed data.
   - Explore the pre-built visualizations and dashboards to analyze the gun crimes data.

## Contributors:
- Kathik Vibuthi

## Acknowledgements:
- Open Baltimore Data for providing the gun crimes dataset.
- Microsoft for developing SSIS, SQL Server, and Power BI.

---

Feel free to customize this README file according to your project's specific details and requirements. Good luck with your project!
