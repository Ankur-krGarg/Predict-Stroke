# 🧠 Stroke Prediction using Machine Learning

A data-driven healthcare project that predicts the likelihood of a stroke based on patient health metrics. Designed for early diagnosis support and medical decision-making.

## 🚀 Project Overview

This ML-based system analyzes patient records to determine stroke risk with a focus on accuracy and clinical relevance. The project applies statistical analysis, advanced preprocessing, and robust classification techniques.

## 📌 Features

- Cleaned and validated real-world healthcare dataset
- Balanced class distribution using resampling techniques
- Applied models: Logistic Regression, Random Forest, XGBoost
- Performance metrics: Accuracy, F1-score, ROC-AUC, Confusion Matrix
- Feature importance insights to support interpretability

## 🗃️ Dataset Source

[Kaggle: Stroke Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)  
Fields include:
- `age`, `hypertension`, `heart_disease`
- `avg_glucose_level`, `bmi`
- `gender`, `smoking_status`, `work_type`, `ever_married`

## ✅ Results Summary

- Best model: `Random Forest`  
- ROC-AUC: `~0.92`  
- Precision-Recall optimized for minimizing false negatives (critical in healthcare)

## 💡 Applications

- Virtual health assistants
- Risk flagging for hospitals and insurance firms
- Embedded ML in medical dashboards

---

> 🛑 *Disclaimer*: This is a research and demo project only. It is not validated for clinical use.
