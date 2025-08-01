# 🫀 Heart Disease Prediction using Logistic Regression

This project uses **Logistic Regression** to predict the likelihood of heart disease based on various medical attributes. The goal is to build a simple, interpretable machine learning model that can assist in early diagnosis and support clinical decision-making.

---

# 📌 Problem Statement

Heart disease is a major cause of mortality worldwide. Detecting it early can lead to timely intervention and save lives. This project aims to predict whether a patient has heart disease using features like age, blood pressure, cholesterol, and more.

---

## 📊 Dataset

- **Source**: UCI Heart Disease Dataset  
- **Total Samples**: 303  
- **Target Variable**: `target` — 0 (no heart disease), 1 (heart disease present)

---

## 🔍 Features Used

| Feature      | Description                            |
|--------------|----------------------------------------|
| age          | Age of the patient                     |
| sex          | Gender (1 = male; 0 = female)          |
| cp           | Chest pain type                        |
| trestbps     | Resting blood pressure                 |
| chol         | Serum cholesterol                      |
| fbs          | Fasting blood sugar > 120 mg/dl        |
| restecg      | Resting electrocardiographic results   |
| thalach      | Maximum heart rate achieved            |
| exang        | Exercise-induced angina                |
| oldpeak      | ST depression induced by exercise      |
| slope        | Slope of the peak exercise ST segment  |
| ca           | Number of major vessels colored        |
| thal         | Thalassemia                            |

---

## 🧠 Model Overview

- **Algorithm**: Logistic Regression  
- **Preprocessing**: Standardization using `StandardScaler`  
- **Train-Test Split**: 90:10  
- **Performance Metrics**: Accuracy, F1-Score

---


## 📊 Model Performance

The model was evaluated using **Accuracy** and **F1 Score** on both the training and testing datasets.

| **Metric**   | **Training Set** | **Test Set** |
|--------------|------------------|--------------|
| Accuracy     | 85.6%            | 74.1%        |
| F1 Score     | 87.4%            | 76.4%        |

- ✅ **Accuracy**: Measures the percentage of correctly predicted instances.
- 🎯 **F1 Score**: Harmonic mean of precision and recall, useful for handling class imbalance.


## 🚀 How to Run

 1. Clone the Repository
 2. Install Dependencies
 3. Run the notebook


## 👩‍💻 Author
Tanya Chauhan








 
