# PCA – Dimensionality Reduction on Digits Dataset
## Overview

This project demonstrates Principal Component Analysis (PCA) for dimensionality reduction and evaluates its impact on classification accuracy using the sklearn digits dataset.

## Objective

Reduce feature dimensions using PCA

Analyze explained variance vs number of components

Compare model performance before and after PCA

## Dataset

Source: sklearn.datasets.load_digits

Features: 64 pixel values

Classes: Digits 0–9

## Approach

Standardize features using StandardScaler

Train Logistic Regression as a baseline model

Apply PCA with multiple component values

Plot cumulative explained variance

Compare accuracy on reduced datasets

Visualize 2D PCA projection

## Key Results

PCA significantly reduces dimensionality

Most variance is retained with 30–50 components

Minimal accuracy loss compared to the baseline model

## Technologies Used

Python

Scikit-learn

NumPy

Matplotlib

## Author

Rushita Bhosale
