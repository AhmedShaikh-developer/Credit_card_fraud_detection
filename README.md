# Credit Card Fraud Detection Predictive Models

## Introduction

This project is focused on detecting fraudulent credit card transactions using various machine learning models. The dataset used contains transactions made by European cardholders in September 2013. It is highly imbalanced, with only 0.172% of transactions being fraudulent. The goal is to develop models that can accurately identify these rare fraud cases.

## Dataset

The dataset consists of 284,807 transactions, of which 492 are frauds. It includes the following steps:
- **Loading the data**: Reading and understanding the dataset.
- **Data Exploration**: Checking for missing data, understanding data imbalance, and exploring the features.

## Models Implemented

This project explores several machine learning models for predicting fraud:
- **RandomForestClassifier**
- **AdaBoostClassifier**
- **CatBoostClassifier**
- **XGBoost**
- **LightGBM**

Each model is trained and evaluated using cross-validation to ensure robust performance.

## Installation

To run the code in this project, you need to have Python 3.x installed along with the necessary libraries. You can install the required packages using pip:

```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn catboost lightgbm xgboost
