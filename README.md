Insurance Claim Fraud Detection System
📌 Project Overview

This project aims to detect fraudulent insurance claims while ensuring that genuine claims are processed quickly. It leverages advanced machine learning techniques to mimic real-world fraud detection challenges such as imbalanced data, missing values, and noisy information.

🚀 Key Features

End-to-End ML Pipeline: Data preprocessing, feature engineering, imputation, modeling, and evaluation.

Hybrid Imputation Strategy: KNN imputer for numeric features and mode imputation for categorical variables.

Imbalance Handling: Applied SMOTE and precision–recall threshold tuning to focus on minimizing false negatives.

Modeling: Implemented Random Forest and XGBoost for fraud detection, emphasizing recall and precision trade-offs.

Performance Focus: Designed to detect fraudulent claims effectively without delaying genuine claims.

🧠 Workflow

Data Preparation – Cleaned data, handled missing values using hybrid imputation.

Feature Engineering – Created ratios like claim_to_sum_ratio, premium_to_sum_ratio, and claim_delay_ratio.

Imbalance Handling – Applied SMOTE and tuned thresholds for optimal recall–precision balance.

Model Training – Trained and compared Random Forest and XGBoost models.

Model Evaluation – Used classification metrics and Precision–Recall trade-off curves for performance validation.

📈 Results

Achieved high recall and balanced precision on noisy real-world–like data.

Minimized false negatives, reducing potential financial loss.

Ensured genuine claims are processed efficiently.
