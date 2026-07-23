# 👨‍💼 Employee Attrition Prediction Using Machine Learning

## 📌 Project Overview

Employee attrition is one of the biggest challenges faced by organizations, leading to increased recruitment costs, productivity loss, and reduced employee satisfaction. This project aims to predict whether an employee is likely to leave the organization by analyzing HR-related data using Machine Learning techniques.

The project follows a complete Machine Learning workflow, including data preprocessing, exploratory data analysis (EDA), model building, evaluation, visualization, and business recommendations for HR decision-making.

---

## 🎯 Project Objectives

- Analyze employee attrition patterns.
- Identify the major factors influencing employee turnover.
- Build and compare multiple Machine Learning classification models.
- Select the best-performing model based on evaluation metrics.
- Provide actionable HR recommendations to improve employee retention.

---

## 📂 Dataset Information

**Dataset:** IBM HR Analytics Employee Attrition Dataset

The dataset contains employee information such as:

- Age
- Department
- Job Role
- Monthly Income
- Business Travel
- Overtime
- Work-Life Balance
- Years at Company
- Job Level
- Attrition (Target Variable)

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Employee Attrition Rate by Department
- Employee Attrition Rate by Job Role
- Monthly Income Distribution
- Work-Life Balance Analysis
- Years at Company Analysis

---

## 🤖 Machine Learning Models

The following classification models were trained and compared:

- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

---

## 📈 Model Evaluation

The models were evaluated using:

- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

### 🏆 Best Performing Model

**Logistic Regression**

Why?

- Highest Recall
- Best F1-Score
- Highest ROC-AUC
- Most suitable for identifying employees at risk of leaving

---

## 📊 Key Findings

- The **Sales Department** recorded the highest employee attrition rate.
- **Sales Representatives** showed the highest attrition among all job roles.
- Employees working **Overtime** were significantly more likely to leave.
- **Business Travel** strongly influenced employee attrition.
- Poor **Work-Life Balance** increased the likelihood of employee turnover.
- Salary alone was not the primary reason for employee attrition.

---

## 📷 Project Visualizations

The project includes the following visualizations:

- Attrition Rate by Department
- Attrition Rate by Job Role
- Monthly Income Distribution
- Work-Life Balance Analysis
- Years at Company Analysis
- Confusion Matrix
- Top 10 Feature Importance
- ROC Curve Comparison

All charts are available in the **charts/** folder.

---

## 💼 HR Recommendations

Based on the analysis:

- Focus retention programs on the Sales department.
- Reduce excessive overtime and improve work-life balance.
- Strengthen onboarding and mentoring during the first two years of employment.
- Monitor employees in high-risk job roles proactively.
- Use predictive analytics to support HR decision-making.

---

## 📁 Repository Structure

```
Employee-Attrition-Prediction/
│
├── analysis.ipynb
├── HR_Attrition.csv
├── README.md
├── HR_Director_Project_Summary.pdf
│
└── charts/
    ├── chart1_department_attrition.png
    ├── chart2_jobrole_attrition.png
    ├── chart3_monthly_income.png
    ├── chart4_work_life_balance.png
    ├── chart5_years_at_company.png
    ├── chart6_confusion_matrix.png
    ├── chart7_feature_importance.png
    └── chart8_roc_curve.png
```

---

## 🚀 Future Improvements

- Handle class imbalance using advanced techniques such as SMOTE.
- Perform Hyperparameter Tuning.
- Deploy the model using Streamlit or Flask.
- Integrate the solution into an HR Analytics Dashboard.
- Train additional ensemble learning models.

---

## 📌 Conclusion

This project successfully built and evaluated multiple Machine Learning models to predict employee attrition. Logistic Regression emerged as the best-performing model, while the analysis identified **Job Role, Overtime, Business Travel, Work-Life Balance, and Years at Company** as the most influential factors affecting employee turnover. These insights can help HR teams implement proactive retention strategies and make data-driven workforce planning decisions.

---

## 👨‍💻 Author

**Shashank Singh Rajput**

Machine Learning & Data Science Intern

XYlofy AI Internship – Week 2 Project
