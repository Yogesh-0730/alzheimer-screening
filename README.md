# 🧠 Clinova — Early Alzheimer's Risk Screening System

An explainable machine learning-based web application for early Alzheimer's disease risk screening. Built as part of a college ML project.

## 🌐 Live Demo

👉 [**Try it here**](https://yourusername.github.io/alzheimer-screening/)

## 📌 Features

- **5 ML Models**: Decision Tree, KNN, SVM, XGBoost, Logistic Regression
- **Real-time Predictions**: Client-side inference — no server needed
- **Explainable AI**: Transparent risk scoring with feature importance
- **Feature Selection**: Mutual Information-based feature ranking
- **PCA Dimensionality Reduction**: 10 components retaining 96.2% variance
- **Responsive Design**: Works on desktop and mobile

## 🔬 Models & Accuracy

| Model | Accuracy | Recall | F1 Score |
|-------|----------|--------|----------|
| Decision Tree | 86.50% | 86.02% | 0.856 |
| KNN (k=7) | 89.50% | 88.17% | 0.887 |
| SVM (RBF) | 90.50% | 95.70% | 0.904 |
| XGBoost | 89.50% | 91.40% | 0.890 |
| **Logistic Regression** | **93.00%** | **96.77%** | **0.928** |

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **ML Backend**: Python, scikit-learn, XGBoost
- **Dataset**: 1,000 synthetic clinical records (15 features)

## 📊 Key Features Used

- MMSE Score, nWBV (Brain Volume), Age, Memory Complaints, Functional Score

## ⚠️ Disclaimer

This is an **academic screening tool** — not a clinical diagnostic system. MCI ≠ Alzheimer's Disease. Always consult qualified healthcare professionals.

## 👥 Team

- Yogesh & Team — B.Tech CSE

## 📄 License

This project is for educational purposes only.
