# 📊 Customer Retention & Churn Analytics

This project delivers a complete data-driven solution to predict and reduce customer churn in the telecommunications industry.  
It combines data analysis, feature engineering, predictive modeling, and actionable retention strategies to drive measurable business impact.

---

## 🚀 Project Highlights
- **Objective:** Predict & reduce customer churn in telecom  
- **Approach:** Data analysis, customer segmentation, feature engineering, predictive modeling  
- **Impact:** 7.34% churn reduction, ~$317K LTV preserved  
- **Top Models:** XGBoost, Random Forest, Logistic Regression  
- **Key Insights:** High-risk segments identified; actionable retention strategies recommended  

---

## 🧠 Problem Statement
Customer churn reduces recurring revenue and increases acquisition costs.  
This project focuses on:
- Identifying customers at high risk of leaving  
- Discovering the main drivers of churn  
- Providing actionable retention strategies to maximize Customer Lifetime Value (LTV)  

---

## 📂 Project Overview
- **Business Understanding:** Defined churn problem & goals  
- **Data Analysis:** Explored behavioral, financial, and demographic patterns  
- **Feature Engineering:** Engagement Score, Support Intensity, Cost Efficiency, Billing Pain, Usage-to-Cost Ratio  
- **Modeling:** Logistic Regression, Random Forest, XGBoost  
- **Evaluation:** Focused on recall, precision, and F1-score for actionable retention  
- **Business Impact:** Predicted 7.34% churn reduction & ~$317K LTV preserved  

---

## 🗃️ Data Overview
- **Dataset:** 6,687 customers  
- **Features:** Demographics, service usage, billing, contract type, customer support interactions  
- **Engineered Features:** Engagement Score, Support Intensity, Cost Efficiency, Billing Pain, Usage-to-Cost Ratio  
- **Target:** Churn (Yes/No)  
- **Dataset Versions:**
  - **V1:** Original dataset  
  - **V2:** Curated subset of important features  
  - **V3:** Feature-engineered, reduced collinearity  

---

## 💡 Key Findings & Business Impact
- **High-Churn Segments:** Month-to-month contracts, solo users, high spenders, frequent support callers  
- **Top Churn Drivers:** Account length, local calls/minutes, monthly charges, total charges, customer service calls, contract type, group membership, payment method, unlimited & international plans, senior customers  
- **Plan Insights:** Unlimited data plans have higher churn (~32%, >$1M LTV lost); international plans have minimal effect  
- **Actionable Strategies:** Loyalty programs, onboarding guides, plan upgrades, contract conversion offers, group plan promotions  
- **Impact:** ~490 customers retained, ~$317K in LTV preserved, enabling data-driven retention campaigns  

---

## 🤖 Modeling Approach
- **Models Tested:** Logistic Regression, Random Forest, XGBoost  
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1 Score  
- **Best Model:** XGBoost (V1 dataset)  
- **Focus:** Maximize recall and F1 to proactively identify at-risk customers  

---

## 📊 Results & Metrics
| Metric / Outcome               | Value                  |
|--------------------------------|----------------------|
| Best Model                     | XGBoost (V1)          |
| Accuracy                        | 91%                   |
| Precision                       | 85%                   |
| Recall                          | 81%                   |
| F1 Score                        | 83%                   |
| Estimated Churn Reduction       | 7.34%                 |
| Customers Retained              | ~490                  |
| Estimated LTV Preserved         | ~$317,630             |

---

## 💻 Tech Stack
- **Python:** pandas, numpy, scikit-learn, XGBoost  
- **Visualization:** Matplotlib, Seaborn  
- **Notebook Environment:** Jupyter  
- **Version Control:** Git & GitHub  
- **Reporting:** Executive dashboards & PDF reports  

---

## 📁 Project Files
- `data/` → Raw & processed datasets  
- `notebooks/` → EDA, feature engineering, modeling notebooks  
- `reports/` → Executive reports & dashboards  
- `models/` → Trained model files  

---

## 👩‍💻 Author
<img width="744" height="265" alt="Screenshot 2025-12-30 145453" src="https://github.com/user-attachments/assets/6c8f6356-4e01-45d4-8666-c134e5839772" />

