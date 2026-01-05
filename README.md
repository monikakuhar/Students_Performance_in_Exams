# Student Exam Score Prediction using Linear Regression

## Project Overview
This project predicts a student’s **Math exam score** based on demographic, educational, and preparation-related features.  
It demonstrates a **complete Machine Learning regression workflow**, from data preprocessing to model evaluation.

The goal is to understand **how different factors influence student performance** and build a reliable predictive model.

---

## Skills & Tools Used
- Python
- Pandas & NumPy
- Data Cleaning & Preprocessing
- Encoding Categorical Variables
- Exploratory Data Analysis (EDA)
- Linear Regression
- Model Evaluation (MAE, MSE, RMSE, R²)
- Data Visualization (Matplotlib, Seaborn)

---

## Problem Statement
Predict the **Math Score** of a student using features such as:
- Gender
- Race/Ethnicity
- Parental level of education
- Lunch type
- Test preparation course
- Reading score
- Writing score

This is a **regression problem**, where the target variable is continuous.

---

## Dataset Information
- **Source:** Kaggle  
- **Dataset Name:** Students Performance in Exams  
- **Link:** https://www.kaggle.com/datasets/spscientist/students-performance-in-exams  

### Target Variable
- `math score`

---

## Workflow
1. Load and explore the dataset  
2. Check for missing values  
3. Encode categorical variables  
4. Select relevant features  
5. Split data into training and testing sets  
6. Train a Linear Regression model  
7. Evaluate model performance  
8. Interpret feature importance  
9. Visualize predictions  

---

## Model Evaluation Metrics
The model is evaluated using:
- **MAE (Mean Absolute Error)** – Average prediction error
- **MSE (Mean Squared Error)** – Penalizes larger errors
- **RMSE (Root Mean Squared Error)** – Error in original scale
- **R² Score** – Explains how well the model fits the data

---

## Key Insights
- Test preparation course has a strong positive impact on scores
- Reading and writing scores are highly correlated with math performance
- Lunch type and parental education level influence student outcomes
