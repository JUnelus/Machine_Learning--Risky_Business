# Machine Learning - Risky Business

![Credit Risk](credit-risk.jpg)

Welcome to the **Risky Business** project! In this assignment, we will dive into the world of machine learning to predict credit risk using data from peer-to-peer lending services. 

## Overview

Credit risk prediction is a critical task in the financial industry, and it presents a unique challenge due to its inherently imbalanced nature. The number of good loans significantly outweighs the number of at-risk loans. To tackle this, we will employ advanced techniques for training and evaluating models with imbalanced classes.

## Techniques Used

We will leverage the power of the following libraries to build and evaluate our models:

- **imbalanced-learn**: A Python package offering a variety of re-sampling techniques commonly used in datasets showing strong between-class imbalance.
- **Scikit-learn**: A machine learning library for Python that provides simple and efficient tools for data mining and data analysis.

### Methods

1. **Resampling**: Adjusting the class distribution by oversampling the minority class or undersampling the majority class.
2. **Ensemble Learning**: Combining the predictions of multiple models to improve the overall performance.

## Goals

By the end of this project, you will:

- Understand the challenges of imbalanced classification problems.
- Learn how to apply resampling techniques to balance the dataset.
- Explore ensemble learning methods to enhance model performance.
- Evaluate the models using appropriate metrics to ensure robust predictions.

## Getting Started

To get started, clone this repository and follow the instructions in the `credit_risk_ensemble.ipynb` notebook. Make sure you have the necessary libraries installed:

```bash
pip install -r requirements.txt