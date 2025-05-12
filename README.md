# Loan Default Prediction Using Machine Learning

This project aims to predict whether a loan applicant will default using real-world financial data from the LendingClub platform. Using a cleaned and sampled version of the dataset, I applied and compared several machine learning models to classify loans as defaulted or fully paid.

---

## Dataset

**Source**: [LendingClub Loan Data on Kaggle](https://www.kaggle.com/datasets/wordsforthewise/lending-club)

**Note**: Due to size, the full dataset is not included in this repo. A sampled version (about 100,000 rows) was used during analysis.

---

## Models Used

1. Logistic Regression
2. Support Vector Machine (SVM)
3. Multi-Layer Perceptron (MLP Neural Network)

Each model was evaluated using accuracy, F1-score, ROC AUC, and confusion matrix.

---

## Evaluation Summary

| Model               | Accuracy | F1 Score (Default) | ROC AUC |
|--------------------|----------|--------------------|---------|
| Logistic Regression| 0.99     | 0.99               | 0.998   |
| SVM (RBF Kernel)   | 0.97     | 0.93               | 0.998   |
| MLP Neural Network | 0.99     | 0.98               | 0.997   |

---

## Visualizations

ROC curves for each model are included in the 'figures' directory.

---

## How to Run

1. Clone the repository
2. Open 'loan_default_risk.ipynb' in Jupyter or Google Colab
3. Run the notebook step-by-step
