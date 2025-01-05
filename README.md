# Logistic Regression from Scratch for the Titanic Dataset

This project implements logistic regression from scratch (without using pre-built libraries like Scikit-learn) to predict the survival of passengers in the Titanic dataset. Logistic regression is a widely used machine learning algorithm for binary classification problems, and in this case, it is applied to predict whether a passenger survived or not based on various features such as age, gender, passenger class, etc.

## Objective

The goal of this project is to implement a logistic regression model from scratch to predict the survival (Survived) of passengers in the Titanic dataset. The target variable (Survived) is binary:

- `1`: The passenger survived.
- `0`: The passenger did not survive.

## Dataset

The Titanic dataset used in this project contains the following features:

- **PassengerId**: Unique identifier for each passenger.
- **Pclass**: Passenger class (1st, 2nd, or 3rd).
- **Name**: Name of the passenger.
- **Sex**: Gender of the passenger.
- **Age**: Age of the passenger.
- **SibSp**: Number of siblings/spouses aboard.
- **Parch**: Number of parents/children aboard.
- **Ticket**: Ticket number.
- **Fare**: Fare paid for the ticket.
- **Cabin**: Cabin number.
- **Embarked**: Port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton).

## Approach

The logistic regression model is implemented from scratch by following these key steps:

1. **Data Preprocessing**:
    - Handle missing values.
    - Encode categorical features (e.g., gender and embarkation port).
    - Normalize numerical features.

2. **Sigmoid Function**:
    - Implement the sigmoid function to map the model's output to a probability between 0 and 1.

3. **Cost Function**:
    - Define the cost function (cross-entropy loss) to measure the performance of the logistic regression model.

4. **Gradient Descent**:
    - Implement the gradient descent algorithm to optimize the model parameters and minimize the cost function.

5. **Prediction**:
    - Make predictions based on the learned model parameters.

6. **Evaluation**:
    - Evaluate the model's performance using accuracy, precision, recall, and other metrics.
