# Ecommerce Customer Analysis (Linear Regression)

## Overview
This project applies **Linear Regression** to analyze customer behavior and predict yearly spending based on various features.

The workflow follows a similar structure to a housing price prediction model and demonstrates how machine learning models can be adapted across datasets.

---

## Dataset
The dataset contains 500 customer records with features such as:
- Avg. Session Length
- Time on App
- Time on Website
- Length of Membership
- Yearly Amount Spent (target variable)

---

## Steps Performed
- Data loading and exploration
- Data cleaning (removed text-based columns)
- Exploratory Data Analysis (pairplot, correlation heatmap)
- Feature selection
- Train-test split
- Model training using Linear Regression
- Model evaluation

---

## Model Results

- MAE: 7.74
- MSE: 93.83
- RMSE: 9.69

---

## Key Insights

- **Length of Membership** has the strongest impact on spending
- **Time on App** is significantly more important than Time on Website
- Time on Website has minimal effect

 This suggests the company should focus more on improving the mobile app experience.

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Author
Fatimah Al-Maqhawi
