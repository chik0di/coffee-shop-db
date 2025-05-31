<h1 align="Center">The Coffee Shop Database Design & Implementation </h1>

<p align="center">
  <img src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExN2loeDY3aWM5YjZyc3Y4cGY5dTdtd3piaGYxdzloZzdydnVndGw1OCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/26ufe34jLiGEOqyM8/giphy.gif" width="400" alt="Coffee Brewing Animation" />
  &nbsp;&nbsp;&nbsp;
</p>


A New York-based coffee shop chain is expanding nationally and needs a robust, centralized database to streamline operations and support data-driven decision-making. Currently, their data is fragmented across multiple systems, including accounting software, supplier databases, point-of-sale (POS) systems, and spreadsheets.

My task is to design and implement a relational database system that consolidates this data, improves operational efficiency, and provides executives with actionable insights. This involves reviewing existing data sources, designing a comprehensive database schema, creating database objects, loading data, and exporting subsets for use in different relational database management systems (RDBMS). 


<h2 align="Center">Data Sources</h2>

The project integrates data from multiple sources:

- Staff Information – Stored in a spreadsheet at headquarters
- Sales Outlet Information – Maintained in a spreadsheet at headquarters
- Sales Data – Extracted as a CSV file from POS systems in sales outlets
- Customer Data – Exported as a CSV file from a custom customer relationship management (CRM) system
- Product Information – Sourced from supplier databases and maintained in spreadsheets

The Coffee Shop sample data can be retrieved [here](https://community.ibm.com/community/user/businessanalytics/blogs/steven-macko/2019/07/12/beanie-coffee-1113)


<h2 align="center">Tools and Technologies</h2> 

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original.svg" width="100" alt="PostgreSQL" />
  &nbsp;&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original.svg" width="100" alt="MySQL" />
</p>


          

<h2 align="Center">Key Tasks</h2>

- Identify Entities & Attributes – Define core data elements and their relationships
- Create an Entity-Relationship Diagram (ERD) – Use the pgAdmin ERD tool to model the database structure
- Normalize Tables – Ensure an efficient, scalable design
- Define Keys & Relationships – Establish primary keys, foreign keys, and constraints
- Create Database Objects – Generate and execute SQL scripts from the ERD tool
- Create & Export Materialized Views – Optimize query performance for reporting
- Import Data into MySQL – Use phpMyAdmin to stage data in a MySQL database

This project will enable the coffee shop chain to centralize data management, optimize decision-making, and scale efficiently as it expands nationwide.

<h3 align="right">Assigned By</h3>
<p align="right">
  <a href="https://www.coursera.org/account/accomplishments/verify/TG89DJFGV7VD?utm_source=link&utm_medium=certificate&utm_content=cert_image&utm_campaign=sharing_cta&utm_product=course">
    <img width="100" src="https://img.icons8.com/nolan/64/ibm.png" alt="IBM" />
  </a>
</p>
