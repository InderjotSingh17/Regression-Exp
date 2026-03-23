# 🏡 House Price Prediction (Complete Machine Learning Pipeline)

## 🚀 Overview

This project implements a **complete end-to-end Machine Learning pipeline** for predicting house prices using regression techniques.
It covers everything from **data analysis and preprocessing to model building, evaluation, and optimization**.

The goal of this project is not just prediction, but **deep understanding of how ML models work in real-world scenarios**.

---

## 🎯 Objectives

* Understand regression problems deeply
* Build multiple ML models and compare them
* Detect and handle overfitting
* Apply feature engineering and feature selection
* Perform hyperparameter tuning
* Use cross-validation for reliable evaluation
* Build clean and reusable ML pipelines

---

## 📊 Dataset

* Dataset used: **Boston Housing Dataset**
* Features include:

  * Crime rate, number of rooms, tax rate, etc.
* Target variable:

  * `medv` → Median house price

---

## 🔍 Exploratory Data Analysis (EDA)

* Feature distribution visualization
* Correlation heatmap
* Feature vs target relationships
* Outlier and skewness understanding

---

## ⚙️ Data Preprocessing

* Train-Test Split
* One Hot Encoding (OHE)
* Feature Scaling (StandardScaler)

---

## 🧠 Models Implemented

### 🔹 Basic Models

* Linear Regression
* Polynomial Regression

### 🔹 Regularization

* Ridge Regression
* Lasso Regression

### 🔹 Tree-Based Models

* Decision Tree Regressor
* Random Forest Regressor

---

## 📈 Model Evaluation

* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score
* Residual Analysis
* Train vs Test Comparison (Overfitting detection)

---

## 🔥 Advanced Techniques

### 🔹 Feature Engineering

* Polynomial feature generation

### 🔹 Feature Selection

* Lasso-based selection
* Feature importance (Random Forest)

### 🔹 Cross Validation

* K-Fold Cross Validation for robust evaluation

### 🔹 Hyperparameter Tuning

* GridSearchCV for optimal model parameters

### 🔹 Pipeline

* Combined preprocessing + model into a single workflow

---

## 📊 Results Summary

| Model                 | Performance                          |
| --------------------- | ------------------------------------ |
| Linear Regression     | Baseline                             |
| Polynomial Regression | Improved accuracy                    |
| Ridge Regression      | Reduced overfitting                  |
| Lasso Regression      | Feature reduction (performance drop) |
| Decision Tree         | Overfitting observed                 |
| Random Forest         | ✅ Best performance                   |

---

## 🏆 Final Model

👉 **Random Forest Regressor**

### Why?

* Lowest error
* Best generalization
* Handles non-linearity well
* Reduces overfitting

---

## 💡 Key Learnings

* More complex models can lead to overfitting
* Feature importance ≠ feature usefulness always
* Cross-validation gives realistic performance
* Regularization helps control model complexity
* Random Forest provides a balance between bias and variance

---

## 🛠️ Tech Stack

* Python 🐍
* NumPy
* Pandas
* Matplotlib & Seaborn
* Scikit-learn

---

## 📁 Project Structure

```
├── notebook.ipynb
├── README.md
```

---

## 🚀 How to Run

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

```bash
jupyter notebook
```

---

## 🎯 Future Improvements

* Try XGBoost / LightGBM
* Deploy model using Flask/Django
* Use larger real-world datasets
* Add model explainability (SHAP)

---

## 👨‍💻 Author

**Inderjot Singh**

---

## ⭐ If you like this project

Give it a ⭐ on GitHub and share your feedback!
