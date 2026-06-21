# Term Deposit Subscription Prediction

Predict customer subscription to term deposits using machine learning models, with SHAP for interpretability.

## Overview
This project builds a binary classification model to identify potential customers likely to subscribe to a term deposit, leveraging bank marketing campaign data.

## Dataset
- **Source:** `bank.csv`
- **Target:** `y` (subscribed: yes/no)
- **Features:** Demographics, contact history, campaign details

## Models Used
- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Naive Bayes

## Evaluation
- Accuracy & F1-Score
- Confusion Matrix & ROC Curve
- **Best Model:** Random Forest (89.5% Accuracy)

## Interpretability
- Used **SHAP** to explain feature importance and individual predictions.

## Results Summary
| Model               | Accuracy | F1-Score |
|---------------------|----------|----------|
| Logistic Regression | 0.888    | 0.252    |
| Decision Tree       | 0.878    | 0.432    |
| **Random Forest**   | **0.902**| 0.380    |
| KNN                 | 0.877    | 0.301    |
| Naive Bayes         | 0.832    | 0.367    |

## How to Run
1. Clone the repository.
2. Upload `bank.csv` when prompted in the notebook.
3. Run all cells.

```bash
git clone <repo-url>
jupyter notebook Task_01_Deposit_Prediction.ipynb
