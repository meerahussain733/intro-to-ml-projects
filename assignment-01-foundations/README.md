# Assignment 01 - Machine Learning Foundations

This folder contains coursework from **CSE 574: Introduction to Machine Learning** completed during my first semester of MS in Computer Science at the University at Buffalo.

The assignment covers core machine learning concepts including:
- data preprocessing and exploratory data analysis
- logistic regression for binary classification
- ordinary least squares (OLS) regression
- ridge regression
- elastic net regression

## Project Components

### 1. Penguin Data Preprocessing and EDA
Performed preprocessing and exploratory analysis on the penguins dataset:
- handled missing values
- standardized categorical values
- detected and removed outliers using IQR
- generated correlation heatmaps, histograms, boxplots, scatter plots, and count plots
- applied feature selection using correlation analysis

**Notebook:** `notebooks/01_penguin_preprocessing_eda.ipynb`

### 2. Logistic Regression from Scratch
Implemented a custom logistic regression model to predict penguin gender using numerical features:
- built sigmoid, cost function, and gradient descent manually
- experimented with multiple learning rates and iteration counts
- tracked loss convergence
- achieved best reported accuracy of **89.85%**

**Notebook:** `notebooks/02_penguin_logistic_regression_from_scratch.ipynb`

### 3. OLS and Ridge Regression on Emissions Data
Implemented regression models to predict total emissions from environmental and economic features:
- train-test split for evaluation
- OLS closed-form solution
- ridge regression with L2 regularization
- compared predictions against actual values using MSE and scatter plots

**Notebook:** `notebooks/03_emissions_ols_ridge_regression.ipynb`

### 4. Elastic Net Regression on Diamond Pricing
Built an elastic net regression pipeline using gradient descent for price prediction:
- feature normalization
- train-test split
- custom elastic net loss
- multiple weight initialization strategies
- analysis of regularization effects and convergence behavior

**Notebook:** `notebooks/04_diamond_elastic_net_regression.ipynb`

## Files
- `data/` - cleaned and preprocessed datasets
- `notebooks/` - implementation notebooks
- `reports/` - assignment report
- `artifacts/` - saved model files

## Skills Demonstrated
Python, NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, Data Preprocessing, EDA, Logistic Regression, OLS, Ridge Regression, Elastic Net, Model Evaluation

## Notes
This project was originally completed as part of academic coursework and has been reorganized for portfolio presentation on GitHub.