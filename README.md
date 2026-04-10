# Titanic Survival Prediction (Advanced ML Project)

## Overview
This project predicts passenger survival on the Titanic using machine learning with advanced feature engineering and a Gradient Boosting model. The goal is to improve prediction accuracy by extracting hidden patterns from the dataset.

## Performance
- Mean Cross-Validation Accuracy: 91.11%
- Validation Method: Stratified 10-Fold Cross Validation
- Model: Gradient Boosting Classifier

## Key Features
- Feature engineering using family and ticket-based grouping
- Extraction of social features from names (titles, surnames)
- Gender and age-based survival indicators
- Fare-based data imputation
- Handling class imbalance using stratified validation

## Methodology
- Data preprocessing and cleaning
- Feature engineering to generate survival-related signals
- Encoding of categorical variables
- Model training using Gradient Boosting
- Evaluation using cross-validation

## Model Strategy
The Gradient Boosting model was selected for its ability to:
- Capture non-linear relationships
- Handle mixed feature types
- Improve performance through ensemble learning

## Validation Approach
Stratified K-Fold Cross Validation was used to ensure balanced class distribution across folds and reliable performance estimation.

## Key Insight
Most of the performance improvement comes from feature engineering rather than model complexity. Social and group-based patterns significantly improve prediction quality.

## Tech Stack
Python, Pandas, NumPy, Scikit-learn
