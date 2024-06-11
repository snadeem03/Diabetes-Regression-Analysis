# Diabetes-Regression-Analysis


## Overview 
 This project aims to analyze the progression of diabetes in patients using Linear Regression. The dataset used in this analysis contains information about diabetes patients, including demographic and clinical features, as well as a quantitative measure of disease progression one year after baseline measurements.

## Dataset
 The dataset used in this analysis is the diabetes dataset available in scikit-learn. It contains 442 samples with 10 features and one target variable representing disease progression.

## Methodolgy
 * Data Loading :The dataset is loaded using the load_diabetes() function from scikit-learn.

 * Model selection : Initially, linear regression is chosen as the baseline model for predicting disease progression.

 * Model Evaluation : The performance of the linear regression model is evaluated using mean squared error (MSE) as the primary metric.

 

## Results 
 * The initial linear regression model yielded a high mean squared error (MSE) of 3350, indicating poor predictive performance.

 * Further analysis is needed to identify the factors contributing to the high MSE and to determine the most effective strategies for improving model accuracy.


## Future Work
 * Experiment with alternative regression algorithms such as Ridge regression, Lasso regression, or ensemble methods like Random Forest and Gradient Boosting.

 * Explore additional datasets or collect more data to supplement the existing dataset and improve model generalization.


## How to run the code 
 * Clone this repository to your local machine.
 * Explore the Jupyter Notebook diabetes_regression_analysis.ipynb for a step-by-step walkthrough of the analysis.


