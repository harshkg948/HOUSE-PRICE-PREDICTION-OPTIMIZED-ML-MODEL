# HOUSE-PRICE-PREDICTION-OPTIMIZED-ML-MODEL
House Price Prediction project improving R² from 0.37 to 0.96 using data cleaning, feature engineering, Linear Regression, and Random Forest Regressor.
# 🏠 House Price Prediction - Model Optimization Project

## 📌 Overview

This project focuses on improving a House Price Prediction model through systematic preprocessing, feature engineering, and model experimentation.

The project started with a baseline model scoring **R² = 0.37**. After optimizing the dataset and tuning a **Linear Regression** pipeline, performance improved to **R² = 0.57**. Using the same cleaned dataset and optimized features, a **Random Forest Regressor** was then trained, achieving a final **R² = 0.96**.

This project demonstrates the importance of both **data quality** and **model selection** in Machine Learning.

---

## 📊 Results

| Model                         | R² Score |
| ----------------------------- | -------- |
| Baseline Model                | 0.37     |
| Linear Regression (Optimized) | 0.57     |
| Random Forest Regressor       | 0.96     |

---

## 🎯 Objective

To improve prediction accuracy by building a strong end-to-end ML pipeline:

* ✅ Data Cleaning
* ✅ Missing Value Handling
* ✅ Outlier Treatment
* ✅ Feature Engineering
* ✅ Feature Scaling
* ✅ Model Tuning
* ✅ Model Comparison

---

## ⚙️ Workflow

### 🧹 1. Data Preprocessing

* Removed duplicates
* Handled missing values
* Treated inconsistent records

### 📉 2. Outlier Detection

* Identified extreme values impacting model learning

### 🏗️ 3. Feature Engineering

* Created derived features to improve predictive power

### 📏 4. Feature Scaling

* Applied StandardScaler for Linear Regression

### 🤖 5. Model Training

#### 📘 Linear Regression

* Tuned preprocessing pipeline
* Achieved **R² = 0.57**

#### 🌳 Random Forest Regressor

* Trained on same optimized dataset
* Captured non-linear relationships
* Achieved **R² = 0.96**

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

## 📐 Evaluation Metric

Used **R² Score** to evaluate model performance.

```python id="pk81zs"
from sklearn.metrics import r2_score
```

---

## 💡 Key Learnings

* Clean data significantly improves performance
* Linear Regression is useful as a strong baseline
* Random Forest captures complex non-linear patterns
* Good preprocessing + right model = strong results

---

## 🚀 Future Improvements

* Hyperparameter Tuning with GridSearchCV
* XGBoost / LightGBM Comparison
* Cross Validation
* Model Deployment with Streamlit

---

## 📂 Project Structure

```bash id="r49ma2"
House-Price-Prediction/
│── data/
│── notebooks/
│── models/
│── src/
│── README.md
│── requirements.txt
```

---

## 👨‍💻 Author
HARSH KUMAR GUPTA

Built as a hands-on Machine Learning project focused on practical model optimization and experimentation.
