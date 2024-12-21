# Turbine-Data-Analysis-and-Modeling

This repository contains a Jupyter Notebook for analyzing and modeling turbine data using machine learning techniques. The workflow focuses on data preprocessing, exploratory data analysis, and predictive modeling with the XGBoost regressor.

FEATURES 

Data Preparation: Loading the turbine dataset, handling missing values, and scaling numerical features.
Exploratory Data Analysis (EDA): Statistical summaries and visualizations.
Machine Learning Model: Predictive modeling using XGBoost.
Evaluation Metrics: R² score, mean absolute error (MAE), and mean squared error (MSE).


The following Python libraries are required to run the notebook:

pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
scipy

Install the required libraries using pip:
pip install pandas numpy matplotlib seaborn scikit-learn xgboost scipy

DATASET-
The analysis uses a CSV file named Turbine_Data.csv. Ensure this file is available in the same directory as the notebook before running it.

WORKFLOW--
Data Loading: Import the dataset and check for missing values.
Data Cleaning: Drop rows with missing values.
Feature Selection: Separate numeric and non-numeric columns.
Train-Test Split: Split the data into training and testing sets.
Scaling: Standardize numerical features.
Modeling: Train an XGBoost regressor and evaluate its performance using R², MAE, and MSE.
Visualization: Generate plots for data analysis and residual checks.

RESULTS-
The notebook outputs key metrics and visualizations, including:
Statistical summaries.
Correlation heatmaps.
Probability plots.
Model performance metrics.
