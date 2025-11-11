# 🕵️‍♀️ Insurance Fraud Detection (Realistic Noisy Data)

A machine learning project to detect **insurance frauds** while ensuring **genuine claims remain unaffected**.  
The dataset is enhanced with **real-world noise, missing values, and label errors** to mimic practical fraud detection challenges.

---

## 🎯 Objective

- Identify fraudulent claims using ML models.
- Simulate real-world conditions with noisy, imbalanced data.
- Focus on **high recall** to catch frauds **without wrongly flagging genuine claims**.

---

## ⚙️ Tech Stack

- Python, pandas, NumPy  
- scikit-learn, XGBoost, Random Forest  
- imbalanced-learn (SMOTE)  
- matplotlib, seaborn  

---

## 🧩 Data Simulation

Real-world inconsistencies added:
- Gaussian noise to numeric columns (`claim_amount`, `premium`, etc.)
- Missing values (~10%)  
- Label flips (5%)  
- Date shifts (±10 days)  
- Category drift (city, region)  
- Fraud camouflage: 25% fraud cases adjusted to appear genuine

All noise added **carefully** to preserve data realism and **avoid disturbing genuine claims**.

---

## 🧠 Model Pipeline

1. **Preprocessing:** Handle missing data, encode categorical vars  
2. **Balancing:** SMOTE applied for class imbalance  
3. **Modeling:** Random Forest, XGBoost, Logistic Regression  
4. **Evaluation:** Accuracy + Recall (priority)  

---

## 📈 Results

| Model          | Accuracy | Recall | Precision |
|----------------|-----------|---------|------------|
| Random Forest  | 0.87      | 0.85    | 0.82       |
| XGBoost        | 0.86      | 0.84    | 0.81       |

Model maintains **high fraud recall** while **minimizing false alarms** on genuine claims.

---

## 🚀 Future Scope

- SHAP for explainability  
- Streamlit dashboard for fraud probability  
- Model retraining under feature drift  

