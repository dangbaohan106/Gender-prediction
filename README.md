# Gender Prediction Using Machine Learning

This project presents a gender classification model built using Python and machine learning techniques. It aims to accurately predict gender based on a structured dataset with 7 input features, applying multiple classification algorithms for performance comparison.

## Objective

To develop a supervised learning model capable of predicting gender from the given dataset. The task includes selecting appropriate features, implementing various algorithms, evaluating model performance, and interpreting the results.

## Methods Used

Three machine learning models were applied and compared:

- **Logistic Regression**: A simple yet effective linear model for binary classification.
- **K-Nearest Neighbors (KNN)**: A non-parametric method used for classification by majority voting among neighbors.
- **Neural Network (using TensorFlow)**: A more complex model capturing nonlinear relationships for higher predictive power.

## Workflow Overview

1. **Data Exploration & Preprocessing**:
   - Handled missing values
   - Normalized numerical features
   - Encoded categorical variables

2. **Model Training & Evaluation**:
   - Split dataset into training and testing sets
   - Trained and tuned models
   - Evaluated using accuracy, classification reports, and confusion matrices

3. **Model Comparison**:
   - Compared model performance to select the most effective approach

## Key Results

- Achieved model accuracy up to **97%** with the Neural Network model
- Demonstrated strong predictive power using even basic features
- Clear performance metrics provided via classification reports

## Technologies

- Python, Jupyter Notebook
- Pandas, NumPy, Scikit-learn
- TensorFlow/Keras for Neural Network
