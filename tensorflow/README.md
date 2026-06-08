# Air Quality Prediction using PyTorch

This notebook implements an Artificial Neural Network (ANN) using PyTorch to predict Air Quality Index (AQI).

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
* Train/Test split

### Exploratory Data Analysis

* Correlation Heatmap
* Pair Plot Analysis
* Boxplot-based Outlier Detection
* Descriptive Statistics

### Model Development

* Create custom PyTorch neural network
* Convert data to tensors
* Create DataLoader objects
* Train ANN model
* Evaluate model performance

## Libraries Used

* PyTorch
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

## Objective

Predict Air Quality Index (AQI) accurately using deep learning techniques implemented with PyTorch while demonstrating the complete PyTorch training pipeline.
