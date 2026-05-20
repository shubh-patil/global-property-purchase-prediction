# Global Property Purchase Decision Prediction

## Overview

This project focuses on predicting whether a buyer will purchase a property based on financial, demographic, and property-related factors.

Using a global real-estate dataset containing 25,000 records across multiple countries and cities, the project performs:

- Exploratory Data Analysis (EDA)
- Data Cleaning & Preprocessing
- Feature Engineering
- Multicollinearity Handling
- Logistic Regression Modeling
- Hyperparameter Tuning
- Model Evaluation

The target variable is:

- `Decision`
  - `1` → Property Purchased
  - `0` → Property Not Purchased

---

# Dataset Description

The dataset includes:

### Property Features
- Property Type
- Furnishing Status
- Country
- City
- Price
- Amenities
- Property Size

### Financial Features
- Buyer Income
- Loan Information
- EMI
- Expenses

### Buyer Perception Features
- Satisfaction Ratings
- Neighborhood Ratings
- Connectivity Ratings

Dataset size:
- 25,000 records
- Global coverage across 20+ countries

---

# Project Workflow

## 1. Exploratory Data Analysis
Performed:
- Missing value analysis
- Duplicate handling
- Country-wise price analysis
- Property type analysis
- Categorical variable exploration
- Encoding analysis

---

## 2. Data Preprocessing
Steps included:
- Removing unnecessary columns
- Encoding categorical variables
- Handling multicollinearity
- Feature scaling using StandardScaler

---

## 3. Model Building

### Algorithm Used
- Logistic Regression

### Validation Techniques
- Train-Test Split
- Cross Validation
- GridSearchCV
- RandomizedSearchCV

---

# Model Evaluation

Evaluation metrics used:
- Accuracy Score
- Confusion Matrix
- Classification Report
- Probability Predictions

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# Key Learnings

This project helped in understanding:
- Real-world preprocessing workflows
- Classification modeling
- Feature correlation and multicollinearity
- Hyperparameter tuning
- Model evaluation techniques

---

# Repository Structure


├── notebooks/
├── data/
├── images/
├── README.md
├── requirements.txt


        ### Phase 2 (Planned)
        - Decision Tree
        - Random Forest
        - XGBoost
        - Model Comparison Dashboard
        
        ### Phase 3 (Planned)
        - Streamlit Deployment
        - Real-time Prediction Interface
        - SHAP Explainability
