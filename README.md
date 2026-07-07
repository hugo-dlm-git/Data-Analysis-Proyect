##Sales, Customers and Incidents Analytics Project

## Project Overview, Business Context and Objectives

This project presents an end-to-end data analytics workflow focused on sales, customers, products, orders, locations and operational incidents.
The original dataset was provided as a flat CSV file containing commercial and operational information. The main goal of the project is to transform this raw dataset into a structured analytical solution using Python, SQL Server and Power BI.
The project simulates a business reporting scenario where a company needs to monitor sales performance, profitability, customer behavior, product performance and operational efficiency. To enrich the analysis, a synthetic incidents table was created to represent operational issues linked to customer orders.
The workflow covers the full data analytics process: data cleaning, quality checks, relational data modeling, SQL-based validation and business analysis, Power BI data modeling, DAX measure creation and dashboard development.


## Tools and Technologies

The project uses the following tools and technologies:

* **Python / pandas**: used for data loading, cleaning, quality checks, data type conversion, text cleaning, synthetic incident generation and relational table creation.
* **Jupyter Notebook / VS Code**: used as the main development environment for the Python data preparation process.
* **SQL Server / SSMS**: used to import the processed CSV files, validate the relational model and run business analysis queries.
* **Power BI**: used to build the analytical model, define relationships and create the final interactive dashboard.
* **Power Query**: used for final data type checks, model preparation and reporting-specific transformations.
* **DAX**: used to create dynamic measures, KPIs, ratios, rankings and time intelligence calculations.
* **GitHub**: used to organize, document and present the complete project as a professional portfolio repository.

## Dataset Description

The original dataset was a Global Superstore-style CSV file with approximately 50,000 rows. It contained sales, orders, customers, products, locations, shipping and date-related fields in a single flat table.

## Repository Structure


## End-to-End Workflo
Raw CSV Dataset ↦ Python Data Cleaning and Quality Checks ↦ Relational Table Generation ↦ SQL Server Import ↦ SQL Data Validation and Business Analysis ↦ Power BI Data Model ↦ DAX Measures and Dashboard ↦ Business Insights

## Data Cleaning and Preparation with Python

Python was used to perform the initial cleaning and preparation of the dataset. The main steps included:

* Loading the original CSV file.
* Checking null values, duplicates and data types.
* Renaming columns.
* Converting date and numeric columns.
* Cleaning text fields.
* Reviewing inconsistencies.
* Creating a synthetic `incidents` table entirely with Python to simulate operational issues and enrich both the SQL analysis and the Power BI visuals.
* Splitting the original flat table into clean relational tables.
* Exporting the final tables as CSV files.


## Relational Data Model

## 10. SQL Server Analysis

## DAX Measures

## Dashboard Design

## Key Business Insights

## How to Reproduce the Project

To reproduce this project, follow these steps:

1. Clone this repository to your local machine.
2. Install the required Python dependencies listed in `requirements.txt`.
3. Open the data cleaning notebook located in the `notebooks/` folder.
4. Run the notebook to process the original raw CSV file.
5. Export the cleaned and transformed tables to the `data/processed/` folder.
6. Import the processed CSV files into SQL Server using SSMS.
7. Run the SQL scripts located in the `sql/` folder to validate the data and perform business analysis.
8. Open the Power BI file located in the `powerbi/` folder.
9. Check the relationships, Power Query transformations and DAX measures.
10. Refresh the Power BI model if needed.
11. Review the dashboard pages and business insights.

## Limitations and Future Improvements

## What This Project Demonstrates

This project demonstrates the ability to complete a full data analytics workflow from raw data to business reporting.
It shows practical skills in:

* Cleaning and preparing data with Python.
* Performing data quality checks.
* Transforming a flat dataset into a relational model.
* Separating customers, products, locations, orders, order details and incidents into different analytical tables.
* Importing and validating data in SQL Server.
* Writing SQL queries for business analysis.
* Using joins, aggregations, CTEs, subqueries and window functions.
* Building a Power BI data model.
* Preparing data for reporting with Power Query.
* Creating DAX measures for KPIs, ratios, rankings and time-based analysis.
* Designing an interactive dashboard.
* Communicating business insights clearly.
* Structuring and documenting a data analytics project in GitHub.

Overall, this project reflects the core technical and analytical skills required for junior Data Analyst, BI Analyst, Reporting Analyst or Operations Analyst roles.

