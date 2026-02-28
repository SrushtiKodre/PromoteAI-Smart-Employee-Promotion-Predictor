# PromoteAI-Smart-Employee-Promotion-Predictor
The proposed system is a machine learning-based promotion prediction model that analyzes employee attributes such as education, performance rating, training score, service length, and awards won to predict whether an employee is likely to be promoted. The system provides: Binary prediction (Promoted / Not Promoted) Promotion probability.

# AI-Powered Employee Promotion Prediction System

A Machine Learning-based web application that predicts whether an employee is likely to be promoted based on performance, training, and service-related attributes.

Built using Logistic Regression and deployed with Streamlit.

# Dataset used:
HR Analytics: Employee Promotion Dataset :  https://www.kaggle.com/datasets/arashnic/hr-ana

# Project Overview

Promotion decisions in large organizations involve analyzing multiple employee performance indicators. Manual evaluation can be time-consuming and inconsistent.

This project provides a data-driven HR analytics solution that:

Predicts employee promotion eligibility

Provides promotion probability score

Offers an interactive web-based interface for HR users

# Tech Stack

Programming Language: Python

Data Processing: Pandas, NumPy

Visualization: Matplotlib, Seaborn

Machine Learning: Scikit-learn

Web Framework: Streamlit

Deployment: ngrok

Development Environment: Google Colab

# Libraries used:

sklearn

pickle

streamlit

pyngrok

imbalanced-learn (optional for experimentation)

# Features Used for Prediction

Department

Region

Education

Gender

Recruitment Channel

Number of Trainings

Age

Previous Year Rating

Length of Service

Awards Won

Average Training Score

# Machine Learning Approach

Algorithm Used:

Logistic Regression (with class_weight='balanced')

Why Logistic Regression?

Performs well on imbalanced datasets

Provides interpretable results

Efficient for binary classification

Evaluation Metrics:

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

# How to Run This Project in Google Colab

This project was developed and deployed using Google Colab.

Follow the steps below to run it.

📌 Step 1: Upload Project Files to Colab

Open Google Colab and upload: Download HR Analytics : Employee Promotion Dataset and upload on colab

train.csv and test.csv

app.ipynb

# Configure ngrok Authentication

Create an account at
ngrok
and copy your Auth Token.
