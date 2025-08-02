# 💳 Credit Card Fraud Detection

This project focuses on building a machine learning model to detect fraudulent credit card transactions using data analysis, preprocessing, and classification techniques.

---

## 📌 Objective

To develop a machine learning pipeline that can accurately identify and classify fraudulent transactions from a highly imbalanced dataset.

---

## 📂 Dataset

- **Source:** [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Description:** This dataset contains transactions made by European cardholders in September 2013. It includes **284,807 transactions**, out of which only **492 are frauds** (0.17%).

---

## 🔧 Tools & Technologies

- Python 🐍
- NumPy & Pandas
- Matplotlib & Seaborn
- scikit-learn
- imbalanced-learn (SMOTE)
- Jupyter Notebook / Google Colab

---

## 🧪 Project Pipeline

### 1. Data Loading
- Load the dataset using Pandas
- Check for missing values and data shape

### 2. Exploratory Data Analysis (EDA)
- Visualize class imbalance
- Analyze transaction amount distribution
- Plot correlation matrix

### 3. Data Preprocessing
- Normalize the `Amount` feature
- Drop irrelevant features (`Time`)
- Handle class imbalance using **SMOTE**

### 4. Model Building
- Split the data using `train_test_split`
- Train a **Random Forest Classifier**
- Evaluate using **confusion matrix** and **classification report**

### 5. Feature Importance
- Plot the top 10 features that contribute to fraud detection

---

## 📈 Results

- **Accuracy:** ~100% (on balanced SMOTE data)
- **Model:** RandomForestClassifier
- **Precision/Recall/F1-score:** All 1.00 on test set (with balanced data)

---

## 🖼️ Project Thumbnail

<img width="1024" height="1024" alt="ChatGPT Image Aug 2, 2025, 06_56_30 PM" src="https://github.com/user-attachments/assets/cf29bcd8-080d-4e29-980a-1364cf4f6b32" />


---

## 🏁 How to Run

1. Clone the repo  
   ```bash
  (https://github.com/SurajSingh-Cse/Credit-Card-Fraud-Detection.git)
   cd credit-card-fraud-detection

## Run the notebook or Python script
---
    credit_card_fraud.ipynb (for Jupyter)
---
## Download the dataset from Kaggle and place creditcard.csv in the working directory.
---
**Source:** [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
---


## ✨ Author
---
Suraj Singh


Aspiring Data Analyst | Python & ML Enthusiast



📍 Rudraprayag, Uttarakhand | 🎓 Dev Bhoomi University
