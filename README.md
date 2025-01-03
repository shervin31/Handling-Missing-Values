# Titanic Dataset - Handling Missing Values

## Project Overview

This project focuses on identifying and handling missing values in the Titanic dataset. The goal is to clean the dataset to ensure accurate and unbiased data analysis by using different imputation techniques. The techniques used in this project include Mean Imputation, Median Imputation, and Mode Imputation. The project also includes data visualizations to guide the selection of the most suitable imputation method.

## Technologies Used

- Python
- Pandas
- Seaborn
- Jupyter Notebook

## Key Steps

1. **Data Loading**  
   Loaded the Titanic dataset using Seaborn and explored the first few entries to understand its structure.

2. **Missing Value Identification**  
   Utilized pandas methods to identify missing values across the dataset and quantified them using `.isnull().sum()`.

3. **Imputation Techniques**  
   - **Mean Imputation**: Used when the data is normally distributed (e.g., 'age' column).
   - **Median Imputation**: Applied for columns with outliers, ensuring a more accurate replacement for missing data.
   - **Mode Imputation**: Employed for categorical data (e.g., 'embarked' column) by filling missing values with the most frequent category.

4. **Data Visualization**  
   Visualized data distributions using Seaborn histograms to assess how to best handle missing values based on the data's characteristics.

5. **Handling Missing Data**  
   - Deletion of rows or columns with excessive missing values.
   - Imputation to fill missing data based on calculated strategies (mean, median, mode).


