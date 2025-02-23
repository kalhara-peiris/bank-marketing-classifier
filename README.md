# Bank Marketing Subscription Classifier

This repository contains a machine learning model to predict whether a customer will subscribe to a term deposit based on their personal and historical marketing data. The dataset used for this project is from the UCI Machine Learning Repository's "Bank Marketing" dataset.

## Project Overview

The goal of this project is to build a classifier model that predicts customer subscription to a term deposit based on various features like age, job, marital status, education, and previous marketing contacts.

### Key Features:
- Age
- Job
- Marital status
- Education level
- Previous marketing contact
- Other demographic and social features

### Objective:
- Train a machine learning model to predict if a customer will subscribe to a term deposit.
- Evaluate the performance of the model on various metrics, including accuracy, precision, recall, and F1-score.

## Dataset

The dataset consists of the following attributes:
- `age`: Age of the client
- `job`: Type of job
- `marital`: Marital status
- `education`: Level of education
- `previous`: Number of contacts performed during the campaign
- `contact`: Type of communication used
- `campaign`: Number of contacts performed during the campaign
- `pdays`: Number of days since the client was last contacted
- `previous`: Number of contacts performed before the campaign
- `poutcome`: Outcome of the previous marketing campaign
- `y`: Whether the client subscribed to the term deposit (target variable)

## Steps

1. **Data Preprocessing:**
   - Cleaning missing values
   - Encoding categorical variables
   - Normalizing numerical features
   
2. **Model Building:**
   - Split data into training and testing sets
   - Train models such as Random Forest, and Neural Network
   - Evaluate models using metrics such as accuracy, precision, recall, and F1-score

3. **Model Evaluation:**
   - Compare models based on performance metrics.
   - Choose the best performing model and tune hyperparameters.

## Requirements

- Python 3.x
- Pandas
- Numpy
- Scikit-learn
- Matplotlib
- Seaborn

Install the dependencies using pip:

```bash
pip install -r requirements.txt
