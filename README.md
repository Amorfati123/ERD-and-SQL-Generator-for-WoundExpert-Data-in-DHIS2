# ERD-and-SQL-Generator-for-WoundExpert-Data-in-DHIS2
This repository contains a Python script for generating an Entity Relationship Diagram (ERD) and corresponding SQL statements from CSV files. This script is part of a research project focusing on the WoundExpert system data within the DHIS2 framework.

## Features
### Dynamic ERD Generation: Automatically generates an ERD based on the structure of the CSV files.
### SQL Statement Creation: Produces SQL statements for table creation and relationships, facilitating easy database setup.
### Custom Data Mapping: Implements a custom data type mapping function to handle various data types in CSV files.

## Technologies and Libraries Used
### Python: The primary programming language for the script.
### Pandas: For reading and processing CSV files.
### SQLAlchemy: Used for ORM (Object Relational Mapping) and generation of SQL statements.
### SQLite: A lightweight database used for creating dummy SQL statements.

## Setup and Usage

Clone the Repository: Clone this repository to your local machine.

Install Dependencies: Install necessary Python packages - Pandas and SQLAlchemy.

Configure Paths: Set the folder_path variable to the location of your CSV files and output_dir for where you want to save the SQL file.

Run the Script: Execute the Python script to generate the ERD and SQL statements.

## File Structure
Sample CSV files representing different data tables in the WoundExpert system.
The output SQL file contains table creation statements and relationships.

## Customization

You can add or modify the relevant_columns dictionary to reflect the structure of your CSV files.
Adjust the dtype_mapping function to handle additional data types as required.
