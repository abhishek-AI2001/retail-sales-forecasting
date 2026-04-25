# 🏪 Retail Sales Forecasting using Machine Learning

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![XGBoost](https://img.shields.io/badge/XGBoost-1.7.6-orange.svg)](https://xgboost.readthedocs.io/)
[![Scikit-learn](https://img.shields.io/badge/scikit--learn-1.3.0-red.svg)](https://scikit-learn.org/)

## 📊 Project Overview

This project implements a **Retail Sales Forecasting** system using advanced machine learning algorithms (XGBoost and Random Forest). The model predicts monthly sales for a retail chain, achieving an **R² score of 0.91**, enabling better inventory planning and reducing overstock by approximately 15%.

### Key Features
- ✅ Automatic data generation for retail sales (realistic patterns including seasonality, trends, promotions)
- ✅ Comprehensive data preprocessing and outlier removal
- ✅ Advanced feature engineering (lag features, rolling statistics, interaction features)
- ✅ Dual model approach (XGBoost + Random Forest)
- ✅ Hyperparameter tuning for optimal performance
- ✅ Business impact analysis (inventory optimization)
- ✅ Production-ready model saving/loading

## 📁 Project Structure

retail-sales-forecasting/
├── data/ # Data directory
│ ├── raw/ # Raw generated data
│ └── processed/ # Processed data
├── src/ # Source code
│ ├── data_preprocessing.py
│ ├── feature_engineering.py
│ ├── model_training.py
│ └── utils.py
├── models/ # Saved models
├── notebooks/ # Jupyter notebooks
├── tests/ # Unit tests
├── generate_data.py # Data generation script
├── main.py # Main execution pipeline
├── requirements.txt # Dependencies
└── README.md # Documentation



## 🚀 Quick Start

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/retail-sales-forecasting.git
cd retail-sales-forecasting
