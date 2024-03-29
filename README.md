# Crowdfunding ETL Project

## Overview
This project focuses on building an ETL (Extract, Transform, Load) pipeline using Python for data manipulation and analysis. It leverages the power of Pandas alongside Python's dictionary methods or regular expressions for data extraction and transformation. The culmination of this project involves creating four CSV files from the transformed data, developing an Entity Relationship Diagram (ERD) and a table schema for database integration, and uploading the data into a PostgreSQL database.

### Environment and Libraries
To accomplish the objectives of this project, you'll need to work within a Python environment. Ensure you have the following libraries installed:
- **Pandas**: For data manipulation and analysis.
- **PostgreSQL**: For database management.

Additionally, the project uses Jupyter notebooks for developing and testing the ETL pipeline.

### Project Tasks
This project accomplishes the following tasks:
- **Data Extraction and Transformation**: 
    - Extract and transform data from provided Excel files using Python, Pandas, and either dictionary methods or regular expressions.
    - Create DataFrames for categories, subcategories, campaigns, and contacts with specific column requirements.
    - Clean and prepare the data for loading into a database.
- **CSV File Creation**:
    - Generate four CSV files (`category.csv`, `subcategory.csv`, `campaign.csv`, `contacts.csv`) from the transformed DataFrames.
    - Push these CSV files to a GitHub repository for version control and collaboration.
- **Database Design and Integration**:
    - Design an ERD and a table schema for the crowdfunding database.
    - Create a PostgreSQL database named `crowdfunding_db`.
    - Implement the table schema within the database, ensuring the correct handling of primary keys, foreign keys, and other constraints.
    - Load data from the CSV files into the corresponding SQL tables in the database.
    - Verify the integrity and correctness of the loaded data by executing SELECT statements.

### Deliverables
The project deliverables include: 
- The ETL pipeline Jupyter notebooks: <a href="https://github.com/ElleNaazB/Crowdfunding_ETL/blob/Ajunjee/ETL_Mini_Project_EBehnia_ASelvam.ipynb "> ASalvam </a> & <a href = "https://github.com/ElleNaazB/Crowdfunding_ETL/blob/Elle/ETL_Mini_Project_ASelvam_EBehnia.ipynb">EBehnia</a>
- Four CSV files corresponding to the transformed DataFrames: <a href = "https://github.com/ElleNaazB/Crowdfunding_ETL/blob/Elle/Resources/campaign.csv"> campaign </a>, <a href ="https://github.com/ElleNaazB/Crowdfunding_ETL/blob/Elle/Resources/contacts.csv"> contacts</a>, <a href = "https://github.com/ElleNaazB/Crowdfunding_ETL/blob/Elle/Resources/category.csv"> category </a>, and <a href = "https://github.com/ElleNaazB/Crowdfunding_ETL/tree/Elle/Resources"> subcategory </a>
- The <a href="https://github.com/ElleNaazB/Crowdfunding_ETL/blob/Elle/Crowdfunding_ETL_Database/QuickDBD-Crowdfunding_ETL.png"> ERD sketch and table schema</a> for the crowdfunding database.
- A PostgreSQL database schema file named<a href= "https://github.com/ElleNaazB/Crowdfunding_ETL/blob/Elle/Crowdfunding_ETL_Database/CoudFunding%20_ETL_Schema.sql">  `crowdfunding_db_schema.sql` </a>. 

This structured approach ensures a comprehensive understanding and execution of the ETL process, from data extraction and transformation to database loading, fostering collaboration and practical application of data manipulation and analysis techniques.
