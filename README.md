# 🚕 NYC Taxi Fare Prediction

## 📌 Project Overview
Predicting taxi fare amounts in New York City using machine learning.
Built as part of my 2-month ML learning sprint.

## 📊 Dataset
- Source: Kaggle NYC Taxi Fare Prediction Competition
- Original size: 55M rows (5.5 GB)
- Used: 2% sample (~1.1M rows) for training

## 🛠️ What I did
- Downloaded and explored the dataset
- Data cleaning & handling missing values
- Feature engineering from datetime & coordinates
- Built and compared multiple ML models
- Evaluated using RMSE metric

## 📈 Results
| Model | RMSE |
|-------|------|
| Baseline (mean prediction) | 9.8999 |
| Linear Regression | 9.8980 |
| Ridge Regression | 5.2178 |
| Random Forest | 4.1631 |
| XGBoost | 3.9677 |

## 🧰 Tech Stack
Python, Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn, Google Colab

## 📁 Files
- `NYC_Taxi_Fare_Prediction.ipynb` — Main project notebook
