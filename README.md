# ❤️ Heart Disease Prediction System

A Machine Learning based system that predicts the likelihood of heart disease using **Logistic Regression**.  
The model is trained on the **UCI Heart Disease Dataset (Kaggle version)** containing medical attributes such as age, cholesterol level, blood pressure, and other health indicators.

This project demonstrates how **machine learning can assist in early detection of cardiovascular diseases** by analyzing patient health data.

---

## 📌 Project Overview

Heart disease is one of the leading causes of death worldwide. Early prediction can help in timely medical intervention and prevention.

This project applies **Logistic Regression**, a supervised machine learning algorithm, to classify whether a person is likely to have heart disease based on medical parameters.

The model is trained using the **UCI Heart Disease dataset**, which contains **303 patient records with 13 input features**.

---

## 🧠 Machine Learning Model

**Algorithm Used**

- Logistic Regression

**Why Logistic Regression?**

- Suitable for **binary classification problems**
- Provides **interpretable probability outputs**
- Efficient for structured datasets

**Prediction Output**

- `0` → No Heart Disease  
- `1` → Presence of Heart Disease

---

## 📊 Dataset Information

**Dataset Source**

- UCI Machine Learning Repository  
- Kaggle version of the dataset

**Total Records:** 303  

**Total Input Features:** 13  

**Example Features**

- Age  
- Sex  
- Chest Pain Type  
- Resting Blood Pressure  
- Cholesterol  
- Fasting Blood Sugar  
- Resting ECG  
- Maximum Heart Rate Achieved  
- Exercise Induced Angina  
- ST Depression (Oldpeak)  
- Slope of Peak Exercise ST Segment  
- Number of Major Vessels  
- Thalassemia  

**Target Variable**

- Heart Disease Presence (`0` or `1`)

---

## 🛠️ Tech Stack

- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

---

## ⚙️ Project Workflow

1. Data Collection  
2. Data Preprocessing  
3. Exploratory Data Analysis  
4. Feature Selection  
5. Model Training using Logistic Regression  
6. Model Evaluation  
7. Prediction System  

---

## 📈 Model Evaluation

Evaluation metrics used:

- Accuracy Score
- Confusion Matrix
- Classification Report

The model analyzes medical attributes to classify whether a patient is at risk of heart disease.

---

## 📂 Project Structure

```
Heart-Disease-Prediction
│
├── dataset
│   └── heart.csv
│
├── notebook
│   └── heart_disease_analysis.ipynb
│
├── model
│   └── logistic_regression_model.pkl
│
├── prediction_system.py
│
└── README.md
```

---

## 🔮 Future Improvements

- Deploy the model as a **web application**
- Use **advanced machine learning algorithms**
- Integrate **larger medical datasets**
- Build an **interactive dashboard**

---

## 📚 References

- UCI Machine Learning Repository – Heart Disease Dataset  
- Kaggle Heart Disease Dataset  
- Scikit-learn Documentation  

---

## 👨‍💻 Author

**Anubhav Srivastava**  
B.Tech Computer Science & Engineering
