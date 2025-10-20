<img width="1920" height="1080" alt="ML Presentation" src="https://github.com/user-attachments/assets/c8efca39-398b-4c14-9a8e-6be10cf5f323" />

# 🧠 Social Media Fake Account Detection

Detecting fake social media accounts using supervised machine learning.  
This project demonstrates how data-driven insights and predictive modeling can help social platforms identify and manage fake user activity.

---

## 🎯 Objective
Develop a machine learning model to identify fake social media accounts based on user behavior and engagement features.

---

## 🧰 Tools & Libraries
**Languages & Libraries:** Python, pandas, scikit-learn, matplotlib  
**Environment:** Jupyter Notebook  
**Version Control:** Git & GitHub  

---

## ⚙️ Project Workflow
1. **Data Preprocessing:** Cleaned and prepared user behavior dataset  
2. **Model Benchmarking:** Compared Dummy Classifier, Logistic Regression, and Random Forest  
3. **Evaluation Metrics:** Accuracy, F1-score, ROC-AUC, and Learning Curves  
4. **Visualization:** Created ROC and Validation Curves for performance interpretation  
5. **Business Insight:** Suggested strategies for mitigating fake account impact  

---

## 📊 Results Summary
| Model | AUC | Accuracy | F1 |
|-------|------|-----------|----|
| Dummy | 0.50 | 0.47 | 0.00 |
| Logistic Regression | 0.96 | 0.90 | 0.90 |
| Random Forest | 0.98 | 0.93 | 0.93 |

---

## 💡 Key Insights
- **Random Forest** achieved the highest performance (AUC = 0.98, F1 = 0.93)  
- Outperformed baseline and linear models, showing strong capability in non-linear pattern detection  
- Suitable for automated detection pipelines with threshold-based alerts  
- Recommended for integration into moderation or fraud prevention systems  

---

## 🚀 Future Improvements
- Apply **SMOTE** or other sampling methods to balance class distribution  
- Use **SHAP values** to explain feature importance and improve transparency  
- Experiment with **XGBoost** or **LightGBM** for potential performance gain  
- Build a **real-time BI dashboard** in Tableau or Power BI to monitor detection metrics  

---

## 🖥️ Project Files
- `Social Media Fake Account Detection.ipynb` → Main notebook with analysis and results  
- `social_media_fake_account_detection.html` → Rendered version for quick viewing  
- `banner.png` → Project header image  

👉 [**View the full interactive report (HTML)**](social_media_fake_account_detection.html)

---

## 👤 Author
**Name:** Nash Chen  
**Location:** London, UK  
**Created:** 2025  
**Contact:** [LinkedIn](https://www.linkedin.com/yenjuchen0514)

---

⭐ *If you like this project, consider giving it a star on GitHub!* 🌟
