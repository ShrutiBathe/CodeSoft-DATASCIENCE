# Titanic Survival Prediction using Machine Learning

## Project Overview

This project aims to predict whether a passenger survived the Titanic disaster using Machine Learning techniques. The model is trained on passenger information such as age, gender, passenger class, fare, and family details.

## Problem Statement

Build a classification model that predicts passenger survival based on historical Titanic passenger data.

## Dataset

The dataset contains information about Titanic passengers, including:

* Passenger Class (Pclass)
* Gender (Sex)
* Age
* Number of Siblings/Spouses (SibSp)
* Number of Parents/Children (Parch)
* Fare
* Embarked Port
* Survival Status

Target Variable:

* Survived

  * 0 = Did Not Survive
  * 1 = Survived

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Random Forest Classifier

## Project Workflow

1. Data Collection
2. Data Exploration
3. Data Cleaning
4. Feature Engineering
5. Data Encoding
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Feature Importance Analysis
10. Model Saving

## Feature Engineering

Additional features were created:

### FamilySize

FamilySize = SibSp + Parch + 1

### IsAlone

Indicates whether a passenger was travelling alone.

## Machine Learning Model

Algorithm Used:

* Random Forest Classifier

Problem Type:

* Supervised Learning
* Binary Classification

## Evaluation Metrics

* Accuracy Score
* Confusion Matrix
* Classification Report

## Key Findings

* Female passengers had a higher survival rate.
* First-class passengers were more likely to survive.
* Fare influenced survival probability.
* Family size affected survival chances.

## Files Included

* Titanic_Survival_Prediction.ipynb
* titanic_survival_model.pkl
* README.md

## Future Improvements

* Compare multiple machine learning algorithms.
* Perform hyperparameter tuning.
* Deploy the model using Flask or Streamlit.
* Improve prediction performance using advanced feature engineering.

## Author

Shruti Bathe

B.Tech CSE (Data Science)

