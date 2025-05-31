# Naamii Task 2: Tabular Data Classification

## Project Overview
This repository contains the solution for the Naamii Task 2 challenge, which focuses on classifying tabular data using three datasets: training, test, and blinded test sets. The objective is to build and tune machine learning models for accurate and robust classification, then generate final class-probability predictions on the blinded test set for evaluation.

## Dataset
- **Training set**: Used for model training and hyperparameter tuning.
- **Test set**: Used for unbiased evaluation of model performance.
- **Blinded test set**: Used for final prediction submission; ground truth labels are hidden.

Dataset download link: [Naamii Task 2 Dataset](https://drive.google.com/file/d/1Zsg7ZiTWcpvm9IZl72z0DnOiNFu4QgGo/view)

## Models Implemented
- Logistic Regression
- Random Forest Classifier (with hyperparameter tuning via GridSearchCV)
- XGBoost Classifier (with hyperparameter tuning via GridSearchCV)

## Methodology
- Data preprocessing including missing value imputation and feature scaling.
- Hyperparameter tuning performed using 5-fold Stratified Cross-Validation.
- Evaluation metrics reported for each model on training and test sets:
  - Accuracy
  - AUROC
  - Sensitivity (Recall / True Positive Rate)
  - Specificity (True Negative Rate)
  - F1-score
- Final class probabilities generated for all datasets, including the blinded test set.

## Usage Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/rahulgupta32/Naamii_task2.git
   cd Naamii_task2
