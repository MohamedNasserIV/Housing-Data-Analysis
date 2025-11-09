# House Price Prediction

## Project Overview
This project performs a comprehensive data analysis and regression modeling on a housing dataset. The goal is to explore the data, visualize relationships, and build models to predict house prices using various features. The project includes linear regression, Ridge regression, and polynomial regression.

## Dataset
The dataset contains information about houses, including features like:
- `sqft_living`
- `sqft_above`
- `floors`
- `waterfront`
- And other relevant housing features.

## Project Tasks / Questions
1. Display data types of each column using `.dtypes`.
2. Drop unnecessary columns and obtain statistical summaries with `.describe()`.
3. Count unique values of the `floors` feature using `.value_counts()` and convert to a DataFrame.
4. Create a boxplot to visualize price outliers for houses with and without a waterfront view.
5. Create a scatterplot using `regplot` to analyze the correlation between `sqft_above` and `price`.
6. Fit a linear regression model using `sqft_living` to predict `price` and calculate R².
7. Fit a linear regression model using multiple features to predict `price` and calculate R².
8. Create and fit a pipeline object to predict `price` and calculate R².
9. Fit a Ridge regression model (α=0.1) and calculate R².
10. Perform a second-order polynomial transform and Ridge regression, then calculate R².

## Screenshots
Screenshots of each question’s code and output are included in this repository for submission.

## How to Run
1. Open the Jupyter notebook (`.ipynb`) in Jupyter Lab, VS Code, or any compatible environment.
2. Run the cells sequentially to reproduce the analysis and results.
3. All dependencies: Python 3.x, pandas, numpy, seaborn, scikit-learn, matplotlib.

## Author
- Mohamed Ragab
- Final Project for Data Analysis / Data Science Course
