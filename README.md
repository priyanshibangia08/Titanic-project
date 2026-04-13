# Titanic-project
# Kaggle - Titanic: Machine Learning from Disaster

This repository contains a comprehensive solution for the [Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic) competition on Kaggle. The goal is to predict which passengers survived the shipwreck using machine learning techniques.

## 📌 Project Overview
The Titanic dataset is a classic binary classification problem. This project walks through the entire data science pipeline, from initial data exploration to generating final predictions for submission.

The solution is divided into three main sections:
1. **Exploratory Data Analysis (EDA) & Feature Engineering**: Understanding data distributions and preparing features.
2. **Modeling and Evaluation**: Training and comparing machine learning models.
3. **Submitting Predictions**: Generating the final results for Kaggle.

## 🛠️ Technologies Used
- **Environment**: Google Colab / Jupyter Notebook
- **Libraries**:
  - `pandas` & `numpy` for data manipulation.
  - `matplotlib` & `seaborn` for data visualization.
  - `scikit-learn` for preprocessing, model selection, and evaluation.
  - `xgboost` for advanced gradient boosting.

## 📂 Dataset
The dataset includes two primary files:
- `train.csv`: Contains passenger data and survival labels for training models.
- `test.csv`: Contains passenger data without survival labels, used for final evaluation.

### Key Features
- **Survived**: 0 = No, 1 = Yes (Target)
- **Pclass**: Ticket class (1st, 2nd, 3rd)
- **Sex**: Gender of the passenger
- **Age**: Age in years
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Fare**: Passenger fare
- **Embarked**: Port of embarkation (C, Q, S)

## 🚀 How to Run
1. **Clone the repository**:
   ```bash
   git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
