# 🚗 Car Price Prediction Analysis

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/scikit__learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)

A comprehensive Machine Learning project focused on building a predictive model to estimate car prices. This project leverages **Linear Regression** coupled with **Recursive Feature Elimination (RFE)** to isolate the most critical automobile features that influence market valuation.

---

## 📌 Project Overview

An automobile company aspires to enter the market by setting up their local manufacturing unit and producing cars. They want to understand the factors on which the pricing of cars depends, specifically:
* Which variables are significant in predicting the price of a car?
* How well do those variables describe the price of a car?

> **Objective:** Use automated and manual feature selection techniques to build a highly interpretable and accurate regression model that helps management understand price dynamics.

---

## 🛠️ Tech Stack & Key Frameworks

* **Core Language:** `Python`
* **Data Manipulation:** `Pandas`, `NumPy`
* **Data Visualization:** `Matplotlib`, `Seaborn`
* **Machine Learning:** `Scikit-Learn` (LinearRegression, RFE, train_test_split, r2_score)
* **Statistical Analysis:** `Statsmodels` (OLS Regression for p-value and VIF analysis)

---

## 📊 End-to-End Methodology

### 1. Exploratory Data Analysis (EDA)
* Visualized numerical and categorical variables using box plots, scatter plots, and pair plots.
* Analyzed multicollinearity using a correlation matrix heatmap.

### 2. Data Preprocessing
* Handled categorical variables by converting them into **dummy variables** (One-Hot Encoding).
* Split the dataset into a 70-30 train-test ratio.
* Rescaled features using **MinMax Scaling** to ensure uniform magnitude across all variables.

### 3. Feature Selection Strategy
* Applied **Recursive Feature Elimination (RFE)** to narrow down the top automated features.
* Refined the model manually by checking the **Variance Inflation Factor (VIF)** to eliminate multicollinearity and evaluating **p-values** to remove statistically insignificant variables ($\text{p-value} > 0.05$).

### 4. Model Evaluation
* Validated assumptions of linear regression by performing **Residual Analysis** (checking error terms for normal distribution and homoscedasticity).
* Evaluated performance on test data using the $R^2$ score metric.

---

## 📁 Repository Structure

| File Name | Description |
| :--- | :--- |
| 📄 `car_price_prediction_linear_regression_rfe.ipynb` | Complete, well-commented Jupyter Notebook containing the full code pipeline. |
| 📊 `CarPrice_Assignment.csv` | Raw dataset containing various technical and structural features of automobiles. |
| 📘 `Data Dictionary - carprices.xlsx` | Metadata file explaining the meaning of each column in the dataset. |

---

## 🚀 How to Run this Project Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/saurabhmungale/Car-Price-Prediction-Linear-Regression.git](https://github.com/saurabhmungale/Car-Price-Prediction-Linear-Regression.git)
