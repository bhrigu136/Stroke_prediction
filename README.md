# Stroke Prediction ML Web App

A full-stack machine learning web app that predicts the risk of stroke based on user health data. Built using React (frontend) and Flask (backend), with a model trained on a real-world dataset from Kaggle.

# Project Overview

I used a real-world dataset from Kaggle, containing various health indicators such as:

- Age
- Gender
- Hypertension
- Heart disease
- Smoking status
- Work type, and more

The main goal was to predict the chances of a stroke using these parameters.

---

## 🛠️ Workflow Summary

1. Data Preprocessing:
   - Handled missing values and encoded categorical features.
   - Used SMOTE to handle class imbalance (only ~5% stroke cases).

2. Model Training:
   - Compared Logistic Regression, Random Forest, and LDA.
   - Selected Linear Discriminant Analysis (LDA) based on better AUC performance.

3. Backend (Flask):
   - Created a RESTful API that accepts user data and returns predictions.

4. Frontend (React):
   - Built a user-friendly interface where users input health data and get instant results.

---

## 🔍 Key Learnings

- Practical use of EDA, data cleaning, and SMOTE.
- Choosing the right evaluation metrics like AUC for imbalanced data.
- Model deployment via Flask API.
- Frontend-backend integration using React and Flask.
  
---

This project gave me hands-on experience in building, evaluating, and deploying ML models, while also improving my skills in frontend and backend development.
