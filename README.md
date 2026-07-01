<img width="1022" height="661" alt="Screenshot 2026-07-01 213053" src="https://github.com/user-attachments/assets/62c8e610-6b6b-4999-a2dd-ac04e1c88989" />
<img width="532" height="447" alt="Screenshot 2026-07-01 213101" src="https://github.com/user-attachments/assets/238a347f-926c-41c3-baf7-8d59b4da57f6" />
<img width="486" height="452" alt="Screenshot 2026-07-01 213110" src="https://github.com/user-attachments/assets/6968cb76-b373-4f5e-8c43-c58715f11e80" />
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
