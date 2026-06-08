# Air Quality Prediction using Deep Learning

This project predicts Air Quality Index (AQI) using Artificial Neural Networks (ANN) implemented in both TensorFlow and PyTorch.

## Project Overview

The objective of this project is to analyze air quality data and build deep learning models capable of predicting AQI values based on environmental and pollutant measurements.

## Dataset Features

* AQI (Target Variable)
* CO
* PM2.5
* PM10
* NO2
* Date-based features (Hour, Day, Month)
* City (One-Hot Encoded)

## Project Structure

```text
air-quality-prediction/
│
├── tensorflow/
│   ├── air_quality_analysis.ipynb
│   └── README.md
│
├── pytorch/
│   ├── air_quality_analyse_pytorch.ipynb
│   └── README.md
│
└── README.md
```

## Implementations

### TensorFlow ANN

Implementation of an Artificial Neural Network using TensorFlow/Keras.

### PyTorch ANN

Implementation of an Artificial Neural Network using PyTorch.

## Data Preprocessing

* Date feature engineering
* One-hot encoding for city names
* Missing value analysis
* Outlier detection
* Correlation analysis
* Feature scaling

## Exploratory Data Analysis

* Correlation Heatmap
* Pair Plots
* Statistical Summary
* Outlier Detection using Boxplots

## Technologies Used

* Python
* TensorFlow
* PyTorch
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

## Future Improvements

* Hyperparameter tuning
* Model comparison with XGBoost and Random Forest
* Deployment using FastAPI
* Real-time AQI prediction dashboard
