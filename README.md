# 🌍 Air Quality AQI Prediction using Deep Learning with TensorFlow

## 📌 Overview

This project predicts the **Air Quality Index (AQI)** using environmental and pollution-related data. A Deep Learning model built with **TensorFlow/Keras** learns the relationship between air pollutants, weather conditions, and AQI values to provide accurate predictions.

## 🚀 Features

* Data preprocessing and cleaning
* Feature engineering
* Exploratory Data Analysis (EDA)
* Feature scaling and normalization
* Deep Learning model training
* Model evaluation and prediction

## 📊 Dataset Features

### Pollution Indicators

* CO (Carbon Monoxide)
* NO₂ (Nitrogen Dioxide)
* SO₂ (Sulfur Dioxide)
* O₃ (Ozone)
* PM2.5
* PM10

### Additional Features

* Temperature
* Humidity
* Wind Speed
* Hour, Day, Month
* City (One-Hot Encoded)

### Target

* AQI (Air Quality Index)

## 🛠️ Technologies Used

* Python
* TensorFlow / Keras
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn
* Jupyter Notebook

## 🤖 Model Architecture

```text
Input Layer
    ↓
Dense (256, ReLU)
    ↓
Dropout (0.3)
    ↓
Dense (128, ReLU)
    ↓
Dropout (0.1)
    ↓
Dense (64, ReLU)
    ↓
Dropout (0.1)
    ↓
Dense (32, ReLU)
    ↓
Output Layer
```

## 📈 Training Configuration

* Optimizer: Adam
* Loss Function: Mean Squared Error (MSE)
* Metric: Mean Absolute Error (MAE)
* Epochs: 50
* Batch Size: 32

## 🎯 Future Improvements

* Hyperparameter tuning
* FastAPI deployment
* Streamlit dashboard
* Real-time AQI prediction
* Model comparison with other ML algorithms

## 👨‍💻 Author

Developed using TensorFlow and Python for Air Quality Index prediction and analysis.
