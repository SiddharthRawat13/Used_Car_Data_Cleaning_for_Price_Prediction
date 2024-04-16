# Car Data Analysis and Cleaning for Price Prediction
## Overview
This project focuses on analyzing and cleaning car data extracted from an auto trader website.
The objective is to prepare the data for machine learning algorithms to predict car prices accurately.
Additionally, the cleaned data is visualized in a PowerBI dashboard for better insights and understanding.

## Data Extraction
The initial step involved extracting car data from the auto trader website. The data was stored in a CSV file named car_data2.csv.
![autotr uncleanddata](https://github.com/SiddharthRawat13/used-Car-Data-Cleaning-for-Price-Prediction/assets/145152277/7bd90d8e-ea41-4dfa-b0f2-51d072bca801)
  Raw Data
## Data Cleaning
![autotradecleaneddata](https://github.com/SiddharthRawat13/used-Car-Data-Cleaning-for-Price-Prediction/assets/145152277/d32858e9-4aca-4d84-be38-e992aa60411a)
 Clean Data
## Engine Details
Engine Size: Extracted the engine size from the 'Engine' column using regex, e.g., 6.2L, 1.6L.
Cylinders: Extracted the number of cylinders from the 'Engine' column, e.g., 8, 4.
Engine Type: Extracted the engine type from the 'Engine' column, e.g., Gas Engine, Turbo Gas Engine.
## Mileage Details
City Mileage and Highway Mileage: Separated the 'Average' column into two separate columns for city and highway mileage.
## Transmission Details
Gear: Extracted the gear information from the 'Transmission' column.
Transmission Type: Extracted the transmission type (Automatic or Manual) from the 'Transmission' column.
## Price and Mileage Conversion
Removed ',' from the 'Price' column and converted it to numeric data type.
Removed 'miles' from the 'Miles' column and converted it to numeric data type.
Removed 'L' suffix from the 'engine size' column and converted it to numeric data type.
## Handling Missing Values
Filled missing values in numeric columns with their respective means.
Filled missing values in categorical columns with their respective modes.
## Data Type Conversion
Converted relevant columns to numeric data types to prepare for machine learning algorithms.
## Visualization
After cleaning the data, it was visualized in a PowerBI dashboard to provide a comprehensive view of the car data.
This visualization aids in understanding the relationships between different variables and can assist in making informed decisions.

## Machine Learning
The cleaned data I used in machine learning algorithms to predict car prices accurately.
The next steps involve feature selection, model training, and evaluation to build a predictive model.


This project demonstrates the process of extracting, cleaning, and preparing car data for machine learning-based price prediction.
The cleaned data is visualized in PowerBI for better insights, and it serves as a foundation for developing predictive models to estimate car prices effectively.
