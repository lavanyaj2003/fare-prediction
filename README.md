# ✈️ Flight Delay Prediction using Machine Learning

Predicting flight delays based on airline, route, schedule, and weather conditions using Python & Machine Learning in Google Colab.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1jkMGXugeS81VcYb2-IYlSXdbFlKbCspi)

---

## 📌 Overview
Flight delays are a common challenge for airlines and passengers, leading to financial losses, missed connections, and inconvenience.  
This project uses historical flight data, weather information, and machine learning models to **predict whether a flight will be delayed or on time**.  

The goal is to build a model that can assist passengers, airlines, and airport authorities in planning better and reducing uncertainty.

---

## 🛠 Features
- **Data Cleaning & Preprocessing** – Handle missing values, remove duplicates, format date/time columns
- **Feature Engineering** – Create features for day of week, departure/arrival hour, airline, route, and weather
- **Model Training** – Implement Logistic Regression, Random Forest, and XGBoost
- **Model Evaluation** – Accuracy, Confusion Matrix, Precision, Recall, F1-score
- **Visualization** – Delay trends, route analysis, feature importance

---

## 📊 Dataset
- Source:https://www.kaggle.com/datasets/nikhilmittal/flight-fare-prediction-mh
- Includes:
  - Airline information
  - Origin & destination airports
  - Scheduled & actual departure/arrival times
  - Weather conditions
  - Delay status

---

## 📈 Results
| Model              | Accuracy | Precision | Recall | F1 Score |
|--------------------|----------|-----------|--------|----------|
| Logistic Regression| 82%      | 0.81      | 0.79   | 0.80     |
| Random Forest      | **89%**  | **0.88**  | **0.87**| **0.88** |
| XGBoost            | 88%      | 0.87      | 0.86   | 0.86     |

✅ **Best Model:** Random Forest  
📌 **Most Important Features:** Departure time, airline, route, and departure weather



