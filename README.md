# Diabetes Regression - Machine Learning Project

## Overview
This project implements a complete Machine Learning pipeline for regression using the Diabetes dataset.  
The goal is to predict a continuous target value based on medical features.

## Dataset
The dataset used is the built-in `sklearn.datasets.load_diabetes`, containing 10 numerical features related to patient health.

## Models used
- Linear Regression
- Decision Tree Regressor
- Ridge Regression
- Lasso Regression
- K-Nearest Neighbors
- Support Vector Regression

## Workflow
1. Data exploration (describe, histograms, boxplots, scatter matrix)
2. Data preprocessing (train-test split, scaling)
3. Model comparison with K-Fold Cross Validation (NMSE)
4. Hyperparameter tuning (GridSearchCV)
5. Evaluation on test set (MSE, R²)
6. Learning curves analysis
7. PCA visualization (2D projection)

## Results
Best performing model: Ridge / Lasso (based on NMSE comparison)

## Comments
- Linear models perform well on this dataset
- Decision Trees tend to overfit
- PCA shows partial separability of target values

## How to run
Requirements:
- python 3.x
- numpy
- pandas
- matplotlib
- scikit-learn
