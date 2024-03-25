# Support Vector Regression (SVR)

This repository contains code for implementing Support Vector Regression (SVR) on a dataset of position levels and corresponding salaries. The code is written in Python and uses the scikit-learn library.

## Code Explanation

The code performs the following steps:

1. Imports the required libraries: numpy, matplotlib, and pandas.
2. Reads the dataset from a CSV file named `Position_Salaries.csv`.
3. Separates the independent variable (position level) and the dependent variable (salary) from the dataset.
4. Reshapes the dependent variable (salary) into a column vector.
5. Performs feature scaling on both the independent and dependent variables using the StandardScaler from scikit-learn.
6. Trains an SVR model on the entire dataset using the Radial Basis Function (RBF) kernel.
7. Demonstrates how to predict a new salary using the trained SVR model for a position level of 6.5.
8. Visualizes the SVR results using a scatter plot for the actual data points and a line plot for the predicted values.
9. Generates a higher resolution and smoother curve for the SVR model by creating a grid of position levels.

## Dataset

The dataset used in this code is included in the repository and named `Position_Salaries.csv`. It contains the following columns:

| Position | Level | Salary |
| -------- | ----- | ------ |
| Business Analyst | 1 | 45000 |
| Junior Consultant | 2 | 50000 |
| Senior Consultant | 3 | 60000 |
| Manager | 4 | 80000 |
| Country Manager | 5 | 110000 |
| Region Manager | 6 | 150000 |
| Partner | 7 | 200000 |
| Senior Partner | 8 | 300000 |
| C-level | 9 | 500000 |
| CEO | 10 | 1000000 |

The `Level` column represents the level of the position, and the `Salary` column represents the corresponding salary for that position level.

## Usage

To run the code, you need to have Python and the required libraries installed. You can install the necessary libraries using pip:
After installing the required libraries, you can run the code by executing the Python script.

## Contributing

Contributions to this repository are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
