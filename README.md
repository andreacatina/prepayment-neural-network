# prepayment-neural-network
Overview

This project implements a neural network model to estimate the Conditional Prepayment Rate (CPR) of mortgage-backed securities. The objective is to capture the nonlinear relationship between loan characteristics, market conditions, and borrowers’ prepayment behavior, providing more accurate predictions than traditional logistic regression models.

Key Features

Data preprocessing: cleaning, normalization, and handling of mortgage loan-level datasets.

Custom loss function: volume-weighted error metric to account for the loan outstanding balance in training.

Model implementation: fully connected neural network built in TensorFlow/Keras, compared against logistic regression as a benchmark.

Evaluation metrics: ROC-AUC, residual plots, and monthly prediction vs. actual CPR visualization.

Hyperparameter tuning: optimized with KerasTuner Hyperband to select the best architecture, learning rate, and batch size.

Technologies

Python (NumPy, Pandas, Matplotlib, Scikit-learn, TensorFlow/Keras)

KerasTuner for hyperparameter optimization

Matplotlib/Seaborn for data visualization

Results

Neural network consistently outperformed logistic regression in predictive accuracy.

Visual analysis confirmed the model’s ability to capture time-varying patterns of prepayment risk.

The framework can be extended to other credit risk applications, such as default or migration modeling.
