# 💳 Credit Scoring Model

A Machine Learning project developed as part of the **CodeAlpha Machine Learning Internship**.

## 📌 Project Overview

This project predicts whether a customer is a good or bad credit risk using machine learning classification algorithms. It includes data preprocessing, feature engineering, model training, evaluation, and comparison of multiple models.

---

## 🎯 Objective

Build a classification model that predicts customer credit risk using historical financial data.

---

## 📂 Dataset

**Dataset:** German Credit Dataset

### Features

- Age
- Sex
- Job
- Housing
- Saving Accounts
- Checking Account
- Credit Amount
- Duration
- Purpose

### Target Variable

- Good Credit (1)
- Bad Credit (0)

---

## 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook
- Git
- GitHub

---

## ⚙️ Project Workflow

1. Import Libraries
2. Load Dataset
3. Exploratory Data Analysis (EDA)
4. Data Cleaning
5. Feature Engineering
6. Label Encoding
7. Train-Test Split
8. Feature Scaling
9. Model Training
10. Model Evaluation
11. Model Comparison
12. Best Model Selection

---

## 🤖 Machine Learning Models

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

## 📊 Model Performance

| Model | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|--------|---------:|----------:|--------:|---------:|--------:|
| Logistic Regression | 0.665 | 0.713 | 0.871 | 0.785 | 0.662 |
| Decision Tree | 0.715 | 0.768 | 0.850 | 0.807 | 0.704 |
| **Random Forest** | **0.745** | **0.783** | **0.879** | **0.828** | **0.747** |

---

## 🏆 Best Model

Random Forest achieved the best overall performance among all three models.

- Highest Accuracy
- Highest Precision
- Highest Recall
- Highest F1 Score
- Highest ROC-AUC

Therefore, Random Forest was selected as the final model.

---

## 📁 Project Structure

```
Credit-Scoring-Model/

│── dataset/
│     └── german_credit_data.csv

│── notebook/
│     └── Credit_Scoring_Model.ipynb

│── images/

│── README.md

│── requirements.txt
```

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone <repository-link>
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open the notebook

```bash
jupyter notebook
```

4. Run all cells.

---

## 🚀 Future Improvements

- Improve model accuracy using hyperparameter tuning
- Perform cross-validation
- XGBoost Classifier
- LightGBM
- CatBoost
- Model Deployment using Flask or Streamlit

---

## 👨‍💻 Author

**Shubham Singh Rajput**

AI & Machine Learning Intern

CodeAlpha Machine Learning Internship

---

⭐ If you found this project useful, consider giving it a Star.