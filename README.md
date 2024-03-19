Introduction
Welcome to the International Debt Analysis notebook! In this project, we'll be analyzing international debt data collected by The World Bank. This dataset contains information about the amount of debt (in USD) owed by developing countries across several categories.

Project Objective
The objective of this analysis is to gain insights into international debt trends and answer key questions such as:

What is the total amount of debt owed by the countries listed in the dataset?
Which country owns the maximum amount of debt and what does that amount look like?
What is the average amount of debt owed by countries across different debt indicators?
Data Description
The dataset contains the following columns:

country_name: Name of the country.
country_code: ISO code of the country.
indicator_name: Name of the debt indicator.
indicator_code: Code of the debt indicator.
debt: Total amount of debt owed by the country (in USD).
Analysis Steps
To achieve our objective, we'll perform the following analysis steps:

Connect to the Database: Connect to the PostgreSQL database containing the international debt data.
Retrieve Data: Retrieve the debt data from the database.
Total Debt: Calculate the total amount of debt owed by all countries listed in the dataset.
Maximum Debt: Identify the country that owns the maximum amount of debt and determine the corresponding amount.
Average Debt: Calculate the average amount of debt owed by countries across different debt indicators.
Tools Used
PostgreSQL: For querying the international debt data.
