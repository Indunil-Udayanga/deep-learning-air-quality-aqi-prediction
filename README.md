###🌍 Air Quality AQI Prediction using Deep Learning with TensorFlow

## 📌 Project Overview

This project predicts the **Air Quality Index (AQI)** using environmental and pollution-related data. A Deep Learning model built with **TensorFlow/Keras** is trained to learn the relationship between air pollutants, weather conditions, and AQI values.

The project includes:

* Data preprocessing
* Feature engineering
* Exploratory Data Analysis (EDA)
* Data scaling and normalization
* Deep Learning model training
* Model evaluation
* AQI prediction for new inputs

---

## 📊 Dataset Features

The model uses the following features:

### Pollution Indicators

* CO (Carbon Monoxide)
* NO₂ (Nitrogen Dioxide)
* SO₂ (Sulfur Dioxide)
* O₃ (Ozone)
* PM2.5
* PM10

### Weather Features

* Temperature
* Humidity
* Wind Speed

### Time Features

* Hour
* Day
* Month

### Location Features

* City (One-Hot Encoded)

### Target Variable

* AQI (Air Quality Index)

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* TensorFlow / Keras
* Jupyter Notebook

---

## 📈 Data Preprocessing

The following preprocessing steps were performed:

1. Converted Date column into datetime format.
2. Extracted:

   * Hour
   * Day
   * Month
3. Removed unnecessary columns.
4. Applied One-Hot Encoding to city names.
5. Checked missing values.
6. Performed outlier analysis.
7. Standardized features using StandardScaler.

---

## 🔍 Exploratory Data Analysis

The project includes:

* Correlation Heatmap
* Pair Plots
* Boxplots for Outlier Detection
* Statistical Summary Analysis

---

## 🤖 Deep Learning Model

Model Architecture:

Input Layer → 256 Neurons (ReLU)
↓
Dropout (0.3)
↓
128 Neurons (ReLU)
↓
Dropout (0.1)
↓
64 Neurons (ReLU)
↓
Dropout (0.1)
↓
32 Neurons (ReLU)
↓
Output Layer (AQI Prediction)

### Compilation

* Optimizer: Adam
* Loss Function: Mean Squared Error (MSE)
* Metric: Mean Absolute Error (MAE)

---

## 🚀 Training

* Epochs: 50
* Batch Size: 32
* Validation Split: 20%

---

## 📊 Model Evaluation

The model is evaluated using:

* Mean Squared Error (MSE)
* Mean Absolute Error (MAE)
* Prediction vs Actual AQI Comparison

---

## 🔮 AQI Prediction

The trained model can predict AQI values for:

* New environmental measurements
* Different cities
* Custom user inputs

Example:

```python
pred_real = scaler_y.inverse_transform(pred_scaled)
print(pred_real)
```
## 🎯 Future Improvements

* Hyperparameter tuning
* Model deployment with FastAPI
* Streamlit web application
* Real-time AQI prediction
* Model comparison with XGBoost and Random Forest

---

## 👨‍💻 Author

Developed as a Deep Learning project for Air Quality Index prediction using TensorFlow and Python.
