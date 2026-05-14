# Linear Regression Analysis Project

This project is a complete practical study of Linear Regression using the Advertising dataset.

Instead of only training models and checking accuracy, this project focuses on understanding:
- how Linear Regression works
- why models fail
- how assumptions affect performance
- how residuals help diagnose problems
- and how different techniques improve the model

The project covers important regression concepts like:
- Residual Analysis
- Gradient Descent
- Multicollinearity
- Polynomial Regression
- Overfitting
- Heteroscedasticity
- Log Transformation

---

# Dataset

The project uses the famous Advertising dataset containing advertising spending across different platforms:

- TV
- Radio
- Newspaper

Target Variable:
- Sales

---

# Project Structure

```text
Linear-Regression-Analysis/
│
├── dataset/
│   └── Advertising.csv
│
├── notebooks/
│   ├── 01_understanding_dataset.ipynb
│   ├── 02_baseline_linear_regression.ipynb
│   ├── 03_ols_vs_gradient_descent.ipynb
│   ├── 04_multicollinearity.ipynb
│   ├── 05_polynomial_regression.ipynb
│   └── 06_heteroscedasticity.ipynb
│
├── images/
│   ├── residual_plots/
│   ├── heatmaps/
│   └── model_visualizations/
│
├── requirements.txt
└── README.md
```


# Notebooks Overview

| Notebook | Description |
|---|---|
| [01_understanding_dataset.ipynb](01_understanding_dataset.ipynb) | Dataset understanding and EDA |
| [02_baseline_linear_regression.ipynb](02_baseline_linear_regression.ipynb) | Baseline Linear Regression |
| [03_ols_vs_gradient_descent.ipynb](03_ols_vs_gradient_descent.ipynb) | OLS vs Gradient Descent |
| [04_multicollinearity.ipynb](04_multicollinearity.ipynb) | Multicollinearity Analysis |
| [05_polynomial_regression.ipynb](05_polynomial_regression.ipynb) | Polynomial Regression |
| [06_heteroscedasticity.ipynb](06_heteroscedasticity.ipynb) | Heteroscedasticity and Log Transformation |

---
# Important Visualizations

## Baseline Linear Regression Residual Plot

This residual plot from the baseline Linear Regression model shows visible patterns in the residuals, suggesting that the model was not able to fully capture all relationships present in the dataset.

![Baseline Residual Plot](images/baseline/residual%20plot.png)

---

## Residual Plot After Polynomial Regression

After applying Polynomial Regression, the residuals became more randomly scattered around zero, indicating that the model captured non-linear relationships more effectively.

![Polynomial Residual Plot](images/non-linearity/polynomial%20regression%20residual%20plot.png)

---

## Heteroscedasticity Funnel Pattern

This residual plot demonstrates heteroscedasticity, where the spread of residuals increases as predicted values increase, forming a funnel-shaped pattern.

![Heteroscedasticity Funnel Plot](images/heteroscedasticity/Residual%20Plot%20%28Heteroscedasticity%29.png)
---

# What This Project Covers

## 1. Understanding the Dataset
- Dataset exploration
- Statistical summary
- Correlation analysis
- Feature relationships
- Data visualization

---

## 2. Baseline Linear Regression
- Building a Linear Regression model
- R² Score and RMSE
- Actual vs Predicted analysis
- Residual analysis
- Model interpretation using Statsmodels

---

## 3. OLS vs Gradient Descent
- Closed-form OLS solution
- Custom Gradient Descent implementation
- Loss optimization
- Learning rate behavior
- Importance of feature scaling

---

## 4. Multicollinearity
- Correlation heatmaps
- Variance Inflation Factor (VIF)
- Coefficient instability
- Sensitivity of correlated features
- Impact on model interpretation

---

## 5. Polynomial Regression
- Detecting non-linearity
- Polynomial feature engineering
- Residual improvement
- Underfitting vs Overfitting
- Train vs Test performance comparison

---

## 6. Heteroscedasticity
- Residual variance analysis
- Funnel-shaped residual patterns
- Breusch-Pagan Test
- Log transformation
- Variance stabilization

---

# Key Learnings

Some important learnings from this project:

- High R² does not always mean a perfect model
- Residual plots are extremely important in regression analysis
- Multicollinearity mainly affects coefficient interpretation
- Polynomial Regression can capture hidden non-linear patterns
- Increasing model complexity too much can cause overfitting
- Heteroscedasticity violates the constant variance assumption
- Log transformation can help stabilize residual variance

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels

---

# Visualizations Included

The project contains several analytical visualizations such as:

- Residual Plots
- Correlation Heatmaps
- Actual vs Predicted Plots
- Polynomial Regression Curves
- Coefficient Stability Analysis
- Funnel-shaped Residual Patterns

---

# How to Run

## Clone Repository

```bash
git clone <your-repo-link>
```

## Install dependencies
```bash
pip install -r requirements.txt
```

---
# Why This Project is Different

Most beginner Machine Learning projects focus only on training models and increasing accuracy scores.

This project focuses more on understanding:

- how Linear Regression works
- why models fail
- how residuals help diagnose problems
- how assumptions affect model behavior
- and how different techniques improve the model

The project follows a complete analytical workflow instead of only comparing accuracy scores.

---

# About Me

Hi, I'm Somil Dogra, a B.Tech CSE (Data Science) student interested in Data Analysis, Machine Learning, and regression modeling.

This project was built as part of my learning journey to deeply understand Linear Regression, residual analysis, and common regression challenges.

---