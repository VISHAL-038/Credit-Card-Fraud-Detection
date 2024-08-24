# Credit Card Fraud Detection

## Project Overview
This project aims to build a machine learning model that can detect fraudulent credit card transactions. The dataset used in this project contains transactions made by credit cards in September 2013 by European cardholders. The dataset is highly imbalanced, as the positive class (fraud) accounts for only 0.172% of all transactions.

The project involves various steps, including data preprocessing, data visualization, feature engineering, model training, and evaluation.

## Dataset
- **Source**: [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- The dataset contains 284,807 transactions, with 492 cases of fraud.
- Each transaction has 30 features, including `Time`, `Amount`, and anonymized features `V1` to `V28`.

## Problem Statement
The goal is to detect fraudulent credit card transactions using various classification algorithms. Given the highly imbalanced nature of the dataset, techniques like resampling and model evaluation using appropriate metrics are crucial for success.

## Project Workflow
### 1. Data Exploration
- Load and explore the dataset to understand its structure.
- Analyze class distribution (fraud vs. non-fraud transactions).

### 2. Data Preprocessing
- Handle missing values (if any).
- Scale features such as `Amount` and `Time`.
- Address class imbalance using techniques like:
  - Random Oversampling
  - Random Undersampling
  - Synthetic Minority Oversampling Technique (SMOTE)

### 3. Data Visualization
- Visualize the distribution of features using histograms, box plots, and correlation heatmaps.
- Plot fraud and non-fraud distributions for key features like `Amount` and `Time`.

### 4. Feature Engineering
- Generate new features (if applicable).
- Drop irrelevant or highly correlated features to reduce model complexity.

### 5. Model Selection and Training
- Train multiple machine learning models including:
  - Logistic Regression
  - Random Forest Classifier
- Use cross-validation to evaluate model performance.

### 6. Model Evaluation
- Evaluate models using appropriate metrics for imbalanced datasets:
  - Confusion Matrix
  - Precision, Recall, F1-Score
  - Area Under the ROC Curve (AUC-ROC)
- Compare results to select the best-performing model.



