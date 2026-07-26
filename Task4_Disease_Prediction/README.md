# Heart Disease Prediction using Machine Learning

## 📌 Overview

This project predicts the possibility of heart disease using Machine Learning classification algorithms. The model is trained on the Heart Disease dataset and compares multiple algorithms to identify the best-performing model.

---

## 🎯 Objective

- Predict heart disease based on patient medical data.
- Compare multiple Machine Learning algorithms.
- Save the best-performing model for future predictions.

---

## 📂 Dataset

- Heart Disease Dataset (Kaggle/UCI)
- Features include:
  - Age
  - Sex
  - Chest Pain Type
  - Resting Blood Pressure
  - Cholesterol
  - Fasting Blood Sugar
  - Resting ECG
  - Maximum Heart Rate
  - Exercise Induced Angina
  - Oldpeak
  - Slope
  - CA
  - Thal

**Target Variable**
- **0** = No Heart Disease
- **1** = Heart Disease

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

---

## 🤖 Machine Learning Algorithms

- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)

---

## 📊 Model Performance

| Model | Accuracy |
|--------|---------:|
| Logistic Regression | 79.51% |
| Random Forest | **98.54%** |
| Support Vector Machine (SVM) | 88.78% |

**🏆 Best Model:** Random Forest Classifier

---

## 📁 Project Structure

```text
Task4_Disease_Prediction/
│
├── dataset/
│   └── heart.csv
│
├── notebook/
│   └── Disease_Prediction.ipynb
│
├── model/
│   └── heart_disease_model.pkl
│
├── images/
│   ├── correlation_heatmap.png
│   ├── confusion_matrix.png
│   └── accuracy_comparison.png
│
├── README.md
└── requirements.txt
```

---

## 📈 Results

- Performed data preprocessing and exploratory data analysis.
- Visualized the dataset using charts and heatmaps.
- Trained and compared three Machine Learning models.
- Random Forest achieved the highest accuracy (**98.54%**).
- Saved the trained model using Joblib for future predictions.

---

## 🚀 Future Improvements

- Add XGBoost classifier.
- Build a Streamlit or Flask web application.
- Train on larger medical datasets.

---

## 👨‍💻 Author

**Shubham Singh Rajput**

Aspiring Machine Learning Engineer
