# Diabetes Health Prediction

A supervised machine learning project to predict mental health outcomes using regression models (i.e. ForestRegression) on the CDC Diabetes Health Indicators dataset. This project explores relationships between diabetes health indicators and poor mental health using robust machine learning methods.

---

## Table of Contents

- About the Project
- Getting Started
- Usage
- Features
- Results
- Contributing
- License
- Acknowledgments

---

## About the Project

A supervised machine learning model to predict mental health outcomes. By applying a regression model, we can assess the impact of various social determinants on poor mental health days. 

Key objectives include:

Developing and comparing machine learning models to predict diabetes-related mental health outcomes.
Exploring feature engineering, multicollinearity analysis, and model tuning.
Providing interpretable insights through metrics like R², Adjusted R², MAE, RMSE, and ROC AUC.

Getting Started

Follow these instructions to set up and replicate the analysis locally.
Prerequisites
Python 3.10+
Dependencies listed in requirements.txt

---

## Installation

## Clone the repo.
git clone https://github.com/yourusername/diabetes_health_prediction.git

## Navigate to the project directory
cd diabetes_health_prediction

## Install dependencies
pip install -r requirements.txt

## Features

✔️ Regression Analysis: Implements multiple regression models, including Random Forest and Ridge Regression, to predict diabetes outcomes.

✔️ Comprehensive Evaluation Metrics: Provides R², Adjusted R², MAE, RMSE, and ROC AUC to assess model performance.

✔️ Multicollinearity Checks: Identifies and manages feature multicollinearity for improved model stability.

✔️ Scalable Feature Engineering: Includes a composite Health Burden Score for more robust predictions.

✔️ Extensible Codebase: Designed to integrate additional datasets or predictive models easily.

---

## Usage

To train and evaluate the models, run the provided main.py script
Loads the CDC Diabetes Health Indicators dataset.
Splits the data into training and test sets.
Trains and evaluates four regression models: Random Forest, Ridge Regression, Linear Regression, and Gradient Boosting.
Outputs performance metrics and visualizations.

---

## Customization

Modify config.py to adjust hyperparameters, feature selections, or model settings.

Use additional datasets by replacing the default dataset in the data/ folder.

## Results

The project outputs include:
Model evaluation metrics: R², Adjusted R², MAE, RMSE, and ROC AUC.
Visualizations of model performance and feature importance.
Insights on how health indicators contribute to diabetes prediction.

--- 

## License

Distributed under the MIT License. See LICENSE for more information.

---

## Acknowledgments

The CDC for providing the Diabetes Health Indicators dataset.
The Scikit-learn community for powerful machine learning tools.
Python's Pandas, NumPy, and Matplotlib libraries for data analysis and visualization.

