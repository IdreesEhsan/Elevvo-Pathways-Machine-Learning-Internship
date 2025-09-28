Task 4: Loan Approval Prediction

This project is part of my Elevvo Pathways Internship.
The goal is to build a machine learning model to predict loan approval status based on applicant and financial information.

📂 Dataset

Source: Loan Approval Dataset (Kaggle).

Target Variable: loan_status (Approved / Not Approved).

Features:

Applicant’s education

Employment type

Income

Loan amount

Loan term

CIBIL score

Asset values (residential, commercial, luxury, bank)

⚙️ Libraries Used

pandas → Data manipulation

sklearn → Preprocessing, model training, evaluation

Models:

LogisticRegression

DecisionTreeClassifier

🔑 Steps

Data Preprocessing

Dropped unnecessary ID column.

Encoded categorical variables (education, self_employed, loan_status).

Scaled numerical features with StandardScaler.

Model Training

Trained Logistic Regression with balanced class weights.

Trained Decision Tree Classifier with balanced class weights.

Evaluation

Accuracy

Confusion Matrix

Classification Report

Bonus Task

Extracted Feature Importance from both Logistic Regression and Decision Tree.

📊 Results
🔹 Logistic Regression

Provides interpretability with feature coefficients.

Balanced class weights improved fairness across classes.

🔹 Decision Tree

Captures non-linear relationships.

Feature importance highlights top predictors of loan approval.

🚀 Key Learnings

Importance of preprocessing (encoding + scaling).

Comparing linear vs. tree-based models.

Using feature importance for model interpretability.
