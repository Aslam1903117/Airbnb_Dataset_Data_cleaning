# Airbnb Dataset Cleaning Project

This project focuses on cleaning an Airbnb dataset to prepare it for Exploratory Data Analysis (EDA). The project utilizes Python and several libraries to perform a series of data cleaning tasks, ensuring the dataset is ready for further analysis.

## Project Overview

The primary goal of this project is to clean and preprocess the Airbnb dataset by performing the following tasks:

1. **Deleting Redundant Columns**: Remove columns that do not contribute to the analysis.
2. **Renaming Columns**: Standardize column names for better readability and consistency.
3. **Dropping Duplicate Values**: Eliminate duplicate entries to ensure data integrity.
4. **Cleaning Individual Columns**: Address specific issues within columns, such as inconsistent formatting.
5. **Removing NaN Values**: Handle missing data by removing or imputing NaN values.
6. **Changing Data Types**: Convert data types, such as changing strings to integers or boolean values to binary (1 or 0).

After cleaning, the dataset is saved in both CSV and Excel formats for easy access and further analysis.

## Installation

To run this project, you need to have Python installed along with the following libraries:

- pandas
- numpy
- openpyxl (for saving Excel files)

You can install the required libraries using pip:

```bash
