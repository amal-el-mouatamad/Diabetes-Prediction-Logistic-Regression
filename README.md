<img width="1022" height="661" alt="Screenshot 2026-07-01 213053" src="https://github.com/user-attachments/assets/62c8e610-6b6b-4999-a2dd-ac04e1c88989" />
<img width="532" height="447" alt="Screenshot 2026-07-01 213101" src="https://github.com/user-attachments/assets/238a347f-926c-41c3-baf7-8d59b4da57f6" />
<img width="486" height="452" alt="Screenshot 2026-07-01 213110" src="https://github.com/user-attachments/assets/6968cb76-b373-4f5e-8c43-c58715f11e80" />
# 🩺 Diabetes Prediction using Logistic Regression

## 📌 Présentation du projet

Ce projet permet de prédire si un patient est atteint de diabète à l'aide du jeu de données Pima Indians Diabetes Dataset et d'un modèle de Régression Logistique (Logistic Regression).

Le projet couvre l'ensemble du processus de Machine Learning, depuis le prétraitement des données jusqu'à l'évaluation des performances du modèle.

---

## 🎯 Objectifs

Explorer le jeu de données.
Identifier et traiter les valeurs manquantes.
Détecter et traiter les valeurs aberrantes (méthode IQR).
Diviser les données en ensembles d'entraînement et de test.
Normaliser les variables avec StandardScaler.
Entraîner un modèle de Régression Logistique.
Évaluer les performances du modèle.

---

## 📂 Jeu de données

Nom : Pima Indians Diabetes Dataset
Nombre d'observations : 768
Nombre de variables : 8
Variable cible : Outcome
0 : Patient non diabétique
1 : Patient diabétique

---

## 🛠 Technologies utilisées

Python
Pandas
NumPy
Matplotlib
Scikit-learn

---

## ⚙️ Processus de Machine Learning

Chargement du jeu de données
Analyse exploratoire des données (EDA)
Nettoyage des données
Remplacement des valeurs invalides (0 → NaN)
Traitement des valeurs manquantes
Détection et traitement des valeurs aberrantes (IQR)
Division des données (Train/Test Split)
Normalisation des variables (StandardScaler)
Entraînement du modèle de Régression Logistique
Évaluation des performances

---

## 📈 Résultats

Précision (Accuracy) : 79,65 %

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

## 📁 Structure du projet

Diabetes-Prediction-Logistic-Regression
│
├── Diabetes_Prediction.ipynb
├── README.md
├── requirements.txt
└── diabetes.csv
```

---

## 👩‍💻 Author

**Amal El Mouatamad**

AI & Data Analytics Student  
ISTA NTIC Rabat
