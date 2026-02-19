# Titanic Dataset – Exploratory Data Analysis (EDA)
# Project Overview
This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to identify patterns, relationships, and key factors influencing passenger survival.
The analysis includes data cleaning, statistical summaries, and data visualization using Python.
#vDataset
The dataset contains passenger information such as:
PassengerId
Survived (Target Variable: 0 = No, 1 = Yes)
Pclass (Passenger Class)
Name
Sex
Age
SibSp (Siblings/Spouses aboard)
Parch (Parents/Children aboard)
Ticket
Fare
Cabin
Embarked
# Tools & Libraries Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
# Analysis Performed
1️ Data Understanding
 '.info()' to inspect structure and missing values
 '.describe()' for statistical summary
 '.value_counts()' for categorical distribution
2️ Data Cleaning
 Handled missing values using mean for Age column
 Identified missing values in Cabin and Embarked
3️ Visualization
 sns.pairplot() for relationship analysis
 sns.heatmap() for correlation matrix
 Histograms for distribution analysis
 Boxplots for outlier detection
 Scatterplots for relationship trends
 Countplots for survival comparison
# Key Findings
Female passengers had significantly higher survival rates.
1st class passengers were more likely to survive.
Higher fare-paying passengers had better survival probability.
Most passengers were between 20–40 years old.
Fare distribution is right-skewed with several outliers.
Passenger class strongly influenced survival chances.
Age alone does not strongly determine survival.
# Conclusion
Survival on the Titanic was influenced mainly by:
Gender
Passenger class
Fare paid
Socioeconomic status played a major role in survival outcomes.
