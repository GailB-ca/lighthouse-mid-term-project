# lighthouse-mid-term-project
Lighthouse Labs Data Science Midterm Project

Slide Deck
https://slides.com/gailbishop/midterm-project

## Table of Contents

1. [db_connection](/blob/main/db_connection.ipynb) - this notebook creates the Postgres db connection and is imported into other workbooks that require the connection
2. [Flights Dataframe ](/blob/main/Flights%20Dataframe.ipynb) - this workbook has exploratory data analysis of the Flights data
3. [Flights Dataframe 2](/blob/main/Flights%20Dataframe%202.ipynb) - this workbook has exploratory data analysis of the Flights data and related Fuel Consumption and Passengers data
4. [Feature Creation Methods](/blob/main/Feature_Creation_Methods.ipynb) - this workbook contains all methods to create the new features and stores the dataframe as a compressed csv
5. [Reference Dataframes](/?) - this workbook contains methods to create summary reference tables of data for creating aggregate features
6. [WeatherData](/?) - this workbook determines a list of 52 representative cities that were used to query the Weather API, and queries the Weather API for 12 months of aggregate weather data
7. [Regression Model Evaluation](/?) - this workbook run 3 regression models and shows evaluation methods for each
8. [Run Final Model](/?) - this workbook read the Test Data from a csv, runs the saved XGB model and exports the predictions to a csv
9. [submission_xgb.csv](/?) - the prediction file for the first week of January 2020

## Reference Folder
This contains Pickle files of dataframes created by the Reference Dataframe workbook. These pickle files were then imported into the Feature Creation Methods workbook.
