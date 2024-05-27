# PRODIGY_DS_02

# Titanic Dataset Exploratory Data Analysis (EDA)

## Project Overview

This project focuses on performing data cleaning and exploratory data analysis (EDA) on the Titanic dataset from Kaggle. The goal is to explore the relationships between variables and identify patterns and trends in the data.

## Dataset

The Titanic dataset provides information on the passengers of the Titanic, including whether they survived or not, their age, sex, class, fare, and other attributes. The dataset is divided into two files:
- `train.csv`: Contains the training data with the target variable `Survived`.
- `test.csv`: Contains the test data without the target variable `Survived`.

## Files in the Repository

- `Task_2_EDA.ipynb`: Jupyter notebook containing the EDA code.
- `train.csv`: Training dataset.
- `test.csv`: Test dataset.

## Steps Performed

### 1. Load the Data
The data is loaded into Pandas DataFrames from CSV files.


### 2. Data Cleaning
Handle missing values, convert categorical variables to numerical variables, and drop unnecessary columns.

### 3. Exploratory Data Analysis (EDA)
Explore the data to understand relationships and identify patterns and trends.


### 4. Insights
- **Survival Distribution**: The count plot of survival shows the proportion of passengers who survived and those who did not.
- **Age Distribution**: The histogram of age reveals the age distribution of passengers.
- **Survival Rate by Sex**: The bar plot shows that females had a higher survival rate than males.
- **Survival Rate by Class**: The bar plot indicates that passengers in first class had a higher survival rate compared to those in second and third class.

## Conclusion

This exploratory data analysis provides insights into the factors affecting passenger survival on the Titanic. By visualizing and analyzing these factors, we can better understand the dataset and prepare it for further modeling and predictions.

## Acknowledgements

This project was provided by Prodigy Infotech as part of the second task in the Data Science internship program. The knowledge gained from this project includes data cleaning techniques, exploratory data analysis methods, and visualization skills using Python libraries like Pandas, Matplotlib, and Seaborn.
