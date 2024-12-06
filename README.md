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

## Screenshots Of MLFLOW UI:

**Experiment Of ML Model Trained 2 Times**

![image](https://github.com/user-attachments/assets/c4d13e91-06b5-4f9b-b6c3-5488aef310ff)

**Overview Of Model Trained Parameters & Metrics**

***For 2 Versions***

![image](https://github.com/user-attachments/assets/75436b81-ff80-4bb0-ba02-cbc38018d530)

![image](https://github.com/user-attachments/assets/01f98e73-4ce5-4ad3-af2b-3d7a0a82270b)

- We can observe the Model Artifacts and Versions on Right Side ("Model Registry") having necessary files like "Pickle File", "yaml File", "requirements.txt File" i.e., combining like a package.

 ![image](https://github.com/user-attachments/assets/54bab15a-b401-4247-887c-8f3584f6902d)
 
**Comparision Of Versions Based On Model Metrics**

![image](https://github.com/user-attachments/assets/61027a7b-cced-49b6-b1c9-0378a3894e84)


