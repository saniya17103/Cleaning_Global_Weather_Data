Global Weather Data Cleaning 
Project Overview

This project focuses on cleaning and preparing a public Global Weather Repository dataset using Python, Pandas, and NumPy.

The objective is to identify and handle common data-quality issues such as missing values, duplicate records, incorrect data types, and inconsistent or invalid values.

Dataset
Dataset: Global Weather Repository
Source: Kaggle
Rows: 166,838
Columns: 41
Format: CSV
Data Cleaning Performed

The following data-quality checks and cleaning operations were performed:

Checked for missing values
Checked and removed duplicate records
Corrected the last_updated column to datetime format
Removed unnecessary spaces from text values
Standardized categorical values such as country and wind direction
Validated latitude and longitude ranges
Checked weather measurements for invalid values
Handled unrealistic wind speed and pressure values
Identified and cleaned invalid negative air-quality measurements
Validated humidity, cloud cover, precipitation, and other weather-related fields
Handled missing values created during the cleaning process
Performed final data-quality checks
Tools Used
Python
Pandas
NumPy
Jupyter Notebook
Files in This Repository
├── Global_Weather_Repository_Cleaned.csv
├── clean_weather_task1.py
├── cleaning_report.csv
└── README.md
Result

The dataset was successfully cleaned and validated while preserving the original dataset structure. The cleaned CSV is ready for further analysis and EDA.

Future Scope

Exploratory Data Analysis (EDA), visualization, and weather-related insights can be performed using the cleaned dataset in a separate project phase.
