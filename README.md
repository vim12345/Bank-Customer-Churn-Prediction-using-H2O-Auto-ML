### Project Name:
## Bank Customer Churn Prediction using H2O Auto ML

## Context:
Customer churn refers to the rate at which customers stop doing business with an entity. In this project, we analyze customer churn by examining various customer attributes, including the recency of account actions and changes in account balance. The goal is to predict which customers are likely to churn, allowing the bank to take preventive measures.

## Aim:
Identify and Visualize Factors Contributing to Customer Churn: Understand the key attributes that lead to customer churn by visualizing the relationships between different features and the churn status.
## Build a Prediction Model:
Classify whether a customer is likely to churn or not.
Preferably choose a model that assigns a probability to the churn, helping customer service teams focus on high-risk customers.
## Tools:
Use Artificial Neural Networks (ANN) and H2O Auto ML to build the prediction models.
## Timeline of the Project:

## Data Analysis:

1. Explore and clean the data.
2. Understand data types and unique values.
3. Visualize the churn rate and relationship between customer features and churn.

## Feature Engineering:

1. Create new features like BalanceSalaryRatio and TenureByAge.
2. Encode categorical variables using methods like label encoding and one-hot encoding.
3. Scale continuous variables for better model performance.

   
## Model Building Using ANN:

## Model Architecture:
1. Input layer with 14 features.
2. Two hidden layers with 12 and 6 neurons respectively, using ReLU activation.
3. Output layer with 1 neuron using Sigmoid activation for binary classification.

## Training:
1. Use Adam optimizer, binary cross-entropy loss, and accuracy as the evaluation metric.
## Evaluation:
1. Evaluate the model on the test set and generate predictions.
2. Assess performance using confusion matrix, classification report, and accuracy score.
## Model Building and Prediction using H2O Auto ML:

## Setup:
Initialize H2O with a memory size of 16GB.
Use H2OAutoML to automatically train and evaluate multiple models within a given time limit.

## Model Selection:
Identify the best model based on the leaderboard, focusing on models like Stacked Ensembles for high performance.
Retrieve model details and performance metrics.

## Prediction:
Use the best model to predict churn on the test set.
