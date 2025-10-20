# 🧠 Social Media Fake Account Detection

### 🎯 Objective
Develop a machine learning model to identify fake social media accounts based on user behavior data.

### 🧰 Tools & Libraries
Python, pandas, scikit-learn, matplotlib

### ⚙️ Process
1. Data cleaning and feature preprocessing  
2. Model benchmarking (Dummy, Logistic Regression, Random Forest)  
3. Evaluation using Accuracy, F1-score, ROC-AUC  
4. Visualization of ROC curves and learning curves  

### 📊 Results
| Model | AUC | Accuracy | F1 |
|-------|------|-----------|----|
| Dummy | 0.50 | 0.47 | 0.00 |
| Logistic Regression | 0.96 | 0.90 | 0.90 |
| Random Forest | 0.98 | 0.93 | 0.93 |

### 💡 Key Insights
- Random Forest achieved the best performance (AUC = 0.98, F1 = 0.93).  
- Recommended for automated fake account detection with threshold-based flagging.  
- Future improvement: apply SMOTE, SHAP interpretation, and periodic retraining.

---

👤 **Author:** Nash Chen  
📅 **Created:** 2025  
📍 London, UK
