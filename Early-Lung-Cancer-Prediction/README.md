# Early Lung Cancer Prediction Using Machine Learning and Explainable AI

## Overview
This project implements an end-to-end machine learning pipeline to predict lung cancer at an early stage using survey-based patient data. Multiple machine learning models were trained and evaluated, and the best-performing model was selected. Explainable AI (XAI) techniques using SHAP were applied to interpret model predictions.

## Project Report
The detailed project report for this work is available directly in this repository:

- **Early Lung Cancer Prediction Report SE25MBDS011.pdf**

The report contains the complete methodology, results, visualizations, and explanations corresponding to the implementation in the Jupyter notebook.

## Dataset
- Source: Kaggle – Survey Lung Cancer Dataset
- Each record represents a patient with symptoms and lifestyle attributes
- Target variable: Lung cancer (Yes / No)

## Methodology
1. Data preprocessing and encoding
2. Train–test split with stratification
3. Feature scaling
4. Training multiple ML models
5. Model evaluation using ROC-AUC, Precision, Recall, F1-score
6. Best model selection (XGBoost)
7. Explainability using SHAP (global and local)

## Models Used
- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Naive Bayes  
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)  
- Neural Network (MLP)  
- XGBoost  

## Results
- XGBoost achieved the highest ROC-AUC score
- SHAP analysis highlighted smoking and respiratory symptoms as key contributors

## Explainable AI (SHAP)
- SHAP Summary Plot: Global feature importance
- SHAP Waterfall Plot: Individual patient-level explanation

## Repository Structure
- `notebooks/` – Jupyter notebook implementation
- `reports/` – Output plots and visualizations
- `data/` – Dataset link reference
- `requirements.txt` – Python dependencies

## Disclaimer
This model is intended for academic and screening support purposes only and should not be used as a replacement for clinical diagnosis.

## Author
**Dasari Surya Vamsi**  
M.Tech Biomedical Data Science
