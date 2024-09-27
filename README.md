# Motor Vehicle Collisions Analysis (2018-2021)
Overview
This project focuses on analyzing motor vehicle collisions in New York City from 2018 to 2021, a period that includes the height of the COVID-19 pandemic. Using data sourced from the New York Police Department (NYPD), we examine the temporal patterns of collisions, crash severity, and other variables to understand how the pandemic influenced driving behavior and road safety.

Dataset
The dataset contains detailed information on motor vehicle collisions in NYC, including crash dates, vehicle types, and contributing factors. The dataset covers incidents where a person was injured, killed, or where damage exceeded $1,000. The data includes:
* 25 Columns: Including crash time, crash date, vehicle type, and other factors.
* Time Frame: Focused on the years 2018 to 2021, capturing pre-pandemic and pandemic-affected periods.

Project Goals
To analyze how motor vehicle collisions were affected during the pandemic.
Identify temporal patterns, such as peak times for accidents.
Understand crash severity and repeat offenses.
Investigate vehicle types involved in crashes and their frequency.

Key Features
SQL Queries: We developed a series of SQL queries to analyze the dataset, focusing on:
Filtering crash data by year and severity.
Aggregating crash information based on time, location, and vehicle types.
Analyzing the patterns of repeat offenders.

Database Structure:
Normalized database schema, designed with primary keys and foreign keys for efficient querying.
Tables include: Collisions, Vehicles, and Vehicle_Damage.
ERD (Entity-Relationship Diagram) detailing the relationships between tables.

SQL Features:
Aggregate Functions (e.g., SUM, AVG)
Complex Queries (e.g., JOINs across multiple tables)
Common Table Expressions (CTEs)
Views for simplifying data extraction

Usage
Run Queries: Use the SQL scripts provided in the queries/ folder to analyze the data.
Views: Predefined views such as Car_by_Time and Driver_vehicles make it easier to access common queries without rewriting SQL code.
Analyze Results: Output from the queries will provide insights on crash patterns, severity, and repeat offenders.

Lessons Learned
SQL Proficiency: We significantly improved our skills in writing and optimizing SQL queries.
Database Normalization: We learned the importance of normalization to minimize redundancy and ensure efficient data querying.
Teamwork: Collaborating as a team allowed us to successfully integrate feedback and refine our approach to data analysis.
COVID-19 Impact: The pandemic created a unique driving environment, leading to both an increase and reduction in certain types of crashes, depending on the context.

Future Work
Temporal Pattern Analysis: Extend the analysis to specific times, such as weekends or rush hours, to identify high-risk periods.
Geospatial Analysis: Use location data to pinpoint high-collision areas and improve urban planning.
Pre- vs Post-Pandemic Comparison: Compare driving patterns before and after the pandemic to explore lasting changes in behavior.

Contributors
Ahmed Elhag
Joseph Rohan Kettish
Zayd Mahfuz
Antoine Williams
Manuel Orallo
