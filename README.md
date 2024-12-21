# Turbine Data Analysis and Modeling

This repository contains a Jupyter Notebook for analyzing and modeling turbine data using machine learning techniques. The workflow focuses on data preprocessing, exploratory data analysis, and predictive modeling with the XGBoost regressor.

## Features

- **Data Preparation**: Loading the turbine dataset, handling missing values, and scaling numerical features.
- **Exploratory Data Analysis (EDA)**: Statistical summaries and visualizations.
- **Machine Learning Model**: Predictive modeling using XGBoost.
- **Evaluation Metrics**: R² score, mean absolute error (MAE), and mean squared error (MSE).

## Requirements

The following Python libraries are required to run the notebook:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `xgboost`
- `scipy`

Install the required libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost scipy
```

## Dataset

The analysis uses a CSV file named `Turbine_Data.csv`. Ensure this file is available in the same directory as the notebook before running it.

## Workflow

1. **Data Loading**: Import the dataset and check for missing values.
2. **Data Cleaning**: Drop rows with missing values.
3. **Feature Selection**: Separate numeric and non-numeric columns.
4. **Train-Test Split**: Split the data into training and testing sets.
5. **Scaling**: Standardize numerical features.
6. **Modeling**: Train an XGBoost regressor and evaluate its performance using R², MAE, and MSE.
7. **Visualization**: Generate plots for data analysis and residual checks.

## Results

The notebook outputs key metrics and visualizations, including:

- Statistical summaries.
- Correlation heatmaps.
- Probability plots.
- Model performance metrics.



