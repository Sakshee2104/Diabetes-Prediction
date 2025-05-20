# 🩺 Diabetes Prediction using Machine Learning

This project implements a machine learning model to predict diabetes risk based on key health indicators. The model uses the **Pima Indians Diabetes Dataset** and applies a **Random Forest Classifier**, achieving high accuracy and balanced predictions. The goal is to aid early diagnosis and reduce reliance on costly traditional clinical methods.

---

## 🧠 Motivation

Diabetes is a chronic illness affecting millions globally. Early detection is critical in preventing complications. Traditional diagnosis can be expensive and inaccessible. This project presents a **cost-effective, data-driven solution** using machine learning to assist healthcare professionals in predicting diabetes risk.

---

## 📊 Dataset

- **Name**: Pima Indians Diabetes Dataset  
- **Source**: [Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Records**: 768 samples  
- **Features**:
  - Pregnancies
  - Glucose
  - Blood Pressure
  - Skin Thickness
  - Insulin
  - BMI
  - Diabetes Pedigree Function
  - Age
  - Outcome (0 = Non-Diabetic, 1 = Diabetic)

---

## ⚙️ Methodology

1. **Data Preprocessing**
   - Handling missing values
   - Normalizing numeric features
   - Train-test split

2. **Model Selection**
   - Algorithm: Random Forest Classifier
   - Hyperparameter tuning using GridSearchCV

3. **Evaluation Metrics**
   - Accuracy
   - Precision
   - Recall
   - F1-Score
   - ROC-AUC Curve
   - Confusion Matrix
   - Feature Importance Analysis

---

## 📈 Results

- **Model Accuracy**: ~85%
- **Key Features**: Glucose, BMI, Age
- **Confusion Matrix**: Balanced classification between diabetic and non-diabetic cases
- **Feature Importance**: Glucose and BMI are the top predictors

---
