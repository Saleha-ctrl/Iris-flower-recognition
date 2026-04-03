# Iris Flower Classification

## Overview
This is a classic machine learning classification project that predicts the species of Iris flowers based on petal and sepal measurements.

## Tech Stack
- Python
- Scikit-learn
- Pandas
- Matplotlib

## Problem Statement
Classify iris flowers into:
- Setosa
- Versicolor
- Virginica

based on input features.

## Workflow
1. Load dataset (Iris.csv)
2. Data preprocessing
3. Feature scaling using StandardScaler
4. Train ML models (KNN / SVM / Logistic Regression)
5. Select best model
6. Save model using pickle
7. Test predictions
   
## Approach
- Data exploration and visualization
- Model training (KNN / Logistic Regression / SVM)
- Evaluation using accuracy score

## Model Files
- scaler.pkl → Used for feature scaling
- Iris_recognition_model.pkl → Trained ML model saved using joblib/pickle

## Results
- Achieved high accuracy (~95–100%)
- Simple but effective classification model

## How to Run
```bash
pip install -r requirements.txt
open code.ipynb in Jupyter / VS Code
