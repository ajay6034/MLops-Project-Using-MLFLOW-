# MLops-Project-Using-MLFLOW-On-Simple-ML Classification Project
## Tracking Model Parameters, Model Metrics Like Accuracy

- Here Mainly I concentrated on working with Mlops Tool like MLFLOW on Machine Learning Model to Track the Model Versions, Model Parametrs, Model Metrics like Accuracy in local system.

# ML Classification with MLflow Tracking

## Overview
This project demonstrates a simple machine learning pipeline for classification using the Iris dataset. The project is designed to showcase the use of MLflow for tracking the model lifecycle, including:
- Experiment tracking
- Model parameter logging
- Model signature inference and storage

## Project Features
- **Dataset**: Iris dataset (from scikit-learn)
- **Algorithm**: Logistic Regression
- **Tracking Tool**: MLflow

## Workflow
1. **Dataset Loading**:
   - Loaded the Iris dataset.
   - Split it into training and testing sets with an 80-20 ratio.

2. **Model Training**:
   - Trained a logistic regression model with hyperparameters:
   - Trained the Model Twice By changing the hyperparameters to observe the versions in model registry.

3. **Evaluation**:
   - Predicted on the test dataset and evaluated the model using accuracy.

4. **MLflow Tracking**:
   - Logged the following using MLflow:
     - Model parameters
     - Evaluation metrics (accuracy)
     - Model artifacts and signatures

## Note: You can see the MLFLOW UI by running the Command "mlflow ui"
