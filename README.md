# Telco Customer Churn Prediction

This project predicts customer churn for a telecommunications company using machine learning.

## Files

* `telco.ipynb`: Jupyter Notebook containing the analysis and modeling code.
* `Telco-Customer-Churn.csv`: The dataset used for this project.

## Project Description

This project aims to analyze customer data and predict which customers are most likely to churn (leave the company). Key steps included:

* Data cleaning and preprocessing
* Exploratory data analysis (EDA) to understand customer behavior
* Feature engineering
* Model training and evaluation using various classification algorithms
* Oversampling to handle class imbalance

## Dependencies

* pandas
* numpy
* matplotlib
* seaborn
* plotly
* scikit-learn
* imblearn
* xgboost

## Usage

1.  Clone this repository.
2.  Ensure you have the required libraries installed (you can install them using `pip install -r requirements.txt`).
3.  Open and run `telco.ipynb` in a Jupyter environment.

## Key Findings

* Senior citizens and customers with month-to-month contracts have higher churn rates.
* Customers with fiber optic internet service are more likely to churn than those with DSL.
* Customers with longer contracts tend to be more loyal.
* The Support Vector Machine model achieved the best performance with an accuracy of 96.3%.

## Performance

The best performing model was Support Vector Machine, with the following metrics:

* Accuracy: 0.963
* Precision: 0.961
* Recall: 0.976
* F1 Score: 0.968

## Author

Vanjul Rander
