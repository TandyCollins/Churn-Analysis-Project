Telco Customer Churn Analysis
Table of Contents
Project Overview

Dataset

Key Findings & Insights

Model Performance

Business Recommendations

Tools Used

How to Use This Repository

Project Overview
This project identifies the key factors driving customer churn in the telecommunications industry. By developing a predictive model, we can identify "at-risk" customers before they leave, allowing for targeted retention strategies.

Dataset
The dataset contains information on 7,043 customers.

Pre-processing: The data was expanded to 31 features using One-Hot Encoding to ensure all categorical variables were machine-readable.

Features Included: Senior Citizen status, tenure, monthly charges, and total charges.

Target Variable: Churn (encoded as 0 or 1).

Key Findings & Insights
Baseline Churn: The dataset reveals a baseline churn rate of 26.54%.

Fiber Optic Risk: InternetService_Fiber optic is the strongest positive predictor of churn, indicating a high likelihood of customers leaving this specific service tier.

Contract Retention: Contract_Two year and Contract_One year are the most significant factors in preventing churn.

Billing Friction: PaperlessBilling and PaymentMethod_Electronic check are positively correlated with churn, suggesting process-related friction.

Model Performance
A Logistic Regression model was utilized for classification.

Overall Accuracy: 82.19%.

Precision (Class 1): 0.69, meaning 69% of predicted churners were correct.

Recall (Class 1): 0.60, indicating the model identifies 60% of all actual churners.

Business Recommendations
Quality Audit: Address potential service quality issues in the Fiber Optic segment to reduce its high churn impact.

Contract Migration: Focus on moving "Month-to-month" users toward 1-year or 2-year contracts through loyalty incentives.

Automated Billing: Encourage a shift away from Electronic Checks toward automated payment methods to reduce manual billing churn.

Tools Used
Python: (Pandas, NumPy, Scikit-learn)

Visualization: Matplotlib, Seaborn

Environment: VS Code / Jupyter Notebooks