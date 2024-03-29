# Crowdfunding ETL Project

## Overview
This project focuses on building an ETL (Extract, Transform, Load) pipeline using Python for data manipulation and analysis. It leverages the power of Pandas alongside Python's dictionary methods or regular expressions for data extraction and transformation. The culmination of this project involves creating four CSV files from the transformed data, developing an Entity Relationship Diagram (ERD) and a table schema for database integration, and uploading the data into a PostgreSQL database.

### Environment and Libraries
To accomplish the objectives of this project, a Python environment is required as well as ensuring the following libraries are installed:
- **Pandas**: For data manipulation and analysis.
- **PostgreSQL**: For database management.

Additionally, the project uses Jupyter notebooks for developing and testing the ETL pipeline.

### Project Tasks
This project accomplishes the following tasks:
- **Data Extraction and Transformation**: 
    - Extracts and transforms data from provided Excel files using Python, Pandas, and either dictionary methods or regular expressions.
    - Creates DataFrames for categories, subcategories, campaigns, and contacts with specific column requirements.
    - Cleans and prepares the data for loading into a database.
- **CSV File Creation**:
    - Generates four CSV files (`category.csv`, `subcategory.csv`, `campaign.csv`, `contacts.csv`) from the transformed DataFrames.
- **Database Design and Integration**:
    - Designes an ERD and a table schema for the crowdfunding database.
    - Creates a PostgreSQL database named `crowdfunding_db`.
    - Implements the table schema within the database, ensuring the correct handling of primary keys, foreign keys, and other constraints.
    - Loads data from the CSV files into the corresponding SQL tables in the database.
    - Verifies the integrity and correctness of the loaded data by executing SELECT statements.

### Deliverables
The project deliverables include: 
- The ETL pipeline Jupyter notebooks: <a href="https://github.com/ElleNaazB/Crowdfunding_ETL/blob/Ajunjee/ETL_Mini_Project_EBehnia_ASelvam.ipynb "> ASalvam </a> & <a href = "https://github.com/ElleNaazB/Crowdfunding_ETL/blob/Elle/ETL_Mini_Project_ASelvam_EBehnia.ipynb">EBehnia</a>
- Four CSV files corresponding to the transformed DataFrames: <a href = "https://github.com/ElleNaazB/Crowdfunding_ETL/blob/Elle/Resources/campaign.csv"> campaign </a>, <a href ="https://github.com/ElleNaazB/Crowdfunding_ETL/blob/Elle/Resources/contacts.csv"> contacts</a>, <a href = "https://github.com/ElleNaazB/Crowdfunding_ETL/blob/Elle/Resources/category.csv"> category </a>, and <a href = "https://github.com/ElleNaazB/Crowdfunding_ETL/tree/Elle/Resources"> subcategory </a>
- The <a href="https://github.com/ElleNaazB/Crowdfunding_ETL/blob/Elle/Crowdfunding_ETL_Database/QuickDBD-Crowdfunding_ETL.png"> ERD sketch and table schema</a> for the crowdfunding database.
- A PostgreSQL database schema file named<a href= "https://github.com/ElleNaazB/Crowdfunding_ETL/blob/Elle/Crowdfunding_ETL_Database/CoudFunding%20_ETL_Schema.sql">  `crowdfunding_db_schema.sql` </a>. 


