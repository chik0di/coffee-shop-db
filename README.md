# Project: The Coffee Shop Database Design & Implementation

## Backstory
A New York based coffee shop chain that is looking to expand nationally by opening a number of franchise locations. As part of their expansion process, they want to streamline operations and revamp their data infrastructure.

My job is to design their relational database systems for improved operational efficiencies and to make it easier for their executives to make data driven decisions.

Currently their data resides in several different systems: accounting software, suppliers’ databases, point of sales (POS) systems, and even spreadsheets. I must review the data in all of these systems and design a central database to house all of the data. I will then create the database objects and load them with source data. Finally, I shall create subsets of data that your business partners require, export them, and then load them into staging databases that use different RDBMS.

## Data Sources
In this scenario, I worked with data from the following sources:

- Staff information held in a spreadsheet at headquarters (HQ)
- Sales outlet information held in a spreadsheet at HQ
- Sales data output as a CSV file from the POS system in the sales outlets
- Customer data output as a CSV file from a custom customer relationship management system
- Product information maintained in a spreadsheet exported from your supplier's database

  The Coffee Shop sample data can be retrieved [here](https://community.ibm.com/community/user/businessanalytics/blogs/steven-macko/2019/07/12/beanie-coffee-1113)

## Softwares Used 
PostgreSQL 
MySQL

## What did I do? 
- Identify entities
- Identity attributes
- Create an entity relationship diagram (ERD) using the pgAdmin ERD tool
- Normalize tables
- Define keys and relationships
- Create database objects by generating and running the SQL script from the ERD tool
- Create a view and export the data
- Create a materialized view and export the data
- Import data into a MySQL database using phpMyAdmin GUI tool

