# TitanicSurvivalPrediction
This project involves a Logistic Regression model to predict the survival of passengers aboard the Titanic. The primary aim is to analyze various passenger attributes to determine the likelihood of survival during the tragic shipwreck.

## Project Overview
The sinking of the Titanic remains a significant event in history, and understanding the factors that influenced passenger survival can provide valuable insights into decision-making, safety measures, and emergency protocols.

## Data 
The dataset used in this project is sourced from [Kaggle ](https://www.kaggle.com/competitions/titanic/data) and has been split into two distinct groups:
Training set (train.csv)

1. Test set (test.csv)
2. Test set (test.csv)

The dataset comprises the following features:

- Pclass: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- Sex: Gender of the passenger
- Age: Age in years
- SibSp: Number of siblings or spouses aboard the Titanic
- Parch: Number of parents or children aboard the Titanic
- Ticket: Ticket number
- Fare: Passenger fare
- Cabin: Cabin number
- Embarked: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
- Target class: Survived (0 = No, 1 = Yes)
- The main objective is to predict the likelihood of survival based on these factors. The 'Survived' column serves as the target variable for the model.

## Model Training
The Logistic Regression model has been employed due to its effectiveness in binary classification problems, like predicting survival (Yes/No) in this case. The features have been preprocessed, missing values handled, and categorical variables encoded to prepare the data for training.

The model has been trained on the training dataset (train.csv) and fine-tuned to optimize its predictive accuracy. Evaluation metrics and cross-validation techniques have been utilized to ensure the model's robustness and generalizability.

## Future Steps
Further improvements or exploration could involve feature engineering, trying different algorithms for comparison, or refining the model's parameters for enhanced accuracy.

This project aims to contribute to the understanding of factors influencing survival on the Titanic and demonstrates the application of Logistic Regression in predictive modeling.
