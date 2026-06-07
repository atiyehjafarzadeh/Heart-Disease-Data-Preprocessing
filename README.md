🫀 Cardiovascular Data Cleaning & Machine Learning Pipeline
📌 Project Overview

This project covers an end-to-end pipeline for data cleaning, preprocessing, feature engineering, and machine learning modeling on a cardiovascular healthcare dataset.

The goal is to transform raw medical data into a high-quality dataset and build a predictive model for cardiovascular disease classification.

📊 Dataset Description

The dataset includes anonymized patient records with:

Demographic information
Clinical measurements
Lifestyle factors
Medical history
Cardiovascular disease label
Follow-up records
🎯 Project Goals
Clean and validate raw healthcare data
Handle missing and inconsistent values
Normalize categorical variables
Engineer meaningful features
Train a machine learning model
Evaluate predictive performance
🧹 Data Preprocessing
Missing Value Handling
Imputed education level
Completed missing diabetes and smoking values
Fixed missing or invalid visit dates
Data Validation
Age range validation
Maximum heart rate correction
Binary feature normalization (e.g., alcoholism, smoking)
Categorical Normalization
Standardized arrhythmia categories
Corrected valvular disease labels
Unified education encoding
Date Processing
Converted date fields to datetime format
Computed follow-up duration
Handled invalid date entries
⚙️ Feature Engineering
Follow-up duration (days)
Ordinal encoding for ordered variables
One-hot encoding for nominal variables
Derived clinical indicators
🤖 Machine Learning Model

A Decision Tree Classifier was trained on the cleaned dataset.

📈 Model Performance

Training Accuracy: 0.9459
Testing Accuracy: 0.9541
📊 Classification Report
| Class | Precision | Recall | F1-score | Support |
| ----- | --------- | ------ | -------- | ------- |
| 0     | 0.92      | 0.99   | 0.96     | 1993    |
| 1     | 0.99      | 0.92   | 0.95     | 2013    |

Overall Accuracy: 0.95

Macro Avg F1-score: 0.95
Weighted Avg F1-score: 0.95
🛠️ Technologies Used
Python 🐍
Pandas
NumPy
Matplotlib
Scikit-learn
Jupyter Notebook
📤 Output

Final cleaned dataset:

final_clean.csv

🔁 Workflow Summary
Load raw dataset
Exploratory Data Analysis (EDA)
Data cleaning & validation
Feature engineering
Train-test split
Train Decision Tree model
Evaluate performance
Export final dataset

💡 Key Insight

The Decision Tree model achieved high test accuracy (~95%), indicating that the preprocessing and feature engineering significantly improved the dataset quality and model learnability.
