# Insurance-Claim-Prediction-ML
nsurance Claim Prediction is a machine learning project that aims to predict whether a vehicle insurance policyholder will make a claim based on various customer and vehicle-related features. Built predictive models that can help insurance companies identify high-risk customers and improve decision-making.
Project Overview

This project predicts whether a vehicle insurance customer will file a claim based on customer and vehicle information. Machine learning models are used to analyze the dataset and identify patterns that help insurance companies assess risk and make data-driven decisions.

Problem Statement

Insurance companies handle thousands of policies and claims. Predicting whether a customer is likely to make a claim can help companies:

Reduce financial risk

Improve pricing strategies

Detect high-risk customers

This project builds a machine learning model to classify whether a policyholder will make an insurance claim.

Dataset

The dataset contains vehicle and policy-related information such as:

Vehicle age

Customer age

Fuel type

Engine type

Transmission type

Safety features (airbags, ESC, sensors)

Vehicle specifications

Target variable:

claim_status

0 → No claim

1 → Claim

Project Workflow
1 Data Preprocessing

Removed unnecessary columns (policy_id)

Handled missing values

Encoded categorical variables

2 Feature Selection

Selected relevant features for model training

3 Model Training

Three machine learning models were trained:

Logistic Regression

Decision Tree

Random Forest

4 Model Evaluation

Models were evaluated using:

Accuracy

Precision

Recall

Confusion Matrix

The best-performing model was selected based on these metrics.

Tools & Technologies

Python

Pandas

Scikit-learn

Matplotlib

Seaborn

Jupyter Notebook

Results

The models were compared using performance metrics and visualized using confusion matrices and accuracy comparison charts.
