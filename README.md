# 🎓 Student Performance Decision Support System (DSS)

This project presents a *Decision Support System (DSS)* to analyze and predict student performance using machine learning and data visualization. By leveraging data science techniques, the system identifies at-risk students and suggests personalized interventions, empowering educators to make data-driven decisions.

---

## 📌 Project Overview

- 🔍 *Objective*: Predict academic success and offer targeted support to students.
- 🛠 *Tools Used*: Python, Pandas, Seaborn, Scikit-learn, Power BI
- 📈 *Modeling Techniques*: Logistic Regression, Decision Tree
- 📊 *Visualization*: Interactive dashboards created with Power BI
- 📁 *Dataset*: [Student Performance Dataset – Kaggle](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)

---
## 📂 Project Structure

student-performance-dss/
├── data/
│   └── Cleaned_StudentsPerformance.csv         # Cleaned dataset for analysis
├── notebooks/
│   └── eda_model_building.ipynb                # EDA and model building notebook
├── dashboards/
│   └── student_performance_dashboard.pbix      # Power BI dashboard file
├── visuals/
│   └── figures and charts                      # Plots and exported images
├── README.md                                   # Project overview
└── report.pdf                                  # Final project report
## 🧪 Machine Learning Workflow

1. *Preprocessing*:
   - One-hot encoding of categorical variables
   - Created average_score and pass_fail variables
2. *EDA Highlights*:
   - Test prep completion boosts scores
   - Reading and writing scores are strongly correlated
   - Minimal gender-based performance gaps
3. *Modeling*:
   - Logistic Regression: 100% test accuracy
   - Decision Tree: Simpler, but lower performance
4. *Evaluation*:
   - Accuracy
   - Confusion matrix
   - Precision/recall (via Power BI)

---

## 💡 DSS Logic Flow

Start
|
v
Calculate Average Score (Math + Reading + Writing) / 3
|
v
Is Average Score < 50?
├── Yes → Classify as “Fail”
│         → Recommend remedial courses & tutoring
└── No
|
v
Is Average Score < 65?
├── Yes → Classify as “At Risk”
│         → Suggest test prep & targeted practice
└── No
|
v
Is Average Score < 80?
├── Yes → Classify as “Pass”
│         → Recommend continued practice & mentorship
└── No
|
v
Classify as “High Performer”
→ Offer advanced learning & leadership opportunities
|
END

---

## 📊 Key Features

- ✅ Predicts pass/fail outcomes using classification models
- 📌 Categorizes students into 4 classes (Fail, At Risk, Pass, High Performer)
- 🎯 Actionable recommendations based on performance tier
- 📉 Analyzes demographic impact on academic performance
- 🧠 Interpretable ML with high accuracy
- 📊 Interactive Power BI dashboard for educators

---

## 📊 Dashboard Summary

- Bar charts: Math, Reading, Writing score distributions
- Pie charts: Parental education levels
- KPI cards: Total average score, pass count
- Filters: Gender, parental education, test preparation
- Confusion matrix: Model evaluation in Power BI

---

## 🔮 Future Scope

- Expand dataset with broader geographic & behavioral data
- Integrate more advanced models (e.g., XGBoost, Neural Networks)
- Real-time monitoring dashboard
- Mobile-friendly decision support tool for educators
- Incorporate explainable AI (e.g., SHAP, LIME)

---

## 📄 Project Report

📥 [Download Full Report (PDF)](link-if-public)

---

## 🙋 Project Author

*Bitla Sravan*  
MSc Data Science Candidate, Berlin, Germany  
📧 sravannetha000111@gmail.com  
📞 +49 176 28622302  

---

> “Data-driven interventions can change the trajectory of a student’s life.”

