# HR-Analytics-Employee-Attrition-Prediction
Project: HR Analytics – Employee Attrition Prediction

This project focuses on analyzing and predicting employee attrition using the IBM HR Analytics Employee Attrition & Performance dataset. The primary objective is to understand the key factors that contribute to employees leaving the organization and build predictive models that can help HR departments take proactive measures to improve retention.

Employee attrition is one of the biggest challenges faced by companies, as it leads to increased hiring costs, loss of knowledge, and lower employee morale. By leveraging data analytics and machine learning, organizations can identify at-risk employees and design strategies that encourage retention and improve workplace satisfaction.

🔍 Problem Statement

The challenge is to predict whether an employee is likely to leave the company based on multiple factors such as age, salary, job role, work-life balance, distance from home, overtime, and more. In addition, the project aims to identify the most significant features that drive attrition, enabling HR managers to take corrective actions.

🛠️ Approach

Data Cleaning & Preprocessing

Removed irrelevant columns such as EmployeeNumber, Over18, and StandardHours.

Encoded categorical variables using Label Encoding.

Scaled numerical features using StandardScaler.

Exploratory Data Analysis (EDA)

Visualized attrition counts to understand imbalance in the dataset.

Analyzed attrition across departments, job roles, and other factors.

Highlighted patterns such as higher attrition among employees doing overtime.

Modeling

Logistic Regression: Interpretable model used to identify key positive and negative drivers of attrition.

Random Forest Classifier: Robust ensemble model used to extract feature importance and improve prediction accuracy.

Model Evaluation

Used metrics such as accuracy, confusion matrix, and classification report.

Compared performance of Logistic Regression and Random Forest.

🎯 Outcomes & Insights

Logistic Regression revealed top drivers such as Overtime, Job Role, Age, and DistanceFromHome.

Random Forest emphasized Monthly Income, Job Level, and Work-Life Balance as significant contributors.

The models achieved an accuracy of around 78–80%, making them useful for real-world HR decision-making.

This project demonstrates how data-driven HR analytics can play a vital role in reducing employee turnover and building a healthier workplace.
