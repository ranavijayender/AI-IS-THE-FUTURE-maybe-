# AI-IS-THE-FUTURE-maybe-
ML project for predicting customer subscription to bank term deposits using Logistic Regression and KNN.
# Bank Term Deposit Subscription Prediction

## Project Overview
This project develops a machine learning model to predict whether a bank customer will subscribe to a term deposit. The analysis compares Logistic Regression and K-Nearest Neighbours (KNN), with the final model selected using validation performance.

## Dataset
The project uses the Bank Marketing Dataset from the UCI Machine Learning Repository.

Dataset:  
https://archive.ics.uci.edu/dataset/222/bank+marketing

## Machine Learning Approach
- Data exploration and quality assessment
- Data preprocessing and feature transformation
- Logistic Regression
- K-Nearest Neighbours (KNN)
- Model validation and comparison
- KNN hyperparameter tuning
- Final evaluation on unseen test data

## Final Model
K-Nearest Neighbours with `k = 3` was selected as the final model based on its F1-score on the validation set. The final model was retrained using the full training dataset and evaluated on the reserved test set.

## Repository Files
- `B104.ipynb` — Complete Jupyter Notebook containing the analysis and machine learning pipeline
- `B104.html` — Executed HTML version of the notebook

## Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook
- Jupyter Notebook
