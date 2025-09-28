🌲 Forest Cover Type Classification (Internship Task 3 – Elevvo Pathways)
📌 Overview

This project is part of my internship at Elevvo Pathways (Task 3).
The goal was to work on the Forest Cover Type dataset (UCI Repository) and build machine learning models to predict the type of forest cover based on cartographic variables.

The dataset contains 581,012 instances and 54 features, with each observation classified into one of 7 forest cover types.

📂 Dataset

Source: UCI Machine Learning Repository – Covertype Dataset

Features: 54 cartographic and environmental attributes (elevation, slope, soil type, etc.)

Target: Forest cover type (1–7)

⚙️ Approach

Data Preprocessing

Loaded the dataset and split into training & test sets

Scaled continuous features for better model performance

Models Implemented

Random Forest Classifier

XGBoost Classifier

Evaluation Metrics

Accuracy

Confusion Matrix

📊 Results

Random Forest Accuracy: ~94%

XGBoost Accuracy: ~95%

XGBoost performed slightly better, with faster convergence and better handling of feature importance.

🛠️ Technologies Used

Python

Pandas

Scikit-learn

XGBoost

💡 Key Learnings

Handling large-scale structured datasets

Building multi-class classification models

Comparing ensemble learning techniques (Random Forest vs XGBoost)

Feature importance analysis for real-world environmental data
