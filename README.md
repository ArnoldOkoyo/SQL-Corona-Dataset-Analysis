Global COVID-19 Analysis (SQL)
Project Description
This SQL project focuses on analysing global COVID-19 trends using comprehensive datasets from the Worldometer repository. The project includes infection rates, recovery trends, and vaccination progress, aiming to provide insights into COVID-19 impacts across regions and over time. Public health insights gained through this project demonstrate competencies in SQL data handling, processing, and analysis of large datasets.
Data Overview
Datasets:
•	worldometer_coronavirus_summary_data: Contains summary COVID-19 data by country and region, including cumulative cases, recoveries, and fatalities.
•	worldometer_coronavirus_daily_data: Contains daily updates of infection and vaccination numbers for individual countries, enabling time-series analysis.
Objective
The goal is to derive key public health insights, tracking COVID-19’s impact and the effectiveness of vaccination efforts. This project demonstrates proficiency in handling, processing, and analysing large-scale data in SQL.
Data Pipeline Summary
1.	Data Acquisition: Load datasets into SQL for processing.
2.	Data Cleaning and Transformation: Ensure data consistency, remove duplicates, standardize data types, and handle missing values.
3.	Data Storage: Store cleaned data in SQL tables (worldometer_summary and worldometer_daily).
4.	Data Analysis:
•	Track infection trends, fatality and recovery rates, and vaccination progress over time and by region.
•	Use joins to perform comparative analysis across tables.
5.	Data Export: Export significant insights or aggregated data for reporting or visualization purposes.
SQL Queries and Analytical Approach
•	Trend Analysis: Queries calculating weekly and monthly infection trends by region.
•	Vaccination Analysis: Queries analysing the rate of vaccination rollout and its impact on infection rates.
•	Comparative Analysis: Combine daily and summary data to observe day-to-day variations relative to overall progress.
Setup and Usage
1.	Database Setup:
•	Create a database labelled COVID19_Global_Analysis in SQL Server.
•	Import the datasets as tables (worldometer_summary and worldometer_daily).
2.	Running Queries:
•	Sample SQL scripts are available in the /queries folder, providing starting points for trend, vaccination, and comparative analysis.
•	Customize scripts to focus on specific regions or timeframes.
3.	Dependencies: SQL Server or a compatible SQL environment is required to execute the analysis queries.
Contributions
If interested in contributing to this project, feel free to fork the repository, suggest improvements, or reach out to collaborate on enhancing this analysis.

