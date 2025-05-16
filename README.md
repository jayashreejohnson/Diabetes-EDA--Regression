# Diabetes Dataset Analysis & Linear Regression Modeling

This project explores a medical dataset to uncover key predictors of diabetes progression and applies linear regression to interpret their relationships with disease outcomes. It emphasizes data preparation, model transparency, and medical relevance in feature analysis.

---

## 🔍 Data Exploration & Cleaning

- Loaded the Stanford Diabetes dataset containing 10 features and a target variable for disease progression.
- Performed EDA with `describe()`, `info()`, and visual distributions to understand variable behavior.
- Cleaned the data by coercing malformed values and filtering rows using `pd.to_numeric()`.

---

## 📊 Regression Modeling & Feature Assessment

- Trained separate linear regression models for each feature to isolate predictive strength.
- Identified **BMI** as the strongest predictor of disease progression (MSE = 3890.46, slope = 10.23).
- Visualized model fit and interpreted coefficients to explain real-world medical significance.

---

## ✅ Outcomes & Applications

- Built a reproducible pipeline for medical data analysis using EDA and regression modeling.
- Established a baseline for multivariate modeling and future clinical ML pipelines.
- Demonstrated the power of simple models in uncovering interpretable health risk factors.

---

## 🛠️ Skills Used

**Languages & Libraries**: Python, Pandas, NumPy, Matplotlib, Seaborn  
**Techniques**: EDA, Data Cleaning, Linear Regression, Model Evaluation (MSE), Visualization

---

## 📁 Dataset

Stanford Diabetes dataset from `sklearn.datasets.load_diabetes()`
