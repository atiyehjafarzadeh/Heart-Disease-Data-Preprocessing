# Cardiovascular Data Cleaning and Preprocessing

## Overview

This project focuses on cleaning, validating, transforming, and preparing a cardiovascular healthcare dataset for machine learning applications.

The workflow includes data quality assessment, missing value handling, categorical value normalization, feature engineering, data validation, and dataset transformation.

## Dataset

The dataset contains cardiovascular patient information including:

* Demographic attributes
* Clinical measurements
* Medical history
* Heart disease indicators
* Follow-up records

## Project Objectives

* Identify data quality issues
* Handle missing values
* Correct invalid and inconsistent records
* Normalize categorical variables
* Engineer useful features
* Prepare data for machine learning models

## Data Cleaning Tasks

### Missing Value Handling

* Education level imputation
* Diabetes value completion
* Smoking value completion
* Visit date correction

### Data Validation

* Age range validation
* Maximum heart rate validation
* Alcoholism value correction
* Binary feature normalization

### Categorical Data Cleaning

* Arrhythmia category normalization
* Valvular disease category correction
* Education level standardization

### Date Processing

* Date conversion to datetime format
* Follow-up duration calculation
* Invalid date handling

### Feature Engineering

* Follow-up day calculation
* Ordinal encoding
* One-hot encoding for nominal features
  
### 🤖 Machine Learning Model (Decision Tree Classifier)

After completing data cleaning and preprocessing, a Decision Tree Classifier was trained to predict cardiovascular disease.

The model was evaluated using a train-test split to measure generalization performance on unseen data.

### 📈 Model Performance
Training Accuracy: 0.9459
Testing Accuracy: 0.9541
### 📊 Classification Report
| Class | Precision | Recall | F1-score | Support |
| ----- | --------- | ------ | -------- | ------- |
| 0     | 0.92      | 0.99   | 0.96     | 1993    |
| 1     | 0.99      | 0.92   | 0.95     | 2013    |
### Overall Results
Accuracy: 0.95
Macro Avg F1-score: 0.95
Weighted Avg F1-score: 0.95
### Key Insight

The Decision Tree model achieved strong performance (~95% accuracy), indicating that the data preprocessing and feature engineering steps significantly improved the quality and separability of the dataset.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

## Output

The final cleaned dataset is exported as:

```text
final_clean.csv
```

## Workflow

1. Load raw dataset
2. Perform exploratory data analysis
3. Detect data quality issues
4. Clean and validate records
5. Transform categorical variables
6. Engineer new features
7. Prepare dataset for machine learning
8. Export cleaned dataset

## Author

Atiyeh 
