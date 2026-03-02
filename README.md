# aqi-prediction-python

# 🌫️ Air Quality Index (AQI) Prediction using Machine Learning  
A complete project to predict the Air Quality Index (AQI) using pollutant-specific values and Machine Learning.  
Includes a fully documented **Google Colab Notebook** and an **APK (Android App)** for practical use.

---

## 📌 Project Summary

This project demonstrates how Machine Learning can be used to forecast the **Air Quality Index (AQI)** based on pollutant concentration values such as CO, Ozone, NO2, and PM2.5.  
It includes:

- ✔ A complete **Google Colab notebook**  
- ✔ A trained **AQI Prediction Model** (Random Forest)  
- ✔ An **Android APK** that predicts AQI (optional)  
- ✔ Clean data preprocessing  
- ✔ Visualization dashboards  
- ✔ Evaluation metrics and interpretation  

---

## 📁 Files in This Repository

| File | Description |
|------|-------------|
| `AQI_Prediction.ipynb` | Complete Google Colab Notebook for training & visualization |
| `AQI-and-Lat-Long-of-Countries.csv` | Dataset used for training the model |
| `aqi_random_forest_model.pkl` | Trained AQI prediction model |
| `app.apk`| Android application for AQI prediction |
| `README.md` | Documentation file |
| `requirements.txt` | Libraries needed to run the project |
| `src/aqi_model.py` | Python script version of the model |

---

## 🚀 Features

- Predicts **AQI Value** using multiple pollutant indicators  
- Uses **Random Forest Regression** for high accuracy  
- Supports **real-time prediction** in Android App (APK included)  
- Provides:
  - Correlation heatmaps  
  - Distribution analysis  
  - Actual vs Predicted plots  
- Maps AQI to **health categories** (e.g., Good, Moderate, Unhealthy)  
- Fully documented and easy to understand  

---

## 🔬 Machine Learning Workflow

### **1. Data Loading**
Dataset is loaded from CSV and inspected:

```python
data = pd.read_csv('AQI-and-Lat-Long-of-Countries.csv')

