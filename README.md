# SQL Challenge - Employee Database Analysis

## Overview

This repository presents a comprehensive data engineering and analysis project focused on a fictional employee database from the 1980s and 1990s. The project encompasses data modeling, database schema design, data import, and SQL queries for data analysis.

## Repository Structure

- `EmployeeSQL`: Contains SQL files for creating the database schema and performing data analysis.
  - `schema.sql`: Defines the table schema.
  - `queries.sql`: Contains SQL queries for data analysis.
- `ERD.png`: An image file of the Entity Relationship Diagram.

## Data Modeling

- An Entity Relationship Diagram (ERD) was designed to visualize the relationships among database entities.
- The SQL schema in `schema.sql` encapsulates the precise table definitions.

## Data Engineering

- Meticulous attention to detail was applied during the data engineering phase, where CSV data was skillfully imported into the database.
- All essential elements, including primary keys, data types, and foreign keys, were thoughtfully incorporated into the schema to ensure database integrity and optimal performance.

## Data Analysis

The following data analysis tasks were completed using SQL queries:

1. List employee number, last name, first name, sex, and salary of each employee.
2. List first name, last name, and hire date for employees hired in 1986.
3. List the manager of each department along with department number, department name, employee number, last name, and first name.
4. List the department number for each employee with their employee number, last name, first name, and department name.
5. List first name, last name, and sex of employees with first name "Hercules" and last name starting with "B."
6. List each employee in the Sales department, including employee number, last name, and first name.
7. List each employee in the Sales and Development departments, including employee number, last name, first name, and department name.
8. List the frequency counts of employee last names in descending order.

## Prerequisites

- PostgreSQL database management system.
- SQL client or tool (e.g., pgAdmin).

## Usage

1. Clone the repository to your local machine.
2. Create a PostgreSQL database and configure the connection in your SQL client.
3. Execute the `schema.sql` file to create the tables.
4. Import the provided CSV data into the respective tables.
5. Run the SQL queries from the `queries.sql` file to perform data analysis.

## License

This project is licensed under the MIT License.

## Author & Acknowledgments 

Author Jorge Nardy.
Data provided by University of Toronto. 
