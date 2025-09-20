📊 Student Performance Prediction

This project analyzes the Student Performance Factors dataset and applies different regression models to predict exam scores based on study-related factors. The goal is to explore how machine learning can uncover insights into academic performance.

📌 Project Overview

The dataset contains features such as:

📚 Study Hours

😴 Sleep Hours

📅 Attendance

🧠 Previous Scores

🍏 Healthy Habits (exercise, diet, etc.)

Using these features, multiple regression techniques were applied to predict Exam Scores.

🔑 Key Tasks
✅ Mandatory Tasks

Data Preprocessing

Load dataset using Pandas

Check for missing values

Split dataset into train and test sets

Linear Regression

Predict exam score using study hours

Evaluate performance using:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R² Score

Visualization

Scatter plot of study hours vs exam score

Regression line visualization

⭐ Bonus Tasks

Polynomial Regression

Fit polynomial features to capture non-linear relationships

Visualize curve fitting with actual data

Multiple Linear Regression

Use additional features (attendance, sleep hours, previous scores, etc.)

Compare results with simple regression

Performance Comparison

Compare MAE, MSE, RMSE, and R² across models

🛠️ Tech Stack

Python

Pandas (for data handling)

Matplotlib (for visualization)

Scikit-learn (for regression models & evaluation)

📈 Results

Linear Regression works well for simple relationships (Study Hours → Exam Score).

Polynomial Regression improves predictions when the relationship is non-linear.

Multiple Linear Regression gives better accuracy when considering multiple factors.


Install dependencies:

pip install pandas matplotlib scikit-learn


Run the Jupyter Notebook or Python script to see results.


📌 Future Improvements

Try advanced models (Random Forest, Gradient Boosting).

Add more student lifestyle factors.

Deploy as a web app for interactive predictions.