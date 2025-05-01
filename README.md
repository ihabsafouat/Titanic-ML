# 🛳️ Titanic - Machine Learning from Disaster

A classic introductory data science project based on predicting the survival of passengers aboard the Titanic. This project applies supervised machine learning techniques to classify whether a given passenger survived the disaster.

## 📊 Project Overview

This project uses the Titanic dataset from [Kaggle](https://www.kaggle.com/competitions/titanic) to:

- Perform Exploratory Data Analysis (EDA)
- Handle missing data and feature engineering
- Build predictive models to classify survival
- Evaluate and compare model performance

## 📁 Dataset

The dataset contains passenger information like age, sex, ticket class, and whether they survived:

- `train.csv`: Training data with labels (survived)
- `test.csv`: Test data without labels
- `gender_submission.csv`: A sample submission file

## 🔧 Technologies Used

- Python (3.8+)
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## 🔍 Exploratory Data Analysis

Key insights:
- Females were more likely to survive than males
- Passengers in higher classes (1st class) had better survival odds
- Children had better survival rates

Visualizations included:
- Survival rates by gender and class
- Age distribution and missing values
- Correlation heatmaps

## ⚙️ Feature Engineering

- Imputed missing `Age` using median by class
- Extracted titles (Mr, Mrs, etc.) from names
- Converted `Sex`, `Embarked`, and `Title` to categorical features
- Created `FamilySize` feature
- Dropped irrelevant features (`Ticket`, `Cabin`)

## 🤖 Models Used

- Logistic Regression
- Random Forest
- Gradient Boosting (optional: XGBoost)
- Support Vector Machine

## 📈 Evaluation

Used cross-validation and accuracy/F1-score metrics to evaluate models.

| Model              | Accuracy |
|--------------------|----------|
| Logistic Regression| 0.80     |
| Random Forest      | 0.83     |
| XGBoost            | 0.85     |

## 📝 Submission

Predicted labels for the test dataset and submitted to Kaggle for evaluation.

## 🧠 Learnings

- Importance of preprocessing and handling missing values
- Impact of feature engineering on model performance
- Hands-on experience with classification models and Kaggle workflow

## 🚀 How to Run

1. Clone the repo
2. Install dependencies: `pip install -r requirements.txt`
3. Run Jupyter Notebook: `jupyter notebook Titanic_ML.ipynb`

## 📎 Resources

- [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic)
- [Scikit-learn Documentation](https://scikit-learn.org/)

---
