# 🩺 Diabetes Prediction with Explainability & Interpretability

**A Machine Learning Project Focused on Early Diabetes Detection with Transparent Model Insights**  
 – Bosy Ayman, Sama Mohamed, Zeyad Sherif_

---

## 📌 Overview

This repository presents a comprehensive approach to **early and accurate diabetes prediction** using machine learning, enriched by **explainability and interpretability** techniques. Our goal is to develop predictive models that not only achieve high accuracy but also offer **clear, transparent insights** into how decisions are made—critical in the medical domain.

---

## 👥 Team Members

- **Sama Mohamed** – 202201867  
- **Zeyad Sherif** – 202201220  
- **Bosy Ayman** – 202202076  

---

## 🎯 Problem Statement

Diabetes is a **chronic, life-altering condition** that affects millions worldwide. Early detection is essential to avoid severe complications such as cardiovascular diseases and kidney failure. However, traditional diagnostic methods can be time-consuming and inaccessible.

This project aims to build **machine learning-based models** that predict diabetes from basic health indicators, allowing:
- Fast and accurate diagnosis
- Remote healthcare accessibility
- Transparent and explainable predictions

---

## 🛠 Algorithms and Models

Each team member will experiment with different models for comparative analysis and interpretation:

- **Sama Mohamed**:
  - Logistic Regression
  - Neural Network
  - XGBoost

- **Bosy Ayman**:
  - Support Vector Machine (SVM)
  - K-Nearest Neighbors (KNN)
  - Naive Bayes

- **Zeyad Sherif**:
  - Decision Tree
  - Random Forest
  - LightGBM

---

## 📊 Dataset Information

| Attribute                     | Description                                                      |
|------------------------------|------------------------------------------------------------------|
| **Dataset Name**             | Pima Indian Diabetes Database                                     |
| **Source**                   | [Kaggle Link](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database) |
| **Format**                   | CSV (Comma-Separated Values)                                     |
| **Size**                     | 768 rows × 9 columns                                              |
| **Features**                 | Pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, Diabetes Pedigree Function, Age |
| **Target**                   | `Outcome` (0 = Non-diabetic, 1 = Diabetic)                        |

---

## 📚 Reference Papers

### 🧠 Sama Mohamed

1. https://www.mdpi.com/2075-4426/13/3/406  
2. https://www.researchgate.net/publication/353487060_Diabetes_Detection_Using_Machine_Learning_Classification_Methods  
3. https://ieeexplore.ieee.org/abstract/document/9076634

### 🤖 Bosy Ayman

1. https://www.sciencedirect.com/science/article/pii/S1877050918308548  
2. https://link.springer.com/article/10.1186/1472-6947-10-16  
3. https://www.sciencedirect.com/science/article/pii/S1877050922021858

### 🌲 Zeyad Sherif

1. https://www.mdpi.com/1660-4601/19/19/12378  
2. https://www.researchgate.net/publication/350390088_Prediction_of_Diabetes_Disease_Using_Machine_Learning_Model  
3. https://www.frontiersin.org/articles/10.3389/fgene.2018.00515/full

---

## 💡 Explainability Tools Planned

- **SHAP** (Global + Local Interpretability)
- **LIME** (Local Interpretable Model-Agnostic Explanations)
- **Partial Dependence Plots (PDP)**
- **Model Coefficients & Feature Importances**
- **Confusion Matrix & ROC Analysis**

---

## 🧪 Model Assumptions Testing

- **Multicollinearity**: Variance Inflation Factor (VIF)
- **Linearity of Log-Odds**: Box-Tidwell Test
- **Outlier Detection**: Z-score and Boxplots
- **Data Distribution**: Normality testing
- **Sample Size Adequacy**: Based on # features and complexity

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/Bosy-Ayman/Diabetes-Explainatory-and-interpretability-project.git
