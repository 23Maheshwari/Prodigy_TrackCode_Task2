# Titanic Dataset Analysis

This project performs data cleaning and exploratory data analysis (EDA) on the Titanic dataset. The analysis explores the relationship between various features and the survival rate of passengers.

## Dataset

The Titanic dataset is obtained from [Kaggle](https://www.kaggle.com/c/titanic/data).

## Analysis Steps

1. **Load the dataset**: The dataset is loaded using Pandas.
2. **Data Cleaning**: Missing values are handled, and irrelevant columns are dropped.
3. **Exploratory Data Analysis (EDA)**: Various visualizations are created to explore the relationships between variables and the survival rate.

## Findings

1. **Survival Rate**:
   - The dataset shows that there were more passengers who did not survive than those who survived.

2. **Survival Rate by Gender**:
   - A higher proportion of females survived compared to males.

3. **Survival Rate by Class**:
   - Passengers in the first class had a higher survival rate compared to those in the second and third classes.

4. **Age Distribution by Survival**:
   - The age distribution shows that younger passengers had a higher chance of survival.

5. **Correlation Analysis**:
   - There are significant correlations between some variables and the target variable (Survived). For instance, being in the first class and being female are positively correlated with survival.

## Requirements

- Python 3.x
- Pandas
- NumPy
- Seaborn
- Matplotlib

