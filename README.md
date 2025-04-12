# Weather Classification Project

This repository presents a machine learning project to classify weather conditions based on historical meteorological data. It demonstrates classification techniques and serves as a practical application of supervised learning in environmental data analysis.

## Overview

The goal is to build a model that can classify different types of weather (e.g., sunny, rainy, foggy) using features such as temperature, humidity, wind speed, and visibility.

## Project Link

You can find the full implementation in the Jupyter Notebook:

**Notebook**: [`weather_classification.ipynb`](./weather_classification.ipynb)

## Project Features

- **Data Loading**: Importing weather dataset with structured features.
- **Data Preprocessing**:
  - Handling missing or inconsistent data
  - Encoding categorical features
  - Normalizing numeric variables
- **Exploratory Data Analysis**: Understanding feature distributions and class balance.
- **Model Training**:
  - Supervised classification model (e.g., Logistic Regression, Random Forest)
  - Train-test split for validation
- **Model Evaluation**:
  - Accuracy and classification report
  - Confusion matrix analysis
- **Visualization**: Plots to understand data and model performance.

## Dataset

The dataset includes weather observations such as:

- Temperature  
- Humidity  
- Wind Speed  
- Visibility  
- Weather Condition (target)

These features are used to classify weather types accurately.

## Key Findings

- The classification model achieved good performance with high accuracy on test data.
- Some classes (e.g., fog or storm) may be harder to classify due to overlap in conditions.
- Feature engineering and proper preprocessing greatly influenced performance.

## How to Use

To run this project locally:

1. Clone or download this repository.
2. (Optional) Create and activate a virtual environment.
3. Install required dependencies.
4. Launch the notebook:
