# Employee Payroll Database

## Overview

This project aims to create a payroll database based on the Employee_Payroll_2023.csv dataset, containing approximately 5000 records of payroll employee information from the City of Los Angeles in the US. The database will be designed using MySQL Workbench, with tables representing entities and their attributes from the dataset. 

## General Instructions

1. **Exploring the Dataset**
   
   - Download Employee_Payroll_2023.csv
   - Open the dataset in Excel to understand its structure and content
   - Identify entities and their attributes that need to be stored as tables in the payroll database

2. **Creating the Database**
  
   - Launch MySQL Workbench
   - Create a new database (see Database_Employee_Payroll_2023.sql)

3. **Creating Tables**
     
    Based on the identified entities and attributes, create different tables in the database with the following fields:

    - **Department Table:** DEPARTMENT_NO, DEPARTMENT_TITLE
   
    - **Job Table:** JOB_CLASS_PGRADE, JOB_TITLE
    
    - **Employee Table:**  EMPLOYEE_NO, GENDER, ETHNICITY,  EMPLOYMENT_TYPE, JOB_STATUS
    
    - **Pay Table:** EMPLOYEE_NO, REGULAR_PAY, OVERTIME_PAY, ALL_OTHER_PAY, TOTAL_PAY
   
    - **Benefits Table:** EMPLOYEE_NO, CITY_RETIREMENT_CONTRIBUTIONS, BENEFIT_PAY


4. **Inserting Data into Tables**
   
   - To populate the tables, use an online Excel to SQL converter like TableConvert (https://tableconvert.com/excel-to-sql) to convert the data from the columns into SQL statements
   - Copy and paste the converted SQL statements into MySQL Workbench to insert values into their respective tables


5. **Making Tables Relational**
  
   - Add primary keys to each table to uniquely identify records within the tables
   - Establish relationships between tables by defining appropriate foreign keys that reference the primary keys of related tables


## SQL Queries and Analysis

After creating the database, we can use SQL queries to perform various analyses on the payroll data. 
You can find some samples questions we could answer in the file Analysis_Employee_Payroll_2023.sql
These are just a few examples of the analyses you could perform using SQL queries. SQL provides powerful tools to filter and analyse data, allowing you to gain valuable insights from the Employee Payroll Database.


## Source

https://controllerdata.lacity.org/Payroll/City-Employee-Payroll-Current-/g9h8-fvhu
