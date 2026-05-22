<div align="center">

# 🚢 Titanic Survival Prediction
### Machine Learning · Classification · Logistic Regression

<br>

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

<br>

> *"In the middle of chaos, patterns still survive."*

<br>

</div>

---

## 📌 Objective

Build a **machine learning classification model** capable of predicting whether a passenger survived the Titanic disaster using passenger information such as:

- Age
- Gender
- Passenger Class
- Fare
- Cabin Information
- Embarkation Port

This project focuses on:

- Data cleaning & preprocessing
- Feature encoding
- Model training
- Performance evaluation using classification metrics

---

## 📂 Dataset

| Property | Detail |
|----------|--------|
| **Name** | Titanic Dataset |
| **Source** | [Kaggle Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset) |
| **Rows** | 891 passengers |
| **Target Variable** | `Survived` |
| **Problem Type** | Binary Classification |

---

## 🧠 Approach

```text
Raw Titanic Passenger Data
   │
   ▼
Data Cleaning
   │  ├── Handle missing Cabin values
   │  ├── Fill missing Age values using median
   │  └── Fill missing Embarked values using mode
   │
   ▼
Feature Encoding
   │  ├── Encode Sex column
   │  ├── Encode Embarked column
   │  └── Encode Cabin column
   │
   ▼
Remove Unnecessary Columns
   │  ├── PassengerId
   │  ├── Name
   │  └── Ticket
   │
   ▼
Train-Test Split
   │
   ▼
Model Training
   │  └── Logistic Regression
   │
   ▼
Evaluation
   │  ├── Accuracy Score
   │  ├── Confusion Matrix
   │  └── Classification Report
```

---

## 📊 Results

| Metric | Score |
|--------|-------|
| **Accuracy** | **80.44%** |

> 🎯 The Logistic Regression model achieved approximately **80% prediction accuracy** on unseen test data.

---

## 🔍 Key Findings

- Female passengers had significantly higher survival chances
- Passenger class strongly influenced survival probability
- Higher fares were often associated with better survival rates
- Missing values can be handled effectively using statistical imputation techniques

---

## 📁 Repository Structure

```text
Titanic-Survival-Prediction/
│
├── Titanic_Project.ipynb      # Full notebook with preprocessing & model training
├── Titanic-Dataset.csv        # Dataset used in the project
└── README.md                  # Project documentation
```

---

## ⚙️ Installation & Usage

```bash
# 1. Clone the repository
git clone https://github.com/Faraz-jehangiri/Titanic-Survival-Prediction.git

# 2. Move into the project folder
cd Titanic-Survival-Prediction

# 3. Install required libraries
pip install pandas numpy scikit-learn jupyter

# 4. Launch Jupyter Notebook
jupyter notebook
```

---

## 🛠️ Tech Stack

- **Python 3.10+**
- **Pandas** — data cleaning & preprocessing
- **NumPy** — numerical operations
- **Scikit-learn** — machine learning & evaluation
- **Jupyter Notebook** — development environment

---

## 👤 Author

**Faraz Jehangiri**  
BS Computer Science — SSUET, Karachi

[![GitHub](https://img.shields.io/badge/GitHub-Faraz--jehangiri-181717?style=flat-square&logo=github)](https://github.com/Faraz-jehangiri)

---

## ⭐ Project Status

✅ Completed  
📚 Beginner Machine Learning Project  
🚢 Classification Model using Logistic Regression

---
