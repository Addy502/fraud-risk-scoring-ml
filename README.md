# fraud-risk-scoring-ml
Fraud risk scoring using machine learning on highly imbalanced transaction data, with a focus on precision–recall trade-offs and threshold tuning.

# Transaction Fraud Risk Scoring (Machine Learning)

## Overview
This project builds a fraud risk scoring model on anonymised credit card transaction data.  
The goal is to identify potentially fraudulent transactions while balancing fraud detection
rate and false positives.

## Dataset
- Anonymised credit card transaction dataset
- Highly imbalanced (~0.17% fraud)

## Approach
- Basic feature engineering (log transaction amount, time-based features)
- Logistic Regression with class-weight balancing
- Evaluation using precision–recall metrics
- Decision threshold tuning using precision–recall curve

## Results
- Recall (fraud): ~80%
- Precision (fraud): ~44%
- Demonstrates trade-off between fraud capture and alert volume

## Notes
This project focuses on practical considerations in fraud detection rather than model complexity.

