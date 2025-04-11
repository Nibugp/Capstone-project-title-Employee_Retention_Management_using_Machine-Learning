# Capstone-project-title-Employee_Retention_Management_using_Machine_learning

In this machine learning capstone project, I explored and evaluated multiple algorithms to identify the most reliable model, synthesizing key concepts in machine learning, data preparation, and predictive modeling to develop a robust and actionable solution.


## **📁 Dataset Overview**

The dataset used contains 1,680 employee records from a global ERD organization, with features spanning demographics, compensation, performance, tenure, and promotion history. Given an attrition rate of 27%, class imbalance was a key challenge.


## **🎯 Project Objectives**

1.	Identify Key Attrition Drivers
2.	Determine the Most Effective Model
3.  Develop a Predictive Model
4.  Evaluate Model Effectiveness and Provide Insights for Future Actions


## **⚙️ Data Preparation & Processing**

The data underwent the following processing steps:

- Missing value imputation for performance and promotion columns.
- Feature engineering, including tenure in months, time since last promotion, and promotion frequency.
- Categorical encoding (Label, One-Hot, and Ordinal).
- Standardization of numerical features.
- Class imbalance handling using SMOTE to improve model sensitivity toward minority class (attrition cases).

  
## **✅ Classification Modeling**

Several machine learning models were trained and evaluated:

- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- SVM
- Neural Network
  

## **🧠 Key Results**

* Neural Network (6-layer deep learning model) and Random Forest showed the best performance on balanced data.

* SMOTE significantly boosted recall from 8.3% to 87.5%, enhancing the model’s ability to identify at-risk employees.

* Final deep learning model achieved:

83% validation accuracy

91% recall

0.91 AUC-ROC score
  

## **🔍 Insights & Feature Importance**

Top predictors of attrition included:

- Compensation (CTC)

- Tenure & Years of Service

- Promotion history

- Job grade

- Performance ratings

SHAP analysis confirmed these drivers and added transparency to model decisions.


## **🚀 Conclusion & Recommendation**

The study demonstrated that deep learning methods are effective for predicting employee attrition, especially when combined with data balancing techniques.


## 📂 Project Structure

- `retention_management.py` — Main Python script for preprocessing, modeling, and evaluation
- - [`retention_management.py`](https://github.com/Nibugp/Capstone-project-title-Employee_Retention_Management_using_Machine-Learning/blob/main/retention_management.py) — View the full source code on GitHub

