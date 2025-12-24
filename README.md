# Car-Price-Prediction-ML
# 🚗 Car Price Prediction using Machine Learning

This project predicts the price of used cars based on features such as company, year of purchase, kilometers driven, and fuel type using machine learning techniques.

---

## 📌 Problem Statement
Used car prices depend on multiple factors, making it difficult to estimate a fair value.  
This project aims to build a regression model that can predict used car prices accurately.

---

## 📊 Dataset
The dataset contains information about used cars with the following features:
- Company
- Year
- Kms Driven
- Fuel Type
- Price (target variable)

The dataset was cleaned by removing incorrect rows and handling price outliers.

---

## 🧠 Approach
- Data cleaning and preprocessing  
- Removal of invalid entries and outliers (IQR method)  
- Feature selection and encoding  
- Model training and evaluation  

---

## 🤖 Model Performance
- Model Type: Regression  
- Evaluation Metric: R² Score  
- Final R² Score: **0.74**

The model explains 74% of the variance in used car prices.

---

## 🛠️ Tech Stack
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Jupyter Notebook  

---

## 📂 Project Structure
Car-Price-Prediction-ML/
│
├── car_price_prediction.ipynb
├── car_data.csv
└── README.md
