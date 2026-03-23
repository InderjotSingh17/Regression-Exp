# 🏡 House Price Prediction — Complete Machine Learning Journey (Beginner → Advanced)

## 🚀 Overview

This project is a **complete end-to-end Machine Learning journey for regression**, covering concepts from **basic linear models to advanced ensemble techniques like XGBoost**.

The focus is not just on prediction, but on **deep understanding of how models learn, improve, and generalize**.

---

## 🎯 Objectives

* Build a strong foundation in regression
* Understand model behavior (bias, variance, overfitting)
* Learn ensemble techniques (Bagging & Boosting)
* Apply feature engineering and selection
* Perform hyperparameter tuning
* Understand how models actually learn (Gradient Descent)

---

## 📊 Dataset

* **Boston Housing Dataset**
* Target: `medv` (Median House Price)
* Features include:

  * Crime rate, number of rooms, tax rate, etc.

---

# 🔍 Exploratory Data Analysis (EDA)

* Feature distributions (histograms + KDE)
* Correlation heatmap
* Feature vs target relationships
* Outlier and skewness analysis

---

# ⚙️ Data Preprocessing

* Train-Test Split
* One Hot Encoding (OHE)
* Feature Scaling (StandardScaler)

---

# 🧠 Models Implemented

## 🔹 Basic Models

* Linear Regression
* Polynomial Regression

## 🔹 Regularization

* Ridge Regression
* Lasso Regression

## 🔹 Tree-Based Models

* Decision Tree Regressor

---

# 🌲 Ensemble Learning

## 🔹 Bagging

* Concept: Reduce variance using multiple models
* Implementation: **Random Forest Regressor**

## 🔹 Boosting

* AdaBoost Regressor
* Gradient Boosting Regressor
* XGBoost Regressor

---

# 📈 Model Evaluation

* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score
* Residual Analysis
* Train vs Test comparison (Overfitting detection)

---

# 🔥 Advanced Techniques

## 🔹 Feature Engineering

* Polynomial features
* Manual feature creation

## 🔹 Feature Selection

* Lasso-based selection
* Feature importance using Random Forest

## 🔹 Cross Validation

* K-Fold Cross Validation for robust evaluation

## 🔹 Hyperparameter Tuning

* GridSearchCV for optimal model performance

## 🔹 Pipeline

* Combined preprocessing + model into a single workflow

---

# ⚙️ Core ML Concept

## 🔹 Gradient Descent (From Scratch)

* Implemented manually
* Visualized learning process
* Understood weight updates and loss minimization

---

# 📊 Results Summary

| Model                   | Performance                          |
| ----------------------- | ------------------------------------ |
| Linear Regression       | Baseline                             |
| Polynomial Regression   | Improved performance                 |
| Ridge Regression        | Reduced overfitting                  |
| Lasso Regression        | Feature reduction (performance drop) |
| Decision Tree           | Overfitting observed                 |
| Random Forest (Bagging) | Strong and stable                    |
| AdaBoost                | Moderate performance                 |
| Gradient Boosting       | 🚀 Best performance                  |
| XGBoost                 | Competitive (needs tuning)           |

---

# 🏆 Final Model

👉 **Gradient Boosting Regressor**

### Why?

* Lowest error
* Highest R² score
* Learns from residual errors
* Best balance between bias and variance

---

# 💡 Key Learnings

* No single model is always best
* Overfitting must be detected using train-test gap
* Bagging reduces variance, boosting reduces bias
* Feature importance ≠ true usefulness always
* Cross-validation gives realistic performance
* Gradient Descent is the core learning mechanism of ML
* XGBoost requires tuning and works best on large datasets

---

# 🛠️ Tech Stack

* Python 🐍
* NumPy
* Pandas
* Matplotlib & Seaborn
* Scikit-learn
* XGBoost

---

# 📁 Project Structure

```
├── notebook.ipynb
├── README.md
```

---

# 🚀 How to Run

```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost
```

```bash
jupyter notebook
```

---

# 🔮 Future Improvements

* Try LightGBM / CatBoost
* Deploy model using Flask/Django
* Add SHAP for model explainability
* Use larger real-world datasets

---

# 👨‍💻 Author

**Inderjot Singh**

---

# ⭐ If you like this project

Give it a ⭐ on GitHub and share your feedback!

