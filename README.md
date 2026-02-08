Project Description
This project predicts house prices in Boston using the Boston Housing Dataset.
The goal is to understand how different factors like number of rooms, crime rate, and population status affect house prices.

Dataset Information
The dataset contains several features, such as:
CRIM: Crime rate
RM: Average number of rooms
LSTAT: Percentage of lower-status population
DIS: Distance to work centers
TAX: Property tax rate

Target
MEDV: Median house price (in $1000s)

Tools Used
Python
Pandas & NumPy
Matplotlib & Seaborn
Scikit-Learn

Data Analysis

Checked for missing values
Visualized correlations between features

Found that:
RM increases house price
LSTAT decreases house price

Models Used

Linear Regression

Polynomial Regression (Degree = 2)

Results

Polynomial Regression performed better than Linear Regression

It achieved lower error and higher accuracy

Conclusion
House prices do not always follow a straight-line pattern.
Using Polynomial Regression helped the model learn better from the data.
Feature scaling improved model performance.
