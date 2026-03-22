# 🔥 Forest Fire Risk Prediction using Linear Models

## 📌 Project Overview

This project aims to predict forest fire risk using environmental and meteorological data. The analysis focuses on applying linear and regularized regression models to understand the relationship between key features and fire risk.

The workflow includes data cleaning, exploratory data analysis (EDA), model building, and performance evaluation using both test data and cross-validation.

---

## 🎯 Objectives

* Analyze the relationship between environmental variables and fire risk
* Build and compare multiple regression models
* Evaluate model performance using appropriate metrics
* Validate model robustness using cross-validation
* Provide interpretable and actionable insights

---

## 🧰 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib & Seaborn
* Scikit-learn

---

## 📊 Models Implemented

* Linear Regression
* Ridge Regression
* Lasso Regression
* ElasticNet

---

## 📈 Model Evaluation

Models were evaluated using:

* R² Score
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Cross-Validation

The results show that Linear Regression, Ridge, and Lasso models achieved consistently high performance with R² scores around 0.98.

---

## 🔁 Cross-Validation

Cross-validation was applied to ensure that model performance is consistent across different data splits.

The results confirm that the models generalize well and are not dependent on a single train-test split.

---

## 📉 Model Diagnostics

* **Actual vs Predicted Plot:** Shows strong alignment with the ideal diagonal line
* **Residual Distribution:** Residuals are approximately normally distributed and centered around zero

These results indicate that the model errors are randomly distributed without systematic bias and that linear model assumptions are reasonably satisfied.

---

## 💡 Key Insights

* Environmental variables such as temperature and dryness indicators are strong predictors of fire risk
* Linear relationships dominate the dataset, making simple models highly effective
* Regularization (Ridge/Lasso) provides stability without sacrificing performance

---

## 🧠 Business Impact

The results suggest that fire risk can be effectively predicted using simple, interpretable models.

This enables:

* Faster decision-making
* Early intervention strategies
* Efficient allocation of firefighting resources

Authorities can prioritize high-risk regions based on key indicators such as temperature and dryness levels.

---

## 🚀 Future Improvements

* Hyperparameter tuning for regularized models
* Testing non-linear models
* Feature importance analysis
* Deployment as a predictive tool

---

## 📁 Project Structure

```
forest-fire-risk-prediction/
│
├── Forest_Fire_Risk_Modeling_and_Analysis.ipynb
└── README.md
```

---

## 🤝 Author

This project was developed as part of a data science portfolio to demonstrate skills in data analysis, machine learning, and model evaluation.

---

