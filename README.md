# ml-classification-project
ML Classification Project using Titanic Dataset

## 📌 Project Overview
This project focuses on building and evaluating supervised machine learning
classification models to predict passenger survival on the Titanic dataset.

Two different algorithms were implemented and compared:
- Logistic Regression
- Random Forest Classifier

The goal is to evaluate model performance using standard classification metrics
and select the best-performing model.

---

## 📂 Dataset
- Dataset: Titanic Dataset
- Source: Publicly available dataset
- Target variable: `Survived`

---

## ⚙️ Technologies Used
- Python 3.11
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 🧹 Data Preprocessing
- Handled missing values:
  - Age: filled with median
  - Embarked: filled with mode
- Converted categorical variables using one-hot encoding
- Performed train-test split (80% train, 20% test)
- Applied feature scaling using StandardScaler

---

## 🤖 Models Implemented
### 1. Logistic Regression
A baseline linear classification model used for comparison.

### 2. Random Forest Classifier
An ensemble learning method that provided better overall performance.

---

## 📊 Evaluation Metrics
The following metrics were used to evaluate both models:
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score

A confusion matrix was plotted for visual evaluation.

---

## 🏆 Results Summary
The Random Forest model outperformed Logistic Regression with higher accuracy
and ROC-AUC score. Therefore, Random Forest was selected as the final model.

---

## ▶️ How to Run
1. Clone the repository
2. Install dependencies:
