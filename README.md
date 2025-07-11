# Sales-Lead-Classification-for-Ficzon-Inc
# Sales-Client-Prediction
# 📈 Sales Client Prediction using Binary Classification Models

This project showcases a Classification-based machine learning approach to predict client sales using various algorithms. It includes data preprocessing, exploratory analysis, model building, and evaluation to determine the best-performing model for accurate sales forecasting.

---

## 📌 Project Overview

- **Dataset**: Sales Lead Classification For Ficzon Inc
- **Task**: Classification — Predicting High Potential(1) or Low Potential(0)
- **Target Variable**: Target (High potential/Low Potential)
- **Model Types**: Binary Classification
---

## 📊 Workflow Summary

1. **Data Loading**
   - Imported dataset using `pandas.read_csv()`
   - Checked data shape, types, and null values

2. **Exploratory Data Analysis (EDA)**
   - Visualized distributions and correlations using `seaborn` and `matplotlib`
   - Identified key features influencing sales

3. **Data Preprocessing**
   - Handled missing values (if any)
   - Removed outliers using statistical methods like IQR or Winsorization
   - Applied encoding for categorical variables

4. **Model Building**
   - Tested multiple regression models:
     - Logistic Regression
     - Decision Tree Regressor
     - Random Forest Regressor
     - KNN
     - XGBoost Regressor

5. **Model Evaluation**
   - Evaluated models using:
     - Accuracy
     - Precision
     - F1 score
     - Recall score
     - Roc-Auc
   - Selected the best-performing model based on metrics

6. **Predictions**
   - Made final predictions on test data
   - Visualized predicted vs actual values

---

## 🔧 Technologies Used

- Python
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📈 Results

- ✅ Best Performing Model: **[Random Forest and XGBoost]**
- 📊 Achieved R² Score: **[0.74 and 0,75]**
- Improved performance with feature selection and ensemble methods

---

