# NBA Draft Prediction Using Machine Learning

## Overview

This project applies machine learning techniques to predict NBA draft outcomes. The goal is to use data-driven models to forecast which players will be drafted and their subsequent performance in the NBA.

## Table of Contents

- [Introduction](#introduction)
- [Motivation](#motivation)
- [Data Extraction](#data-extraction)
- [Data Cleaning](#data-cleaning)
- [Feature Engineering](#feature-engineering)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Data Transformation](#data-transformation)
- [Model Selection and Training](#model-selection-and-training)
- [Model Evaluation and Interpretation](#model-evaluation-and-interpretation)
- [Model Deployment](#model-deployment)
- [SHAP Analysis](#shap-analysis)
- [Real-World Application](#real-world-application)
- [Challenges and Solutions](#challenges-and-solutions)
- [Final Thoughts](#final-thoughts)

## Introduction

This project aims to utilize machine learning to predict NBA draft outcomes, enhancing team decision-making processes and improving roster-building strategies.

## Motivation

### Building Successful NBA Rosters
Accurate predictions help teams assess rookie potential, ensuring long-term competitiveness.

### Improving Recruitment Strategies
Data analysis enables more effective identification of promising rookies and improves draft success rates.

### Personal Interest
As a data analysis enthusiast, this project provides a deep dive into the patterns and trends within NBA drafts.

## Data Extraction

1. **Connect to SQLite Database**
   - Extract data from relevant tables: player attributes, team salaries, player salaries, draft, draft combine, and game data.
   - Merge draft and draft combine data tables.
   - Remove unnecessary columns containing 'set' and 'location'.

## Data Cleaning

1. **Fill Missing Values**
   - Use mode for categorical data and mean for numerical data.
2. **Remove Irrelevant Data**
   - Eliminate redundant rows and columns.
3. **Verify Data Integrity**
   - Ensure the dataset's integrity post-cleaning.

## Feature Engineering

1. **Select Relevant Features**
   - Based on domain knowledge.
2. **Create New Columns**
   - Capture position data.
3. **Calculate Additional Metrics**
   - E.g., BMI.

## Exploratory Data Analysis (EDA)

1. **Summary Statistics**
   - Show distributions of key features.
2. **Target Variable Analysis**
   - Analyze the distribution of drafted vs. undrafted players.
3. **Visualize Relationships**
   - Correlation and feature relationship visualizations.

## Data Transformation

1. **Normalize/Scale Numeric Features**
2. **Encode Categorical Features**
   - Use one-hot encoding.
3. **Split Data**
   - Into training, validation, and test sets.

## Model Selection and Training

1. **Select Multiple Models**
   - Logistic regression, decision trees, random forests, SVM, KNN, gradient boosting, XGBoost.
2. **Train Models**
   - Using the training dataset.
3. **Evaluate Models**
   - Metrics: accuracy, precision, recall, F1-score, ROC-AUC, and specificity.

## Model Evaluation and Interpretation

1. **Compare Models**
   - Based on key metrics.
2. **Select Best Model**
   - Highest recall preferred.
3. **Feature Importance Analysis**
   - Identify key predictive factors.

## Model Deployment

1. **Save Best-Performing Model**
2. **Real-Time Predictions**
   - Load and use the model for predictions.

## SHAP Analysis

1. **Generate SHAP Values**
   - Explain model predictions.

## Real-World Application

1. **Data Collection**
   - Gather actual data for new players.
2. **Feature Engineering**
   - Standardize and engineer features.
3. **Predict Draft Position**
   - Use the model and SHAP analysis for predictions.

## Challenges and Solutions

1. **Missing Data**
   - Apply imputation techniques.
2. **Model Generalization**
   - Use cross-validation to avoid overfitting.
3. **Balancing Metrics**
   - Focus on optimizing recall for better prediction accuracy.

## Final Thoughts

This project demonstrates the power of data analysis and machine learning in transforming NBA draft predictions. Continuous learning and adaptation are crucial for success in rapidly evolving fields.

---

**Thank you for reviewing this project. For more details, please refer to the slides included.**
