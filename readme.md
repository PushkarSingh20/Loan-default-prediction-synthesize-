<h1 align="center">🏦 Credit Risk AI - Loan Default Prediction</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?logo=python" alt="Python">
  <img src="https://img.shields.io/badge/LightGBM-Gradient%20Boosting-green" alt="LightGBM">
  <img src="https://img.shields.io/badge/Pandas-Data%20Processing-orange?logo=pandas" alt="Pandas">
  <img src="https://img.shields.io/badge/Scikit--Learn-ML-yellow?logo=scikit-learn" alt="Scikit-learn">
  <img src="https://img.shields.io/badge/ROC--AUC-Evaluation-red" alt="ROC-AUC">
</p>

<p align="center">
  <b>Predict who might default… before the bank finds out the hard way.</b><br>
  A machine learning project that predicts loan default probability using structured financial data 💳<br>
  Built using LightGBM with advanced feature engineering and ROC-AUC optimization.
</p>

---

## 🚀 Features

- 📊 Predicts probability of loan default (not just yes/no)
- ⚖️ Handles highly imbalanced dataset (~8% defaults)
- 🧠 Advanced feature engineering (financial ratios + risk scores)
- ⚡ Fast and efficient LightGBM model
- 📈 Optimized for ROC-AUC (real-world credit risk metric)
- 🔄 Robust training using Stratified Cross Validation

---

## 🛠️ Tech Stack

| Category | Tools / Frameworks |
|----------|------------------|
| Programming Language | **Python 3.10+** |
| Machine Learning | **LightGBM** |
| Data Processing | **Pandas, NumPy** |
| Modeling | **Scikit-learn** |
| Evaluation Metric | **ROC-AUC** |

---

## 🧩 Project Workflow

1. **Data Loading** → Load `train.csv` and `test.csv`
2. **Preprocessing** → Handle missing values, fix anomalies, remove noise
3. **Feature Engineering** → Create financial ratios & risk indicators
4. **Model Training** → Train LightGBM using Stratified K-Fold CV
5. **Evaluation** → Optimize using ROC-AUC score
6. **Prediction** → Generate probability predictions for test data
7. **Submission** → Export results as `submission.csv`

---

## 🧠 Key Feature Engineering

- 📌 EXT_SOURCE Aggregations (Mean, Std, Product)
- 💰 Credit-to-Income Ratio
- 📉 Annuity-to-Income Ratio
- ⏳ Credit Term
- 👤 Age & Employment Stability Features

These features capture **financial risk, repayment burden, and borrower stability**.

---

## 📈 Model Performance

- Strong separation between defaulters and non-defaulters  
- Optimized for ranking performance (not accuracy)

---

## ⚖️ Why ROC-AUC?

- Dataset is highly imbalanced  
- Accuracy can be misleading  
- ROC-AUC measures ranking ability of the model  

---

## 📂 Output Format

Contains:

- TARGET → Probability between 0 and 1  
- No missing values  

---

## 🏦 Real-World Use Case

This model can be used in banking systems to:

- ✅ Approve low-risk applicants  
- ❌ Reject high-risk applicants  
- 💰 Adjust interest rates based on risk  
- ⚡ Enable real-time credit scoring  

---

## 🧑‍💻 Author

**Pushkar Singh**  
[🔗 LinkedIn](https://www.linkedin.com/posts/pushkar-singh-512648235_python-ai-machinelearning-activity-7385974773329203201-c_GG)

---

## Atlast

Fork it, improve it, break it, fix it.

Or just star the repo and pretend you’ll come back later ⭐

