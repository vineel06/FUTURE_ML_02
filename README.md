# FUTURE_ML_02
# Support Ticket Classification & Prioritization (Task 2)

## Overview
This project builds a machine learning system to automatically classify
customer support tickets and assign priority levels.

Such systems help businesses reduce response time and improve
customer satisfaction by routing tickets efficiently.

## Dataset
Customer Support Ticket Dataset (Kaggle)  
Each ticket includes text description, issue category, and priority level.

## Approach
1. Loaded and explored real-world support ticket data
2. Cleaned and preprocessed raw ticket text
3. Converted text into numerical features using TF-IDF
4. Built classification models using Logistic Regression
5. Predicted ticket categories and priority levels
6. Evaluated models using accuracy, precision, recall, and F1-score

## Results
- The model successfully classifies ticket categories such as
  Technical Issues and Billing Inquiries
- Priority prediction reflects the inherent ambiguity in real-world data
- Even moderate accuracy provides operational value by assisting
  support teams with faster triaging

## Business Use Case
This system can help:
- Automatically route tickets to the correct team
- Identify urgent issues early
- Reduce manual sorting effort
- Improve overall support efficiency

## Tools Used
- Python
- Pandas, NumPy
- Scikit-learn
- TF-IDF Vectorization
- Jupyter Notebook
