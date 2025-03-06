# 🏡 California Housing Price Prediction

## 📌 Project Description

This project focuses on predicting house prices using the **California Housing Prices dataset**.
The goal is to build a machine learning model that accurately predicts the **median house value**

### 🔹 **Project Steps**

- **Data Exploration and Cleaning**
- **Handling Missing Values**
- **Scaling using MinMaxScaler**
- **Encoding Categorical Variables**
- **Model Selection (Ridge, Lasso, LinearRegression, KNeighborsRegressor etc.)**
- **Hyperparameter Tuning using GridSearchCV**
- **Model Evaluation using MSE, RMSE, R² Score**

---

## 📌 Technologies & Libraries Used

- **Python**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Scikit-learn**
- **XGBoost, LightGBM**

---

## 📌 About the Dataset

- **Source:** Kaggle - [California Housing Prices Dataset](https://www.kaggle.com/datasets/camnugent/california-housing-prices)
- **Features:**
  - `longitude` & `latitude` → **Geographical location**
  - `housing_median_age` → **Median age of houses**
  - `total_rooms`, `total_bedrooms` → **Number of rooms & bedrooms**
  - `population`, `households` → **Population & number of households**
  - `median_income` → **Median income of households in the block**
  - `ocean_proximity` → **Categorical feature describing the house’s distance from the ocean**
- **Target Variable:** `median_house_value` (House price in USD)

---

## 📌 Models Used

Several machine learning models were tested and compared:

- **Linear Regression**
- **Ridge Regression**
- **Lasso Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**
- **Gradient Boosting Machines (XGBoost)**
- **Support Vector Regression (SVR)**
- **Neural Network (MLP Regressor)**

---

## 📌 Evaluation Metrics

- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
- **R² Score (Coefficient of Determination)**

---

## 📌 Results & Findings

- **Best performing model:** 🚀 **Random Forest Regressor** achieved the lowest RMSE.

---

## 🚀 How to Run the Project

### **1️⃣ Install Required Libraries**

```bash
pip install numpy pandas seaborn matplotlib scikit-learn xgboost lightgbm
```
