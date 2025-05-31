# Task-4-Logistic-Regression---Binary-Classification
To apply Logistic Regression to a binary classification problem and evaluate its performance using standard classification metrics like  confusion matrix, precision, recall and ROC-AUC
# 🔍 Logistic Regression - Binary Classification

This repository contains the solution for **Task 4** of the **AI & ML Internship Program**, which focuses on building a binary classifier using **Logistic Regression**.

---

## 📌 Objective
To apply Logistic Regression to a binary classification problem and evaluate its performance using standard classification metrics like **confusion matrix**, **precision**, **recall**, and **ROC-AUC**.

---

## 🛠 Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 📂 Files Included
- `data.csv`: The binary classification dataset.
- `Logistic_Regression.ipynb`: Jupyter notebook containing model training, evaluation, and visualizations.
- `README.md`: Project overview and documentation.

---

## 🔄 Workflow

1. **Data Preprocessing**:
   - Loaded dataset and checked for null values.
   - One-hot encoded categorical features.
   - Feature and target variable separation.
   - Standardized features for model training.

2. **Model Training**:
   - Used `LogisticRegression` from `sklearn.linear_model`.
   - Performed train-test split using `train_test_split`.

3. **Model Evaluation**:
   - Metrics:
     - Accuracy
     - Precision
     - Recall
     - ROC-AUC Score
   - Confusion matrix and classification report
   - ROC Curve plotted
   - Sigmoid function visualized to understand output probability

---

## 📊 Evaluation Metrics (Sample)

| Metric      | Value     |
|-------------|-----------|
| Accuracy    | 0.92      |
| Precision   | 0.89      |
| Recall      | 0.91      |
| ROC-AUC     | 0.94      |

> Note: Replace with actual values from your output.

---

## 📈 Visual Outputs
- **Confusion Matrix**: Heatmap to show True/False Positives & Negatives.
- **ROC Curve**: To visualize the trade-off between sensitivity and specificity.
- **Sigmoid Curve**: Demonstrates the logistic regression output transformation.

---

## 🧠 Concepts Covered

- Difference between Logistic and Linear Regression
- Sigmoid Activation Function
- Binary Classification Metrics
- ROC-AUC Curve Interpretation
- Threshold Tuning and Probability Outputs

---

