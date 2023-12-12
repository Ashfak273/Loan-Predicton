# Loan-Predicton# Loan Prediction Project

This repository contains the code and data for a Loan Prediction project. The goal of this project is to predict whether a loan application will be approved or not based on various features. Different machine learning models, including Logistic Regression, Decision Tree, Random Forest, and XGBoost, have been implemented for this task.

## Project Structure

- **`data/`**: Contains the dataset used for training and testing.
- **`notebooks/`**: Jupyter notebooks for data preprocessing, model training, and evaluation.
  - `1_Data_Preprocessing.ipynb`: Data cleaning and preprocessing using LabelEncoder.
  - `2_Model_Training.ipynb`: Model training using various classifiers (Logistic Regression, Decision Tree, Random Forest, XGBoost).
  - `3_Model_Tuning.ipynb`: Hyperparameter tuning using Random Search and Grid Search.
  - `4_Ensemble_Model.ipynb`: Implementation of a Voting Classifier for model ensemble.
- **`src/`**: Python scripts for utility functions and model training.
- **`results/`**: Store model evaluation metrics, plots, and other results.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/loan-prediction.git

cd loan-prediction

pip install -r requirements.txt

jupyter notebook

