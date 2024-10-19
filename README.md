# Final Project: Predicting Tomato Yield using Regression

**Author**: Omer Shadmi

## Overview

This project addresses a regression problem aimed at predicting the continuous value of `tomato_yield`, based on several numerical variables related to environmental factors and plant measurements. The goal is to analyze the impact of different variables on the target variable, `tomato_yield`, and understand how factors such as plant size, pollination activity, and temperature conditions contribute to the yield. The dataset used in this project is focused on tomato crops, containing 15,289 rows and 18 columns with various measured variables related to tomato growth and environmental conditions. This analysis helps in gaining insights into how these factors interact and influence overall tomato production.


## Dataset

The dataset used for this project is `tomatoes.csv`, and it contains numerical variables like:

- **Average Plant Size**: Area occupied by a single plant (in square meters)
- **Bee Pollination Activity**: Number of bees visiting per square meter per minute
- **Maximum/Minimum Upper Bloom Temperature**: Recorded temperatures during the bloom season
- **Tomato Yield**: The total production in terms of weight per plant per area (in kg)

The dataset is processed to handle missing values and ensure all variables are in a numerical format.

## Key Steps

1. **Data Preparation**:
   - Importing necessary libraries (Pandas, Matplotlib, Seaborn).
   - Loading and inspecting the dataset.

2. **Exploratory Data Analysis**:
   - Generated summary statistics using `.describe()` and `.info()`.
   - Investigated the distribution of values, missing data, and unique element counts for each variable.

3. **Data Cleaning**:
   - Identified missing values, especially in the "Average Upper Bloom Temperature" column where some values were recorded as words instead of numbers.
   - Addressed negative values and replaced non-numeric values with NaN or zeros.

4. **Numerical Analysis**:
   - Described each variable and its impact on the target (`tomato_yield`).

## Project Files

- `Final_Project_Omer_Shadmi.ipynb`: The Jupyter notebook containing all code, analysis, and results.

## Requirements

The project requires the following libraries:

- Pandas
- Matplotlib
- Seaborn
- Numpy

## Conclusion
This project successfully explores the data and prepares it for further regression modeling. It focuses on handling missing data, verifying data types, and extracting valuable insights from numerical variables.


