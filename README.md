# **HR Analytics – Employee Attrition Prediction**

## Project Overview
Employee attrition is a major challenge for organizations as it increases recruitment costs, reduces productivity, and impacts team stability. This project focuses on analyzing HR data to identify the key factors influencing employee attrition and building a machine learning model to predict whether an employee is likely to leave the organization.

Using Python-based analytics and explainable machine learning techniques, the project provides actionable insights that can help HR teams design effective employee retention strategies.


## Objectives
* Analyze employee data to understand patterns and trends related to attrition
* Identify key factors influencing employee resignation
* Build a predictive classification model for employee attrition
* Handle class imbalance using SMOTE
* Explain model predictions using SHAP values


## Tools & Technologies Used

* **Python**
* **Pandas & NumPy** – Data preprocessing and analysis
* **Matplotlib & Seaborn** – Data visualization
* **Scikit-learn** – Machine learning modeling and evaluation
* **Imbalanced-learn (SMOTE)** – Handling class imbalance
* **SHAP** – Model explainability
* **Google Colab** – Development environment


## Project Files

* `HR_Employee_Attrition_Dataset.csv` – Dataset used for analysis
* `HR_Analytics_Employee_Attrition_Prediction.ipynb` – Complete analysis and modeling notebook
* `HR_Analytics_Employee_Attrition_Report_Anjali_Gupta.pdf` – Final project report


## Project Workflow

1. **Data Loading & Preprocessing**
   * Data inspection, cleaning, encoding categorical variables, and feature scaling

2. **Exploratory Data Analysis (EDA)**
   * Attrition analysis by department, income, overtime, and tenure
   * Correlation analysis to identify key relationships

3. **Model Building**
   * Logistic Regression model for attrition prediction

4. **Handling Class Imbalance**
   * Applied SMOTE to balance attrition classes

5. **Model Evaluation**
   * Accuracy, confusion matrix, classification report, and ROC–AUC

6. **Model Explainability**
   * SHAP summary and bar plots to identify top drivers of attrition


## Key Insights
* Employees working overtime are more likely to leave the organization
* Lower income and fewer years at the company increase attrition risk
* Compensation, job level, and career progression significantly impact retention


## Conclusion

This project demonstrates how HR analytics and machine learning can be used to predict employee attrition and uncover its main drivers. The combination of predictive modeling and SHAP-based explainability provides transparent and actionable insights that can help organizations improve employee retention and make data-driven HR decisions.


## Author
**Anjali Gupta**


### Note
This project was completed as part of an HR Analytics internship assignment and is intended for learning and analytical demonstration purposes.

