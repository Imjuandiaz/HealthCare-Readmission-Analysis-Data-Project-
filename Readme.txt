# The Second Chance: An Analysis on Transforming Patient Discharge and Recovery

## 📘 Project Overview
**The Second Chance** is a data-driven healthcare analytics project developed using the **PCCI (Parkland Center for Clinical Innovation)** dataset.  
The study investigates hospital readmission patterns and builds a predictive model to identify patients at high risk of returning within 30 days.  
This analysis bridges **clinical insight and data science**, empowering hospitals to improve discharge strategies and post-care recovery outcomes.

---

## 🎯 Objective
The goal of this project is to uncover the **key drivers behind 30-day hospital readmissions** and develop a **predictive model** capable of supporting proactive care decisions.  
By combining descriptive analytics and machine learning, this project provides actionable insights to help hospitals **reduce readmission rates** and **enhance patient outcomes**.

---

## 🧩 Data Summary
**Dataset Features:**
- **Demographics:** `Gender`, `Age`, `Marital_Status`, `Insurance_Provider`
- **Clinical Data:** `Chronic_Conditions`, `ER_Visits`, `ICU`, `Condition`, `Care_Plan_Following_Discharge`
- **Behavioral Factors:** `Tobacco_User`, `Depression`, `Diabetes`, `Obesity`, `Anxiety`, `Dementia`
- **Cost & Vitals:** `Cost_Of_Initial_Stay`, `Glucose`, `Bmi`, `Pulse`, `Temperature`
- **Target Variable:** `Readmit30` (1 = Readmitted within 30 days, 0 = Not Readmitted)

---

## 📊 Exploratory Insights
1. **20% of patients** were readmitted within 30 days.  
2. **Heart failure** and **pulmonary diseases** emerged as leading causes of readmission.  
3. **Older and Medicare-insured patients** exhibited higher risk.  
4. Following **post-discharge care plans** significantly reduced readmission probability.  
5. Patients readmitted within 30 days showed **higher average costs**, **more chronic conditions**, and **more ER visits**.

---

## 🧠 Machine Learning Model: Random Forest Classifier

### **Performance Results**
- **Accuracy:** 0.83  
- **AUC:** 0.68  
- **Precision:** 0.91  
- **Recall:** 0.16  

### **Model Insight**
The Random Forest classifier achieved **strong accuracy (83%)** and **high precision (91%)**, meaning it reliably identifies patients most likely to be readmitted.  
While recall is modest (16%), this reflects a **conservative model** that minimizes false alarms — ideal for allocating limited healthcare resources efficiently.  
The Random Forest was therefore selected as the **final production model** for this analysis.

---

## 🧾 Model Evaluation
- **Confusion Matrix:** High true negatives and precision, with a conservative recall profile.  
- **ROC Curve (AUC = 0.68):** Indicates moderate discriminative performance between readmitted and non-readmitted patients.  
- **Precision-Recall Curve:** Reinforces strong precision focus, suitable for risk flagging.  
- **Learning Curve:** Demonstrates model stability and minimal overfitting.  
- **Calibration Curve:** Confirms good probability reliability at higher predicted risk levels.

---

## 💡 Key Findings
- Frequent **ER visits** and **multiple chronic conditions** are the strongest predictors of readmission.  
- **Adherence to discharge care plans** significantly reduces the likelihood of readmission.  
- The **Random Forest** model provides hospitals with a scalable, interpretable, and high-precision prediction tool.  
- Proactive outreach to flagged patients can meaningfully reduce 30-day return rates and associated costs.

---

## 🏁 Conclusion
“The Second Chance” demonstrates how predictive analytics can transform healthcare decision-making.  
By identifying at-risk patients early and addressing preventable factors, hospitals can lower readmissions, enhance care quality, and optimize resource allocation.  
This project exemplifies how **machine learning and human-centered care** can work together to give every patient a second chance at full recovery.

---

## ⚙️ Technologies Used
- **Python Libraries:** Pandas, Scikit-learn, Matplotlib, Seaborn, PyCaret, Dython, YData Profiling  
- **Visualization Tools:** Tableau, Power BI  
- **Development Environment:** Jupyter Notebook  
- **Version Control:** GitHub

---

## 👤 Author
**Juan Díaz**  
Data Analyst | Machine Learning & Healthcare Analytics Enthusiast  
📧 Contact: juan.diaz.data@gmail.com  
🔗 GitHub: [https://github.com/Imjuandiaz](https://github.com/Imjuandiaz)

---
© 2025 Juan Díaz. All rights reserved.
