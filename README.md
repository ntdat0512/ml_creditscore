# Credit Score Classification

## Overview

This project applies machine learning techniques to classify customer credit scores into different categories. The workflow includes data cleaning, preprocessing, dimensionality reduction, clustering, classification, and regression-based analysis.

## Dataset

The dataset used in this project is **Credit Score Classification** from Kaggle.

Main files:

* `train.csv`: used for training and evaluation
* `test.csv`: original test file without target labels

In this project, only `train.csv` is used and split into training and testing sets.

## Main Tasks

* Data cleaning and preprocessing
* Handling missing values and outliers
* Encoding categorical features
* Feature scaling
* Dimensionality reduction using PCA and LDA
* Clustering using KMeans and GMM
* Classification using KNN, Softmax Regression, and SVM
* Regression extension based on Softmax output

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
```

## Models

The following models are implemented and evaluated:

* K-Nearest Neighbors
* Softmax Regression
* Crammer-Singer SVM
* KMeans
* Gaussian Mixture Model
* Support Vector Regression
* Ridge Regression

## Results

The models achieved approximately **70% accuracy** on the credit score classification task. LDA generally improved model performance compared to using the original feature space.

## How to Run

### 1. Clone this repository

```bash
git clone https://github.com/your-username/credit-score-classification.git
cd credit-score-classification
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Download the dataset

Download the dataset from Kaggle and place the data files in the `data/` directory.

Expected files:

```text
data/
├── train.csv
└── test.csv
```

### 4. Run the notebook

```bash
jupyter notebook notebooks/CreditScoreClassification.ipynb
```

## Reports

* Full report: `reports/report.pdf`
* Presentation slides: `reports/presentation.pdf`

## Team Members

* Phan Nguyễn Mạnh Cường
* Nguyễn Tiến Đạt
* Hồ Trọng Hiếu
