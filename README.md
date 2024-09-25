

# Cross-Selling Insurance Policies
---
## Introduction
This project aims to develop predictive models that can enhance cross-selling strategies for insurance policies. The goal is to identify the likelihood of a customer purchasing additional policies based on various demographic and historical data.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Data Analysis](#data-analysis)
- [Models](#models)
- [Evaluation](#evaluation)
- [Contributors](#contributors)
- [License](#license)

## Features
- **Data Preprocessing**:
  - Handling of categorical variables using ordinal and one-hot encoding.
  - Sampling techniques: undersampling, oversampling (SMOTE).
- **Modeling**:
  - Logistic Regression with various configurations of encoding and sampling.
  - Cross-validation with undersampling, oversampling, and combinations of both.

## Data Analysis
The dataset consists of 381,109 observations, each described by 12 variables. The features include both quantitative (e.g., Age, Annual Premium) and qualitative data (e.g., Gender, Region Code). Key aspects:
- No missing values are present in the dataset.
- Feature distribution analysis and handling of categorical variables using encoding methods.

## Models
The primary model used in this project is Logistic Regression. Multiple variations of the model were created with different configurations:
- **Original dataset** with ordinal encoding.
- **Undersampled and oversampled datasets** using one-hot encoding.
- Evaluation of models using cross-validation techniques and comparison across different sampling strategies.

## Evaluation
Models were evaluated based on standard metrics like:
- Precision
- Recall
- F1-score

Results showed that oversampling techniques significantly improved the recall for the positive class (class 1). Confusion matrices and precision-recall curves were generated to compare model performance visually.

## Conclusions 
The first model trained using the original dataset showed a great accuracy score, which nevertheless reflected the unbalanced nature of the dataset. Using SMOTE the model reached a recall score of 0.98 for positive class and a precision score of 0.99 for negative class.
## Contributors
- [Francesco Gardini](https://github.com/gardi97)

