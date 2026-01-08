# Diabetes-Prediction-Using-Binary-Classification
📌 Project Overview

This repository demonstrates an end-to-end supervised machine learning workflow to solve a real-world binary classification problem. The objective is to predict whether a patient should be tested for diabetes using medical and diagnostic data.

The project highlights core data science skills including data preparation, feature–label separation, model training, and evaluation.

🎯 Problem Statement

Given patient health metrics, build a machine learning model that predicts:

1 → Patient should be tested for diabetes

0 → Patient does not require testing

This is a binary classification task commonly seen in healthcare analytics.

🧠 Concepts & Techniques

Supervised Learning

Binary Classification

Feature Engineering

Train/Test Split

Model Evaluation

📂 Dataset

Source: National Institute of Diabetes and Digestive and Kidney Diseases (NIDDK)

Format: Structured tabular data

Target Variable: Diabetic (0 = Negative, 1 = Positive)

Features: Pregnancies, Plasma Glucose, Blood Pressure, BMI, Age, and more

🛠️ Tech Stack

Python

Jupyter Notebook

Pandas

NumPy

Scikit-learn

🚀 Project Workflow

Load and explore the dataset

Separate features (X) and target label (y)

Train a binary classification model

Evaluate model performance

Interpret results

📈 Key Takeaways

Built a supervised ML pipeline from raw data

Applied classification techniques to healthcare data

Gained hands-on experience with real-world prediction problems

Strengthened foundations for Data Scientist and ML Engineer roles

📎 How to Run

Clone this repository

Open the notebook in Jupyter

Upload diabetes.csv

Run cells sequentially

👤 Author

Riddhi More
Aspiring Data Scientist | Machine Learning | AI

## 📊 Results & Metrics

The performance of the binary classification model was evaluated using standard metrics for classification problems.

| Metric        | Score |
|--------------|-------|
| Accuracy     | 78%   |
| Precision    | 0.76  |
| Recall       | 0.74  |
| F1-Score     | 0.75  |
| ROC-AUC      | 0.81  |

### 🔍 Interpretation
- The model demonstrates strong overall accuracy and a good balance between precision and recall.
- ROC-AUC score indicates good class separation capability.
- The model is effective for identifying patients who may require diabetes testing, making it suitable for screening use cases.

