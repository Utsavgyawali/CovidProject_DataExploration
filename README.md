COVID-19 Global Data Exploration
Project Overview
This project serves as a comprehensive demonstration of data exploration and analysis using SQL (Microsoft SQL Server). The objective was to analyze real-world COVID-19 datasets to extract meaningful insights regarding infection rates, mortality, and vaccination progress across the globe.

This project is a critical component of a data analyst portfolio, showcasing the ability to transform raw, messy data into clean, queryable information ready for visualization.

Key Skills Demonstrated
Data Wrangling: Importing and cleaning raw Excel datasets into structured relational database tables.
SQL Proficiency: Writing complex queries using JOINS, CTEs (Common Table Expressions), Temp Tables, and Window Functions to calculate rolling metrics.
Data Normalization: Handling NULL values and applying data type conversions to ensure accurate statistical calculations.
Database Design: Creating permanent VIEWS to optimize data retrieval for downstream BI tools like Tableau.
Technical Implementation
Data Cleaning: Transformed large-scale raw data to isolate relevant columns (location, date, total_cases, new_cases, total_deaths, population, new_vaccinations).
Exploratory Data Analysis (EDA):
Calculated the likelihood of death per infection by country.
Analyzed total cases versus population to determine infection penetration.
Identified countries with the highest infection rates compared to their respective populations.
Analyzed global mortality and vaccination statistics.
Advanced SQL Techniques:
Used CTEs to manage complex sub-queries.
Implemented Temp Tables for efficient data manipulation.
Created SQL Views to store calculated metrics for future visualization, demonstrating clean, reproducible data workflows.
Dataset Source
Data sourced from Our World in Data (COVID-19 dataset).
How to Use
Clone this repository.
Import the provided .xlsx files into your SQL Server instance.
Run the SQL script to reproduce the data exploration and generate the analytical views.
This project was developed to showcase foundational data analysis capabilities for roles in Data Analytics and Business Intelligence.
