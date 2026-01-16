

# Breast Cancer Diagnosis ML Model

## Objective
Build a supervised machine learning model to classify tumors as Malignant (M) or Benign (B) using the Wisconsin Breast Cancer Dataset. Demonstrates the full ML workflow: data preprocessing, model training, evaluation, and error analysis.

## Dataset
- Source: [UCI Machine Learning Repository]
 ( https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic)
- Files: `wdbc.data`, `wdbc.names`

## Files
- `task1_cancer_classification.ipynb` → Colab notebook with full workflow and evaluation.
- `wdbc.data`, `wdbc.names` → Dataset files (optional if too large).

## How to Run
1. Open `task1_cancer_classification.ipynb` in Google Colab or Jupyter Notebook.
2. Make sure `wdbc.data` is in the same folder as the notebook.
3. Run all cells sequentially.

## Output
- Train error and Test error (shows generalization gap)
- Accuracy, Precision, Recall, F1-score on test set
- Confusion matrix
- Short conclusion on overfitting/underfitting

## ML Issues Noted
- Feature scaling required for Logistic Regression
- Decision Tree can overfit (high variance)
- Feature correlation exists
