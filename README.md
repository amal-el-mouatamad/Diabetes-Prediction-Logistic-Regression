# 🩺 Diabetes Prediction using Logistic Regression

## 📌 Project Overview

This project predicts whether a patient has diabetes using the Pima Indians Diabetes Dataset and a Logistic Regression machine learning model.

The project includes the complete machine learning workflow, from data preprocessing to model evaluation.

---

## 🎯 Objectives

- Explore the dataset
- Handle missing values
- Detect and treat outliers using the IQR method
- Split the dataset into training and testing sets
- Standardize features
- Train a Logistic Regression model
- Evaluate model performance

---

## 📂 Dataset

- Dataset: Pima Indians Diabetes Dataset
- Samples: 768
- Features: 8
- Target: Outcome (0 = No Diabetes, 1 = Diabetes)

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## ⚙️ Machine Learning Workflow

1. Load Dataset
2. Exploratory Data Analysis (EDA)
3. Data Cleaning
4. Replace invalid values (0 → NaN)
5. Handle Missing Values
6. Detect and Treat Outliers (IQR)
7. Train-Test Split
8. Feature Scaling (StandardScaler)
9. Logistic Regression
10. Model Evaluation

---

## 📈 Results

**Accuracy:** **79.65%**

### Confusion Matrix

```
[[132 14]
 [ 33 52]]
```

### Classification Report

| Class | Precision | Recall | F1-score |
|------|----------:|-------:|---------:|
| 0 | 0.80 | 0.90 | 0.85 |
| 1 | 0.79 | 0.61 | 0.69 |

---

## 📁 Project Structure

```
Diabetes-Prediction-Logistic-Regression
│
├── Diabetes_Prediction.ipynb
├── README.md
├── requirements.txt
└── diabetes.csv``
```

---

## 👩‍💻 Author

**Amal El Mouatamad**

AI & Data Analytics Student  
ISTA NTIC Rabat
