# End-to-End Heart Disease Classification

## Overview
This project builds a machine learning model to classify whether a person has heart disease based on clinical features. It follows an end-to-end pipeline—from data preprocessing and exploratory analysis to model evaluation—enabling accurate predictions and supporting healthcare decision-making.

## Features
- Classification of heart disease using health indicators like age, cholesterol, resting ECG, etc.
- Exploratory Data Analysis (EDA) to uncover trends and feature relationships.
- Evaluation and comparison of multiple machine learning models.
- Visualizations for both data insights and model interpretability.
- Easily extendable for real-world deployment or further research.

## Technologies Used

**Programming Language:**  
- Python

**Libraries:**  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook

## Dataset

- **Source:** [Heart Disease UCI Dataset on Kaggle](https://www.kaggle.com/ronitf/heart-disease-uci)

- **Features:**
  - Age  
  - Sex  
  - Chest Pain Type (cp)  
  - Resting Blood Pressure (trestbps)  
  - Cholesterol (chol)  
  - Fasting Blood Sugar (fbs)  
  - Resting ECG (restecg)  
  - Max Heart Rate (thalach)  
  - Exercise Induced Angina (exang)  
  - ST Depression (oldpeak)  
  - Slope  
  - CA  
  - Thal  
  - Target (0 = No disease, 1 = Disease)

## Results

- Multiple classifiers (Logistic Regression, SVM, Random Forest, etc.) evaluated  
- Best-performing model selected based on accuracy and ROC-AUC  
- Insights visualized for better understanding and explainability

---

## Steps to Run the Project

### 1. Clone the Repository

git clone https://github.com/Anushka-200617/heart_disease_classifier.git
cd heart_disease_classifier

### 2. Install Dependencies
Option A: Using pip
pip install -r requirements.txt

Option B: Using conda (recommended)
conda env create -f environment.yml
conda activate heart_disease_env

### 3. Launch Jupyter Notebook
jupyter notebook

### 4. Run the Notebook
Open end-to-end-heart-disease-classification.ipynb and run all cells in order.





