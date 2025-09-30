# Prepayment Risk Prediction with Neural Network

## Overview
This project implements a neural network to estimate the **Conditional Prepayment Rate (CPR)** of mortgage-backed securities.  
The model captures nonlinear relationships between loan characteristics, market conditions, and borrower behavior, providing more accurate forecasts compared to traditional logistic regression.

## Features
- Data preprocessing: cleaning, normalization, and feature engineering on loan-level datasets.  
- Custom **volume-weighted loss function** to account for loan outstanding balances.  
- Neural network built with **TensorFlow/Keras**, benchmarked against logistic regression.  
- **Hyperparameter tuning** with KerasTuner (Hyperband).  
- Evaluation: ROC-AUC, residual plots, and monthly CPR prediction vs. observed data.

## Technologies
- Python (NumPy, Pandas, Scikit-learn, TensorFlow/Keras)  
- KerasTuner for optimization  
- Matplotlib / Seaborn for visualization  

## Results
- The neural network outperformed logistic regression in predictive accuracy.  
- The model effectively captured time-varying patterns of prepayment risk.  
- Framework can be extended to other credit risk tasks (e.g., default, migration).  

---
Author: **Andrea Catina**
