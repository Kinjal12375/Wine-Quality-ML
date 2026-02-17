#  Wine Quality ML Mini Project

An end-to-end supervised machine learning pipeline for wine quality classification, incorporating exploratory data analysis, feature engineering, model evaluation, and hyperparameter optimization.

---

## Project Overview
This project aims to predict whether a wine sample is GOOD or BAD based on its physicochemical properties using classification algorithms.

The original wine quality score was converted into a binary target:
- GOOD (1) → Quality ≥ 7  
- BAD (0) → Quality < 7  

---

## Dataset Features
- Fixed Acidity  
- Volatile Acidity  
- Citric Acid  
- Residual Sugar  
- Chlorides  
- Free Sulfur Dioxide  
- Total Sulfur Dioxide  
- Density  
- pH  
- Sulphates  
- Alcohol  
- Quality (Target)

---

## Project Workflow
- Data Loading & Exploration  
- Statistical Analysis  
- Correlation Matrix Analysis  
- Target Variable Engineering  
- Train-Test Split  
- Model Training  
- Feature Scaling  
- Model Comparison  
- Hyperparameter Tuning (GridSearchCV)  
- Feature Importance Analysis  

---

##  Models Implemented
- Logistic Regression  
- K-Nearest Neighbors  
- Decision Tree Classifier  

---

## Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  
- ROC-AUC Curve  

---

## Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Google Colab  

---

##  Key Insights
- Alcohol content shows strong positive correlation with wine quality.  
- Feature scaling significantly improved KNN performance.  
- Decision Tree handled non-linear relationships effectively.  

---
## How to Run

1. Clone repository  
2. Install packages: `pip install -r requirements.txt`  
3. Open `Wine_Quality_Classification.ipynb` in Colab or Jupyter  

