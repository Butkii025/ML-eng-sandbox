# Machine Learning Algorithms from Scratch

This folder contains implementations of core machine learning algorithms built **from scratch** using only basic libraries like NumPy — no scikit-learn or other ML frameworks used for the core logic. The goal is to understand how these algorithms work internally, not just how to call them.

## Contents

| Algorithm | File | Type |
|---|---|---|
| K-Nearest Neighbors | `knn.py` | Classification / Regression |
| Linear Regression | `linear_regression.py` | Regression |
| Logistic Regression | `logistic_regression.py` | Classification |

## Overview

### 1. K-Nearest Neighbors (KNN)
A non-parametric, instance-based algorithm that predicts the output for a new data point by looking at the 'k' closest points in the training data.

- Distance metric used: Euclidean distance
- Works for both classification and regression tasks

### 2. Linear Regression
Models the relationship between input features and a continuous target variable by fitting a straight line (or hyperplane) that minimizes the error.

- Optimization method: Gradient Descent
- Loss function: Mean Squared Error (MSE)

### 3. Logistic Regression
Used for binary classification problems. Predicts the probability of a class using the sigmoid function.

- Optimization method: Gradient Descent
- Loss function: Binary Cross-Entropy / Log Loss

## How to Run

```bash
python knn.py
python linear_regression.py
python logistic_regression.py
```

## Requirements

```
numpy
matplotlib   # for visualizations, if used
```
---
