# Income-Inequality-Prediction
## Overview

Predicts whether an individual earns above or below a certain income limit using machine learning. Helps monitor income inequality for policymaking and research.

## Dataset

     43 columns including demographic, employment, and household features

     Target: income_above_limit (binary: Above/Below limit)

     Contains missing values (NaN or "?")

## Steps

    Data Cleaning: Remove ID, strip spaces, replace "?" with NaN, fill missing values

    Encoding: Label encode categorical features

    Scaling: StandardScaler for numeric features

    Train-Test Split: 80% train, 20% test

    Model: Random Forest Classifier

    Evaluation: F1-score

## How to Run
    pip install pandas numpy scikit-learn matplotlib
    python income_inequality_prediction.py

## Results

    F1-score: 0.975 

    Top features influencing income: age, education, employment, marital_status, race
