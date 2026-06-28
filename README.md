# Employee Attrition Prediction

## Project Overview
This project aims to predict whether an employee is likely to leave the company using Machine Learning. The project includes data preprocessing, exploratory data analysis (EDA), model building, evaluation, and visualization. The results help HR teams identify employees who may be at risk of leaving and support better employee retention strategies.


## Objectives
- Analyze employee attrition patterns.
- Clean and preprocess the HR dataset.
- Build machine learning models to predict employee attrition.
- Compare model performance.
- Visualize important trends and factors affecting employee attrition.
- Provide business recommendations for HR.

---

## Dataset
**Dataset Name:** HR_Attrition.csv

The dataset contains employee information such as:
- Age
- Department
- Job Role
- Monthly Income
- Years at Company
- Work-Life Balance
- Overtime
- Job Satisfaction
- Education
- Attrition (Target Variable)

Target Variable:
- **Attrition**
  - Yes = Employee Left
  - No = Employee Stayed

---

## Tools & Libraries Used
- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Project Tasks

### Task 1 – Data Loading & Exploration
- Loaded the dataset using Pandas.
- Displayed the first 10 rows.
- Checked dataset shape.
- Identified target and feature columns.
- Counted employee attrition.
- Identified numeric and categorical columns.

### Task 2 – Data Cleaning & Preprocessing
- Checked and handled missing values.
- Removed unnecessary columns.
- Converted the Attrition column into numeric values.
- Applied One-Hot Encoding.
- Scaled numerical features.

### Task 3 – Exploratory Data Analysis
- Analyzed attrition by department.
- Analyzed attrition by job role.
- Compared attrition with monthly income.
- Studied work-life balance and attrition.
- Examined years at company versus attrition.

### Task 4 – Model Building
Built and compared three machine learning models:
- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

### Task 5 – Model Evaluation
Models were evaluated using:
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

### Task 6 – Visualizations
Created the following charts:
- Attrition by Department
- Attrition by Job Role
- Monthly Income vs Attrition
- Confusion Matrix
- Top 10 Feature Importance
- ROC Curve Comparison (Bonus)

### Task 7 – HR Insights
Generated business insights and recommendations to help HR improve employee retention.

---

## Key Findings
- Employee attrition is influenced by multiple factors including monthly income, years at the company, job role, and work-life balance.
- Some departments and job roles experience higher employee turnover.
- Salary alone does not explain attrition; career growth and employee satisfaction also play an important role.
- Early identification of high-risk employees can help HR improve retention.

---

## Business Recommendations
- Improve employee engagement through regular feedback sessions.
- Provide career development and training opportunities.
- Focus retention efforts on departments with higher attrition.
- Promote a healthy work-life balance.
- Recognize employee performance and achievements.

---

## Future Improvements
- Use larger and more recent datasets.
- Apply advanced machine learning techniques.
- Develop a web application for HR teams.
- Include additional employee satisfaction and performance data.

---

## Declaration
This project is created for educational purposes and is my own original work.

