# Crop-Prediction-ML-DL-Project
Machine Learning and Deep Learning based Crop Prediction System

This repository contains a comprehensive implementation of multiple machine learning and deep learning models for crop yield prediction using the Indian Crop Production Dataset (2000-2015). The project evaluates and compares 9 different algorithms including Random Forest, Gradient Boosting, XGBoost, Linear Regression, SVR, ANN, DNN, CNN, and LSTM to identify the most effective approach for agricultural yield forecasting.

Key Features:
Data preprocessing and feature engineering of 238,838 agricultural records
Implementation of 9 ML/DL models with hyperparameter tuning
Comprehensive model evaluation using MAE, RMSE, and R² metrics
Feature importance analysis and model interpretation
Sample prediction demonstration
Comparative analysis of ensemble methods vs. deep learning approaches

Best Performance: Random Forest achieved R² = 0.9127, demonstrating that ensemble methods outperform deep learning for tabular agricultural data.

Dataset:
Dataset: Indian Crop Production Dataset (2000-2015)
Records: 238,838 after preprocessing
Features: State_Name, District_Name, Crop_Year, Season, Crop, Area
Coverage: 33 states, 692 districts, 125 crops, 6 seasons

Machine Learning Models:
Linear Regression
Random Forest Regressor
Support Vector Regression (SVR)
Gradient Boosting Regressor
XGBoost Regressor

Deep Learning Models:
Artificial Neural Network (ANN)
Deep Neural Network (DNN)
Convolutional Neural Network (CNN)
Long Short-Term Memory (LSTM)

Dataset Link: https://www.kaggle.com/datasets/abhinand05/crop-production-in-india?resource=download

