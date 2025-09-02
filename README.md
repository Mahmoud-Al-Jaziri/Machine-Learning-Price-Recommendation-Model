# Restaurant Price Recommendation Model 🍽️💰

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-orange?logo=ai)
![XGBoost](https://img.shields.io/badge/XGBoost-1.5%2B-green?logo=xgboost)
![Flask](https://img.shields.io/badge/Flask-2.0%2B-lightgrey?logo=flask)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.0%2B-red?logo=scikitlearn)

A machine learning model that recommends optimal pricing for restaurant dishes using XGBoost regression and feature importance analysis.

## ✨ Features

- **Price Optimization**: Suggests optimal pricing for restaurant menu items
- **Feature Importance**: Identifies key factors influencing dish pricing
- **Categorical Encoding**: Handles categorical data using one-hot encoding
- **Web API**: Flask-based REST API for easy integration
- **Model Interpretability**: Provides insights into pricing decisions

## 🏗️ Model Architecture

### Data Preprocessing
- **Low Cardinality Identification**: Automatic detection of categorical columns
- **One-Hot Encoding**: Conversion of categorical features to numerical representations
- **Feature Scaling**: Normalization of numerical features
- **Data Cleaning**: Handling missing values and outliers

### Algorithm Selection
- **XGBoost Regressor**: Chosen for optimal balance of speed and accuracy
- **Feature Importance**: Built-in feature selection capabilities
- **Gradient Boosting**: Sequential model improvement through error correction

## 📊 Dataset Features

Typical features used in the model:
- Dish category (appetizer, main course, dessert, etc.)
- Ingredients cost and complexity
- Preparation time
- Restaurant type and location
- Seasonal availability
- Customer preferences and trends
- Competitor pricing data
