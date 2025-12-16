Predicting Early Signs of Diabetes from Lifestyle Data Using Machine Learning

📌 Overview

This project investigates the early detection of diabetes risk using lifestyle data and machine learning models. By analyzing patterns in behavioral, health, and socioeconomic factors, the study aims to distinguish between healthy, pre-diabetic, and early-stage diabetic individuals.

The work demonstrates how data-driven methods can support preventative healthcare, personalized risk assessment, and proactive intervention strategies.

This repository contains the datasets, analysis notebooks, and modeling pipeline used in the project.

🎯 Research Objectives

The project is guided by the following research questions:

Can machine learning models accurately predict early signs of diabetes using only lifestyle data?

Which lifestyle features are the most significant predictors of diabetes risk?

How do different machine learning models compare in terms of performance and interpretability?

Can individuals with “low-risk” profiles still be classified as high-risk due to other contributing factors?

🧠 Machine Learning Models Used

The following supervised learning models were implemented and evaluated:

Logistic Regression – baseline model with high interpretability

Random Forest Classifier – best-performing model, capable of capturing non-linear relationships

Neural Network (Multilayer Perceptron) – captures complex patterns but with lower interpretability

Class imbalance was handled using SMOTE (Synthetic Minority Over-sampling Technique).

🏆 Key Results

Best Model: Random Forest Classifier

F1-Score: 0.9318

Top Predictive Features:

Body Mass Index (BMI)

General Health

Age

High Blood Pressure

High Cholesterol

Income & Education (socioeconomic factors)

The Random Forest model demonstrated superior performance across ROC-AUC, precision, recall, and F1-score metrics.

🔍 Experiments Conducted
Experiment 1 – Model Performance Comparison

Evaluated Logistic Regression, Random Forest, and Neural Networks for multi-class diabetes classification.

Experiment 2 – Feature Importance Analysis

Used Random Forest feature importance scores to identify the most influential lifestyle predictors.

Experiment 3 – Atypical High-Risk Individuals

Analyzed individuals with low-risk profiles (based on BMI, Age, and General Health) who were still classified as pre-diabetic or diabetic, highlighting the multi-factorial nature of diabetes risk.

📊 Datasets
Dataset 1 – Diabetes Health Indicator Dataset (Curated)

Integrated from Kaggle sources

Includes lifestyle, health, and socioeconomic features

Target variable:

0 = Healthy

1 = Pre-diabetic

2 = Diabetic

Dataset 2 – Generated Synthetic Dataset

Synthetic lifestyle data used to:

Address class imbalance

Improve model robustness

🛠️ Tools & Technologies

Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

SMOTE (imbalanced-learn)

Google Colab
