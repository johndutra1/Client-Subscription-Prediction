# Client Subscription Prediction – Bank Marketing Dataset

This project involved building a supervised machine learning pipeline to predict whether a client would subscribe to a term deposit based on a variety of economic and demographic features.

## 🧠 Project Overview

- **Goal**: Predict client subscription using historical bank marketing data.
- **Techniques**: Random Forest, XGBoost, Logistic Regression.
- **Performance**: Achieved an F1 score of **0.81** through model tuning and class balancing.

## 🛠️ Key Features

- Feature engineering from economic and demographic data
- Class imbalance handled using **SMOTE**
- Model selection and hyperparameter tuning via **cross-validation**
- Model explainability using **SHAP**
- Ablation analysis to address potential **label leakage**
- Ensemble model that outperformed individual classifiers

## 📁 Dataset

- Source: [UCI Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing)
- Includes client demographics, campaign contact details, and economic indicators.

## 📌 Tools & Libraries

- Python, Pandas, NumPy, Scikit-learn, XGBoost, Imbalanced-learn (SMOTE), SHAP, Matplotlib, Seaborn

## 📝 Results

The ensemble model provided a strong balance between precision and recall, validated with cross-validation and confirmed by SHAP interpretability analysis.

---

This project was developed as part of a machine learning course at **The University of Texas at Dallas** (May 2025).
