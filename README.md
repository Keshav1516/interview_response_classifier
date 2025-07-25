# 🎙️ Interview Response Classifier

**Builds a machine learning classification model to predict categories of interview responses using real-world conversational data.**

---

## 📌 Project Overview

This repository hosts a data-driven **interview response classification** project implemented in Python. It includes:

- A Jupyter notebook (`Interview_Response_Classifier_F.ipynb`) containing data exploration, feature engineering, model training, evaluation, and inference.
- CSV datasets: `train_IA_-_train.csv`, `test_IA_-_test.csv`, and `data_with_pred.csv` with predictions.
- Enables prediction of response categories (e.g., satisfactory, unsatisfactory) using popular supervised techniques like Logistic Regression, Random Forest, and SVM.

---

## 📂 Repository Structure

├── Interview_Response_Classifier_F.ipynb # Interactive notebook with full ML pipeline
├── train_IA_-train.csv # Training dataset
├── test_IA-_test.csv # Test dataset
├── data_with_pred.csv # Test results + model predictions
├── .gitignore # Files to exclude from Git
└── README.md # Project overview and instructions


---

## 🛠️ Features & Workflow

- 📊 **Data Loading & Exploration**  
  Insights into question-response patterns and class balance.

- 🧩 **Feature Engineering**  
  Techniques like TF-IDF text encoding, response length, keyword frequency, sentiment scoring.

- 🤖 **Modeling & Classification**  
  Implements models such as Logistic Regression, Random Forest, SVM for predicting response quality.

- 📈 **Performance Evaluation**  
  Metrics include accuracy, precision, recall, F1‑score, confusion matrix, and ROC-AUC.

- 🔍 **Result Analysis**  
  Predictions are saved in `data_with_pred.csv` for interpretation and further use.

---
