## 📌 Problem Statement
The objective of this project is to implement and evaluate multiple machine learning classification models on the **Adult Census Income Dataset**.  
The task is to predict whether an individual's income exceeds $50K per year based on demographic and employment attributes.

---
- **Dataset:** Adult Census Income (UCI Machine Learning Repository)  
- **Instances:** ~48,842  
- **Features:** 14 attributes (categorical + numerical)  
- **Target Variable:** `income` (binary: `<=50K` or `>50K`)  
- **Preprocessing Steps:**  
  - Missing values (`?`) replaced with `NaN` and dropped  
  - Label encoding applied to categorical features  
  - Train-test split (80/20)  
  - Standard scaling applied to numerical features  

---
The following six models were implemented on the same dataset:
1. Logistic Regression  
2. Decision Tree Classifier  
3. k-Nearest Neighbor Classifier  
4. Naive Bayes Classifier (GaussianNB)  
5. Random Forest (Ensemble)  
6. XGBoost (Ensemble)  
---

## 📊 Comparison Table of Evaluation Metrics
| ML Model Name       | Accuracy | AUC | Precision | Recall | F1 | MCC |
|---------------------|----------|-----|-----------|--------|----|-----|
| Logistic Regression | xx.xx    | xx.xx | xx.xx     | xx.xx  | xx.xx | xx.xx |
| Decision Tree       | xx.xx    | xx.xx | xx.xx     | xx.xx  | xx.xx | xx.xx |
| kNN                 | xx.xx    | xx.xx | xx.xx     | xx.xx  | xx.xx | xx.xx |
| Naive Bayes         | xx.xx    | xx.xx | xx.xx     | xx.xx  | xx.xx | xx.xx |
| Random Forest       | xx.xx    | xx.xx | xx.xx     | xx.xx  | xx.xx | xx.xx |
| XGBoost             | xx.xx    | xx.xx | xx.xx     | xx.xx  | xx.xx | xx.xx |

*(Replace `xx.xx` with actual values from your Streamlit app output.)*

---


| ML Model Name       | Observation about model performance |
|---------------------|--------------------------------------|
| Logistic Regression | Performs well on linear relationships; interpretable but less powerful on complex data. |
| Decision Tree       | Easy to interpret; prone to overfitting; moderate accuracy. |
| kNN                 | Sensitive to scaling; slower with large datasets; moderate performance. |
| Naive Bayes         | Fast and simple; assumes feature independence; decent baseline. |
| Random Forest       | Strong performance; handles categorical + numerical features well; robust against overfitting. |
| XGBoost             | Best overall performance; powerful ensemble method; slightly higher computational cost. |

---

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/ML-Assignment-2-Classification.git
