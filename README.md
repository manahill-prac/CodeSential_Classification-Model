# Breast Cancer Classification

This repository contains a machine learning project that builds and compares classification models on the **Breast Cancer Wisconsin dataset**.

## Dataset
- **Source:** scikit-learn built-in `load_breast_cancer`
- **Type:** Binary classification (malignant vs benign)
- **Features:** 30 numeric features describing tumor characteristics
- **Target:** 0 = malignant, 1 = benign

## Objective
- Build and evaluate classification models
- Compare model performance
- Analyze feature importance or coefficients

## Models Used
- **Logistic Regression** – Feature coefficients displayed
- **Decision Tree Classifier** – Feature importance displayed
- **K-Nearest Neighbors (KNN)** – Feature importance via permutation displayed

## Preprocessing
- Missing value handling (if any)
- Feature scaling
- Encoding (not required here as features are numeric)

## Evaluation
- Confusion matrix
- Classification report (styled tables)
- Feature insights for each model

## How to Run
1. Clone the repository.
2. Open notebook in Jupyter Notebook or Google Colab.
3. Run all cells sequentially to reproduce results.

