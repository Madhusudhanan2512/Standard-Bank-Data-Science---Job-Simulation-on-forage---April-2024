# 🏠 Predicting Home Loan Approval with Machine Learning

This project aims to predict the **loan approval status** of customers using traditional machine learning algorithms. It not only seeks to create a predictive model but also to understand the **factors that influence loan approvals**.

---

## 🔍 Problem Statement

Financial institutions often receive numerous loan applications and must decide which ones to approve. Manual evaluation can be slow and prone to error. This project uses machine learning to:

- Predict whether a loan application will be approved.
- Identify key factors influencing loan approval.

---

## 📊 Dataset Overview

- **Total records:** 614  
- **Number of features:** 13  
- **Data types:** `float64 (4), int64 (1), object (8)`  
- **Missing values:** Present, handled during preprocessing  
- **Duplicates:** None

---

## 🔎 Exploratory Data Analysis

From the analysis:
- Higher income correlates with higher loan approval rates.
- Customers requesting larger loan amounts are more likely to be approved.
- Graduates tend to have higher loan approval rates than non-graduates.

---

## 🤖 Modeling

Three models were implemented:

1. **Logistic Regression**  
   - Binary classification using sigmoid activation.
   - Ideal for linear decision boundaries.

2. **Decision Tree**  
   - Captures non-linear relationships.
   - Interpretable model based on feature splits.

3. **Random Forest**  
   - Ensemble of decision trees.
   - Robust to overfitting and gives best performance among the three.

---

## ✅ Model Evaluation

Evaluation metric: **Accuracy** (based on confusion matrix)

| Model              | Accuracy |
|-------------------|----------|
| Logistic Regression | 77%      |
| Decision Tree       | 71%      |
| Random Forest       | **80%**  |

📌 **Random Forest** gave the best accuracy.

---

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn (for visualization)
- Jupyter Notebook

---

## 📌 Key Insights

- Income and education significantly impact loan approval.
- Random Forest offers the most reliable performance.
- Logistic Regression gives a good baseline accuracy.

---

## 📌 Conclusion

This project shows how machine learning can assist in automating the loan approval process by offering data-driven decisions. Future improvements may include using advanced models like XGBoost or integrating deep learning techniques.