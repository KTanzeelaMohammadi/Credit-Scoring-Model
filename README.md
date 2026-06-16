# Credit Scoring Model

A machine learning pipeline built in Python to assess financial risk by predicting the creditworthiness of loan borrowers. This model determines whether an applicant is likely to default or successfully repay a loan.

## 📌 Project Overview
As my first data science project in financial risk, this repository establishes a solid baseline using an industry-standard statistical approach. It processes raw borrower data, engineers key financial metrics, and handles class imbalance to predict loan defaults.

## 🛠️ Tech Stack & Key Concepts
1. **Language:** Python (Google Colab)
2. **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
* **Algorithm:** Logistic Regression (chosen for its high interpretability in banking)
3. **Feature Engineering:** Calculated the **Debt-to-Income (DTI)** ratio.
4. **Class Imbalance:** Handled using balanced class weights.

## 📊 Evaluation Metrics
The model's performance is evaluated using:
 **ROC-AUC Score:** 

## 🚀 Future Enhancements
To evolve this project further, I plan to:
1. Compare this baseline with tree-based models like Random Forest or XGBoost.
2. Implement Weight of Evidence (WoE) and Information Value (IV) for feature selection.
3. Build a scoring function to map default probabilities to a traditional 300–850 credit score scale.
