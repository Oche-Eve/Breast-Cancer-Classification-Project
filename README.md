# Breast Cancer Classification Project - Machine Learning for Early Diagnosis

## Overview
This project builds a Machine Learning model to classify breast tumors as Benign or Malignant to support early diagnosis. Built with Python, Scikit-learn, and the public Wisconsin Breast Cancer Dataset.

**Author:** Oche Evelyn Ochoje - Program Analyst, Federal University of Health Sciences Teaching Hospital, Otukpo (FUHSTH Otukpo) | Aspiring Health Informatics PhD Researcher

**Note:** This is an educational project using a public dataset from sklearn.datasets.load_breast_cancer(). No real patient data from FUHSTH was used.

## Objective
To develop an accurate predictive model for breast cancer diagnosis.

## Dataset
- Source: sklearn.datasets.load_breast_cancer() - Public Wisconsin Dataset
- 569 samples, 30 features
- Target: 0=Malignant, 1=Benign

## Workflow
1. Importing Libraries
2. Loading Dataset
3. Exploratory Data Analysis (Histogram, Scatter, Box Plot)
4. Feature Engineering (IQR Outlier, Correlation Heatmap)
5. Data Splitting & Scaling (80/20 split, StandardScaler)
6. Model Building (LogisticRegression max_iter=10000)
7. Model Evaluation (Accuracy, Classification Report, Confusion Matrix)

## Results
- Accuracy: 95%+
- Evaluation: Classification Report + Confusion Matrix

## Technologies
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## How to Run
1. Clone repo
2. pip install pandas numpy scikit-learn matplotlib seaborn
3. Run notebook in Jupyter/Colab

## Future Work
Try Random Forest, SVM, and deploy with Streamlit.

*For educational and research purposes only.*
