# InsightFlow-Predictive-Analytics-and-Modeling
Machine Learning Project using Python for Data cleaning and training model.
Machine Learning Project – Heart Disease Prediction
Overview

This project demonstrates a complete Machine Learning workflow using only Python.
The goal is to analyze a real-world heart disease dataset, clean and explore the data, and apply multiple supervised learning algorithms to predict the presence of heart disease.
The project concludes with a final presentation created in Gamma.

Dataset

Source: https://raw.githubusercontent.com/mrdbourke/zero-to-mastery-ml/master/data/heart-disease.csv

Description: The dataset includes clinical and behavioral features used to determine whether a patient shows signs of heart disease.

Content: A mix of numerical and categorical variables such as age, sex, blood pressure, cholesterol, maximum heart rate, and more.

Tools

Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn

Google Colab for running the notebook

Gamma for the final PowerPoint-style presentation

Steps
1. Data Loading

Loaded the CSV directly from the URL using Pandas

Checked dataset structure (columns, types, shape)

2. Exploratory Data Analysis (EDA)

Summary statistics

Visual exploration of distributions

Correlation analysis and heatmaps

Detection of outliers and early patterns

3. Data Cleaning & Preprocessing

Handling missing values

Encoding categorical features

Feature scaling when required

Splitting the data into training and test sets

4. Machine Learning Models

Explored several classification algorithms, including:

Logistic Regression

Decision Tree

Additional comparison models

Each model was evaluated using:

Accuracy

Precision, Recall, F1-Score

Confusion Matrix

Cross-validation

Feature importance (when applicable)

5. Model Selection

Performance comparison across all models

Selection of the best-performing algorithm

Hyperparameter tuning with GridSearchCV or RandomizedSearchCV

6. Presentation

Final presentation created with Gamma, including:

Problem overview

Analysis workflow

Models tested

Evaluation metrics

Key conclusions and insights

Results

Identification of the most influential features

Clear comparison across multiple ML algorithms

Selection of the most robust and reliable model

Insights into factors contributing to heart disease risk

How to Run
In Google Colab

Open the notebook.

Run all cells in order.

The dataset loads automatically from the provided URL.

Gamma Presentation

Open the Gamma project and export it as a PowerPoint file if needed.
