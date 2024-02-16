# Netflix Titles Data Cleaning Project

## Overview

This project focuses on cleaning and ensuring the quality of the Netflix titles dataset obtained from Kaggle. The dataset contains information about movies and TV shows available on Netflix, including details such as title, director, cast, country, release year, rating, duration, genre, and description. The cleaning process involves handling missing values, removing duplicates, standardizing text data, and correcting errors to prepare the dataset for analysis and further usage.

## Project Components

1. **Data Loading**: 
   - The dataset is loaded into a Pandas DataFrame using the `pd.read_csv()` function.

2. **Data Cleaning Steps**:
   - **Step 1**: Check for missing values using the `isnull().sum()` method.
   - **Step 2**: Remove duplicates using the `drop_duplicates()` method.
   - **Step 3**: Standardize text data, such as capitalizing the first letter of director names using the `str.title()` method.
   - **Step 4**: Correct errors, such as misspelled values, in certain columns. For example, correcting the 'type' column to contain only 'TV Show' or 'Movie'.

3. **Save Cleaned Dataset**:
   - The cleaned dataset is saved to a CSV file named `cleaned_data.csv` using the `to_csv()` method.

## Usage

1. **Data Cleaning**:
   - Open the provided Jupyter Notebook.
   - Run the notebook cells sequentially to execute each data cleaning step.
   - Review the output after each step to ensure data quality improvements.

2. **Customization**:
   - Modify the cleaning steps or add additional cleaning procedures as needed based on specific requirements or data quality issues encountered.

3. **Dependencies**:
   - Python 3.x
   - Jupyter Notebook
   - pandas
