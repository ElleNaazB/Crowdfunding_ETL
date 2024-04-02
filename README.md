# Crowdfunding ETL Project

## Overview
This project focuses on building an ETL (Extract, Transform, Load) pipeline using Python for data manipulation and analysis. It leverages the power of Pandas alongside Python's dictionary methods or regular expressions for data extraction and transformation. The culmination of this project involves creating four CSV files from the transformed data, developing an Entity Relationship Diagram (ERD) and a table schema for database integration, and uploading the data into a PostgreSQL database.

### Environment and Libraries
To accomplish the objectives of this project, a Python environment is required as well as ensuring the following libraries are installed:
- **Pandas**: For data manipulation and analysis.
- **PostgreSQL**: For database management.
- **Numpy**: For mathematical operations on arrays.
- **Openpyxl**: For reading and writing data.
- **Json**: For encoding data into JSON data.

Additionally, the project uses Jupyter notebooks for developing and testing the ETL pipeline.

Before running the code file, the environment will need to be updated with the relevant dependencies used for this project. To setup a new environment for this project, please see below:
1) Open a new terminal 
2) Execute 'conda env list' to see whether a suitable environment has already been created for this project. If not, please proceed to the following steps. 
3) Execute 'conda create --name crowdfunding_ETL' to create a new conda environment called "crowdfunding_ETL." Input 'y' if prompted.
4) Execute 'conda env list' to confirm whether the 'crowdfunding_ETL' environment has been successfully created. 
5) Execute 'conda list' to see the dependencies already loaded into this environment. 
6) Execute 'pip install pandas' to install pandas in the selected environment. 
7) Execute 'pip install openpyxl' to install openpyxl in the selected environment. 

### Project Tasks
This project accomplishes the following tasks:
- **Data Extraction and Transformation**: 
    - Extracts and transforms data from provided Excel files using Python, Pandas, and either dictionary methods or regular expressions.
    - Creates DataFrames for categories, subcategories, campaigns, and contacts with specific column requirements.
    - Cleans and prepares the data for loading into a database.
- **CSV File Creation**:
    - Generates four CSV files (`category.csv`, `subcategory.csv`, `campaign.csv`, `contacts.csv`) from the transformed DataFrames.
- **Database Design and Integration**:
    - Designs an ERD and a table schema for the crowdfunding database.
    - Creates a PostgreSQL database named `crowdfunding_db`.
    - Implements the table schema within the database, ensuring the correct handling of primary keys, foreign keys, and other constraints.
    - Loads data from the CSV files into the corresponding SQL tables in the database.
    - Verifies the integrity and correctness of the loaded data by executing SELECT statements.

### Deliverables
The project deliverables include: 
- The ETL pipeline Jupyter notebooks: <a href="https://github.com/ElleNaazB/Crowdfunding_ETL/blob/main/ETL_Mini_Project_EBehnia_ASelvam.ipynb "> ETL_Mini_Project_EBehnia_ASelvam </a>
- Four CSV files corresponding to the transformed DataFrames: <a href = "https://github.com/ElleNaazB/Crowdfunding_ETL/blob/main/Resources/campaign.csv"> campaign </a>, <a href ="https://github.com/ElleNaazB/Crowdfunding_ETL/blob/main/Resources/contacts.csv"> contacts</a>, <a href = "https://github.com/ElleNaazB/Crowdfunding_ETL/blob/main/Resources/category.csv"> category </a>, and <a href = "https://github.com/ElleNaazB/Crowdfunding_ETL/blob/main/Resources/subcategory.csv"> subcategory </a>
- The <a href="https://github.com/ElleNaazB/Crowdfunding_ETL/blob/main/Crowdfunding_DB_ERD%20Diagram.png"> ERD sketch and table schema</a> for the crowdfunding database.
- A PostgreSQL database schema file named<a href= "https://github.com/ElleNaazB/Crowdfunding_ETL/blob/main/Crowdfunding_DB_Schema.sql">  Crowdfunding_DB_Schema.sql </a>. 


