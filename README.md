# Loan Prediction Project

This project predicts loan approval status using the bankcustomer.csv dataset containing applicant information. The dataset is processed and used to train a Support Vector Machine (SVM) model.

## Installation

Ensure Python is installed along with the following libraries:

- numpy
- pandas
- seaborn
- scikit-learn

Install them using pip.

## Data Preprocessing

1. Load the dataset and remove missing values.
2. Convert categorical values to numerical.
3. Separate features and target variables.

## Model Training

1. Split the dataset into training and testing sets.
2. Train an SVM model with a linear kernel.

## Evaluation

The model achieved an accuracy of 79.8% on the training set and 83.3% on the testing set.
