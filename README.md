# Credit Score Classification

## Overview

This project applies machine learning techniques to classify customer credit scores into different categories. The workflow includes data cleaning, preprocessing, dimensionality reduction, clustering, classification, and regression-based analysis.

## Dataset

The dataset used in this project is Credit Score Classification from Kaggle.

Main files:
- `train.csv`: used for training and evaluation
- `test.csv`: original test file without target labels

In this project, only `train.csv` is used and split into training and testing sets.

## Main Tasks

- Data cleaning and preprocessing
- Handling missing values and outliers
- Encoding categorical features
- Feature scaling
- Dimensionality reduction using PCA and LDA
- Clustering using KMeans and GMM
- Classification using KNN, Softmax Regression, and SVM
- Regression extension based on Softmax output

## Project Structure

```text
credit-score-classification/
├── README.md
├── requirements.txt
├── notebooks/
│   └── CreditScoreClassification.ipynb
├── reports/
│   ├── report.pdf
│   └── presentation.pdf
└── data/
    └── README.md
