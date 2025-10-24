# Evaluation of Supervised Learning Models for Credit Card Fraud Prediction
##  Author: Pau Casé - October 2025

# 📄 Project Overview
This project evaluates the performance of multiple supervised learning algorithms for credit card fraud detection using real-world data. Multiple tests were run with different hyperparameters.
The main objective is to compare models in terms of accuracy and PRAUC with a special focus on handling class imbalance.
It uses the Kaggle dataset from Université Libre de Bruxelles (https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

# 🧰 Repository Contents

## File	Description
- Credit Card Fraud Prediction.ipynb	Jupyter Notebook with data analysis, preprocessing, and model evaluation.
- Evaluation of reinforcement learning models in Credit Card Fraud.pdf  Detailed report discussing methodology, results, and conclusions.
- requirements.txt	List of Python packages used.

## Models evaluated
- Random Forest
- Decision Tree
- K-Nearest Neighbors

## Metrics Used
- Precision-Recall Area Under the Curve (main)
- Accuracy, Precision, Recall
- Confusion Matrix

## Results
Among all tested models, the Decision Tree achieved the highest balance between recall and precision, indicating strong performance in detecting fraudulent transactions.
