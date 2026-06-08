# Air Quality Prediction using TensorFlow

This notebook implements an Artificial Neural Network (ANN) using TensorFlow/Keras to predict Air Quality Index (AQI).

## Workflow

### Data Loading

* Load Air Quality dataset
* Explore dataset structure

### Data Preprocessing

* Convert Date column to datetime format
* Extract:

  * Hour
  * Day
  * Month
* One-hot encode City feature
* Handle missing values
* Scale numerical features

### Exploratory Data Analysis

* Correlation Heatmap
* Pair Plot Analysis
* Boxplot-based Outlier Detection
* Descriptive Statistics

### Model Development

* Build ANN using TensorFlow/Keras
* Train model on processed data
* Evaluate performance on test data

## Libraries Used

* TensorFlow
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

## Objective

Predict Air Quality Index (AQI) accurately using deep learning techniques implemented with TensorFlow.
