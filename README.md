# NYC Yellow Taxi Data Analysis

## Project Overview
This project explores the initial inspection and preparation of New York City Yellow Taxi trip data provided by the NYC Taxi & Limousine Commission (TLC). It was completed as part of the Google Data Analytics / Foundations of Data Science learning experience on Coursera.

The objective is to understand the dataset's structure, assess data quality, identify relevant variables, and prepare the data for future exploratory data analysis and predictive modeling.

## Objectives
- Import and inspect data using Python.
- Examine DataFrame dimensions, column names, data types, and non-null counts.
- Investigate trip distance and total fare values.
- Analyze payment methods, vendor distribution, and recorded tip amounts.
- Identify potential anomalies and opportunities for feature engineering.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Jupyter Notebook

## Dataset
The notebook dataset contains 22,699 rows and 18 columns. Variables include pickup and drop-off timestamps, passenger count, trip distance, location IDs, payment type, fare amount, tips, tolls, and total amount.

Source: [NYC Taxi & Limousine Commission](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)

## Initial Findings
- The dataset contains 22,699 rows and 18 columns.
- The initial inspection reported no null values across the columns.
- Pickup and drop-off timestamps are stored as object data types and should be converted to datetime.
- Extreme distances and fare amounts require further investigation.
- The purpose of the `Unnamed: 0` column should be verified.

## Next Steps
1. Validate potential outliers and duplicate records.
2. Convert timestamps and calculate trip duration.
3. Explore relationships between trip characteristics and fares.
4. Define a prediction target and select appropriate features.
5. Develop and evaluate a baseline predictive model.

## Learning Outcomes
This project demonstrates foundational skills in Python-based data inspection, DataFrame manipulation, summary statistics, variable assessment, and analytical communication.

**Acknowledgment:** Completed as a guided learning project using Coursera course materials and NYC TLC trip data.
