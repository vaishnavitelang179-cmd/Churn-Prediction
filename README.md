# Churn-Prediction


This project focuses on predicting customer churn using machine learning techniques.  
The goal is to identify customers who are likely to leave a service based on their demographic, service usage, and account-related information.

Predicting churn helps businesses take proactive actions such as targeted offers or improved customer support to retain customers.

---

## Problem Statement
Customer churn is a major challenge for subscription-based businesses.  
By analyzing historical customer data, this project builds a predictive model to estimate the likelihood of churn and provide insights into customer behavior.

---

## Dataset
The project uses the **Telco Customer Churn** dataset.

Due to repository size limitations, the dataset is not included in this repository.

You can download it from Kaggle:
https://www.kaggle.com/datasets/binaryhack/churn-prediction

After downloading, place the CSV file in the same directory as the notebook before running it.

---

## Approach
The project follows a complete machine learning workflow:

1. Data loading and inspection  
2. Data cleaning and preprocessing  
3. Encoding categorical features  
4. Train-test split to avoid overfitting  
5. Model training using Logistic Regression  
6. Model evaluation using accuracy, precision, recall, and F1-score  
7. Identification and removal of data leakage features  

Special care was taken to remove target-related features that could lead to unrealistically high performance.

---

## Model Used
- **Logistic Regression**

This model was chosen for its interpretability and effectiveness in binary classification problems such as churn prediction.

---

## Results
- **Accuracy:** ~80%  
- **Recall (Churn class):** ~57%

The results demonstrate that the model is able to identify a significant portion of customers who are likely to churn, while maintaining good overall predictive performance.

---

## Key Insights
- Customers with certain contract types and billing patterns show higher churn tendencies  
- Removing data leakage features is critical for obtaining realistic model performance  
- Recall is an important metric in churn prediction, as missing churned customers can be costly for businesses  

---

## Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Jupyter Notebook  

---

## Conclusion
This project demonstrates an end-to-end machine learning pipeline for churn prediction, from raw data processing to model evaluation.  
The approach can be extended with additional feature engineering or alternative models to further improve performance.

