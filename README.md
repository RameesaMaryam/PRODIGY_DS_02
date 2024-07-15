# Titanic Dataset Analysis

This repository contains the analysis for cleaning and performing exploratory data analysis (EDA) on the Titanic dataset from Kaggle. The primary objective of this project is to explore relationships between different variables and identify patterns and trends in the data.

## Dataset

The dataset used in this project is the Titanic dataset, available from [Kaggle's Titanic Competition page](https://www.kaggle.com/c/titanic/data). Ensure you have downloaded the dataset and placed it in the working directory as `train.csv`.

## Steps Involved

### 1. Loading the Dataset

The first step involves loading the dataset using the Pandas library and displaying the first few rows to understand its structure.

### 2. Handling Missing Values

- Missing values in the `Age` column are filled with the median age.
- Missing values in the `Embarked` column are filled with the mode.
- Unnecessary columns like `PassengerId`, `Name`, `Ticket`, and `Cabin` are dropped to streamline the dataset.

### 3. Data Cleaning

This step ensures that all missing values are handled and irrelevant columns are removed, resulting in a clean dataset ready for analysis.

### 4. Exploratory Data Analysis (EDA)

Several visualizations and analyses are performed to explore the relationships between different variables:

- **Survival Rate by Gender:** A bar plot is used to visualize the survival rate of passengers based on gender.
- **Survival Rate by Passenger Class:** A bar plot shows the survival rate across different passenger classes.
- **Survival Rate by Age Group:** Age groups are created, and their survival rates are visualized using a bar plot.
- **Survival Rate by Embarkation Port:** The survival rates based on the port of embarkation are visualized using a bar plot.

### 5. Correlation Matrix

A heatmap is generated to explore the correlation between different numeric variables in the dataset, helping to identify strong relationships.

## Tools and Libraries Used

- **Python:** The programming language used for analysis.
- **Pandas:** For data manipulation and analysis.
- **NumPy:** For numerical operations.
- **Matplotlib:** For creating static visualizations.
- **Seaborn:** For creating attractive and informative statistical graphics.

## Results and Insights

Through this analysis, various insights into the factors affecting the survival of passengers on the Titanic are uncovered. Visualizations help in understanding the impact of gender, passenger class, age group, and embarkation port on survival rates.

## Usage

To replicate this analysis, follow these steps:

1. Download the Titanic dataset from [Kaggle](https://www.kaggle.com/c/titanic/data).
2. Place the `train.csv` file in your working directory.
3. Run the provided Jupyter notebook or Python script to perform data cleaning and EDA.

## Conclusion

This project demonstrates the process of cleaning and exploring a real-world dataset to uncover meaningful patterns and trends. The findings from the analysis can be used to make informed decisions and predictions regarding similar datasets.
