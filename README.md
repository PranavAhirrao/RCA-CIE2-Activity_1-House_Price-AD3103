# Activity 1: Multiple Linear Regression

## 1. Introduction
This project is part of CIE 2 for the subject **Regression and Classification Algorithms**. The aim is to understand and implement Multiple Linear Regression to predict house prices using different property features.

## 2. Objective
- Understand Multiple Linear Regression.
- Study the relationship between input features and house prices.
- Perform manual regression calculations.
- Train and compare Single Linear Regression and Multiple Linear Regression models.
- Evaluate model performance using regression metrics.

## 3. Dataset Information
**Dataset Name:** Housing Prices Dataset

**Dataset Source:** Kaggle

**Dataset Link:** https://www.kaggle.com/datasets/yasserh/housing-prices-dataset/data

- Number of Rows: 545
- Number of Columns: 13
- Target Variable: `price`
- Input Features: area, bedrooms, bathrooms, stories, mainroad, guestroom, basement, hotwaterheating, airconditioning, parking, prefarea and furnishingstatus.

## 4. Tools and Technologies
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 5. Work Completed
The following tasks were performed:

1. Loaded and inspected the dataset.
2. Checked missing values and duplicate records.
3. Performed data cleaning and preprocessing.
4. Created scatter plots and a correlation heatmap.
5. Performed manual Multiple Linear Regression calculations.
6. Split the dataset into 80% training and 20% testing data.
7. Built Single Linear Regression and Multiple Linear Regression models.
8. Compared actual and predicted values.
9. Evaluated models using MAE, MSE, RMSE, R² and Adjusted R².
10. Performed residual analysis and multicollinearity checks using VIF.
11. Predicted the price of a new house.
12. Recorded the conclusion, limitations and decision log.

## 6. Model Results

| Evaluation Metric | Single Linear Regression | Multiple Linear Regression |
|---|---:|---:|
| R² Score | 0.273 | 0.653 |
| Adjusted R² | 0.266 | 0.605 |
| MAE | 1,474,748 | 970,043.40 |
| RMSE | 1,917,104 | 1,324,506.96 |

The Multiple Linear Regression model performed better than the Single Linear Regression model on the test dataset.

## 7. Conclusion
Multiple Linear Regression provided better house-price predictions by considering multiple property features instead of only area. The model achieved an R² score of 0.653, showing that it explains approximately 65.3% of the variation in test-set house prices.

The model is useful for learning regression techniques, but its predictions are estimates and should be used with caution.

## 8. Repository Contents
- `Activity1_Multiple_Linear_Regression_Final_Updated.ipynb` – Completed Jupyter Notebook.
- `Housing.csv` – Dataset used for the activity.
- `README.md` – Project description and results.

## 9. GitHub Reference
**Submission GitHub ID:** https://github.com/complexiota

---

**Subject:** Regression and Classification Algorithms  
**Activity:** Activity 1 – Multiple Linear Regression  
**Academic Year:** 2026–27
