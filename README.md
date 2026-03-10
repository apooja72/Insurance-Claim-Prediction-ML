# Insurance Claim Prediction using Machine Learning
Insurance Claim Prediction is a machine learning project that aims to predict whether a vehicle insurance policyholder will make a claim based on various customer and vehicle-related features.
The objective of this project is to apply machine learning techniques to analyze insurance data and build predictive models that can help insurance companies identify high-risk customers and improve decision-making.

## Project Overview
This project predicts whether a vehicle insurance customer will file a claim based on customer and vehicle-related features. Machine learning models are used to analyze the dataset and help identify potential insurance risks.

---

## Problem Statement
Insurance companies need to assess the likelihood of claims to manage risk and improve decision-making. This project builds classification models to predict whether a policyholder will make an insurance claim.

---

## Dataset
The dataset includes various vehicle and policy attributes such as:

- Vehicle age  
- Customer age  
- Fuel type  
- Engine type  
- Transmission type  
- Safety features (airbags, ESC, sensors)  
- Vehicle specifications  

**Target Variable**

`claim_status`

- 0 → No claim  
- 1 → Claim

---

## Project Workflow

### Data Preprocessing
- Removed unnecessary columns (`policy_id`)
- Handled missing values
- Encoded categorical variables

### Model Training
Three machine learning models were trained:

- Logistic Regression  
- Decision Tree  
- Random Forest  

### Model Evaluation
Models were evaluated using:

- Accuracy  
- Precision  
- Recall  
- Confusion Matrix  

The best-performing model was selected based on evaluation metrics.

---

## Tools & Technologies

- Python  
- Pandas  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

