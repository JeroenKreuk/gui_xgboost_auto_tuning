# XGBoost Auto Tuner

A GUI application for optimizing hyperparameters of XGBoost models and evaluating their performance. This tool is designed to assist in the process of tuning hyperparameters for binary classification tasks. It allows users to load their dataset, preprocess it, perform feature selection, apply SMOTE resampling, scale the features, and optimize XGBoost hyperparameters using Optuna.

## Features

- Load and preprocess datasets.
- Perform one-hot encoding of categorical variables.
- Calculate feature importance using RandomForestRegressor.
- Perform feature selection based on user-defined importance threshold.
- Apply SMOTE (Synthetic Minority Over-sampling Technique) for addressing class imbalance.
- Option to scale features.
- Optimize XGBoost hyperparameters using Optuna.
- Evaluate the trained model on the training and test sets.
- Display evaluation results in a graphical user interface.
![image](https://github.com/JeroenKreuk/gui_xgboost_auto_tuning/assets/85551796/81acf7bd-5f96-426a-a3e6-4f61bd69a9c5)

## Usage

1. Run the Python script.
2. Load a dataset using the "Open database" button.
3. Select the target/label column.
4. Process and analyze the data:
   - Dummyfy the dataset (one-hot encoding).
   - Calculate feature importance using RandomForestRegressor.
   - Perform feature selection based on importance threshold.
   - Apply SMOTE and scale the features as needed.
5. Optimize XGBoost hyperparameters using Optuna.
6. Evaluate the final model on the training and test datasets.
7. View and analyze the results within the GUI.

## Prerequisites

Make sure you have the following Python libraries installed:

- tkinter
- pandas
- scikit-learn
- xgboost
- optuna
- imbalanced-learn

You can install these libraries using `pip`:

```bash
pip install tkinter pandas scikit-learn xgboost optuna imbalanced-learn
