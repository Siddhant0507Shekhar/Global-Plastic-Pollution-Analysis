# Global Plastic Pollution Analysis

This project focuses on analyzing global plastic pollution data. It involves the use of data science techniques to explore and visualize the relationship between per capita plastic waste and GDP per capita in different countries.

## Project Overview

The project consists of the following main steps:

1. Importing necessary libraries:
   - `numpy` for numerical computations
   - `pandas` for data manipulation and analysis
   - `seaborn` for data visualization
   - `matplotlib` for creating plots
2. Reading the dataset:
   - The dataset is loaded from the file `per-capita-plastic-waste-vs-gdp-per-capita.csv`.
3. Data exploration:
   - Displaying the first 5 rows of the dataset
   - Checking the shape of the data (number of rows and columns)
   - Checking for null values in the data and calculating the percentage of null values in each column
   - Checking the information about the data, including column names, non-null counts, and data types
4. Data preprocessing:
   - Renaming column names for clarity
   - Removing entities/countries with incomplete/missing data
   - Dropping rows with missing continent values
   - Dropping rows with missing per person waste generation values
   - Handling missing values and converting data types
   - Generating additional columns for total waste and total mismanaged waste by country
5. Data visualization:
   - Creating a scatter plot graph to visualize the relationship between GDP per capita and mismanaged waste per person

## Dependencies

- numpy
- pandas
- seaborn
- matplotlib

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/Siddhant0507Shekhar/Global-Plastic-Pollution-Analysis
