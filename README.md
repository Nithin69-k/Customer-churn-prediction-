# Customer-churn-prediction-
Customer churn refers to when subscribers stop using a company’s services and switch to competitors. In the telecom industry, churn rates can be as high as 15–25% annually due to intense competition. Retaining existing customers is more cost-effective than acquiring new ones. Machine Learning helps by identifying at-risk customers early, allowing
Telecom_Customer_Churn_Prediction
Repository navigation
Code
Issues
Pull requests
Customer churn refers to when subscribers stop using a company’s services and switch to competitors. In the telecom industry, churn rates can be as high as 15–25% annually due to intense competition. Retaining existing customers is more cost-effective than acquiring new ones. Machine Learning helps by identifying at-risk customers early, allowing

 1 star
 0 forks
 0 watching
 Branches
 Tags
 Activity
Public repository
praveengouda25/Telecom_Customer_Churn_Prediction
Name	
praveengouda25
praveengouda25
6 months ago
Dataset
6 months ago
Power-BI Dashboard
6 months ago
icons
6 months ago
outputs
6 months ago
README.md
6 months ago
TelecomCustomerChurn.ipynb
6 months ago
output
6 months ago
Repository files navigation
README
github linkedin

Telecom Customer Churn Prediction
Customer Churn

📌 Introduction
Customer churn refers to when subscribers stop using a company’s services and switch to competitors.
In the telecom industry, churn rates can be as high as 15–25% annually due to intense competition.

Retaining existing customers is more cost-effective than acquiring new ones.
Machine Learning helps by identifying at-risk customers early, allowing targeted retention strategies.
This project uses ML models to predict churn and highlight factors influencing customer decisions.
🎯 Objectives
Calculate the % of churn vs retained customers.
Analyze key drivers responsible for churn.
Train ML models to classify churn vs non-churn customers.
Recommend the best-performing model for real-world deployment.
📂 Dataset
We used the Telco Customer Churn dataset.

📊 Power BI Dashboard
Along with Machine Learning models, a Power BI dashboard was created to provide interactive insights into customer churn.
This dashboard helps stakeholders visualize churn drivers and explore customer segments at risk.

🔹 Key Features of the Dashboard:
Churn Rate Overview – % of customers who left vs retained.
Customer Demographics – Breakdown by gender, senior citizen, dependents.
Account & Services – Contract type, billing methods, internet & security services.
Revenue Impact – Monthly charges vs churn behavior.
Drill-Down Analysis – Ability to filter customers based on churn risk.
📷 Dashboard Preview
Customer Churn Dashboard

📂 Dashboard File
You can explore the interactive Power BI dashboard by downloading the .pbix file:

👉 Telecom_Customer_Churn_Dashboard.pbix

Features include:

Churn status – Whether the customer left within the last month.
Services – Phone, internet, streaming, online security, tech support, etc.
Account info – Contract type, billing, monthly & total charges, tenure.
Demographics – Gender, senior citizen, dependents, partners.
🛠️ Tech Stack
Programming: Python
Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
Deployment: Flask
Visualization: Matplotlib / Seaborn
🔎 Workflow
Data Preprocessing – Handle missing values, encode categorical data, scale features.
EDA – Analyze churn distribution & customer behavior.
Feature Engineering – Extract meaningful variables.
Model Training – Logistic Regression, Decision Tree, Random Forest, KNN, Naive Bayes, Ensemble methods.
Evaluation – Accuracy, Precision, Recall, F1-score, ROC-AUC.
Deployment – Flask app for churn prediction.
📊 Exploratory Data Analysis (EDA)
1. Churn Distribution
Churn distribution

~26% of customers switched providers.

2. Churn vs Gender
Churn wrt Gender

Both genders show similar churn behavior.

3. Contract Types
Contract distribution

Customers with Month-to-Month contracts are most likely to churn.

4. Payment Methods
Payment Methods
Payment wrt Churn

Customers paying via Electronic Check churn more frequently.

5. Internet Services
Internet Services

Customers with Fiber Optic services show higher churn.

6. Dependents
Dependents

Customers without dependents churn more.

7. Online Security
Online Security

Lack of online security services increases churn risk.

8. Senior Citizens
Senior Citizen

Senior citizens have a higher churn rate.

9. Billing
Billing

Customers with Paperless Billing are more likely to churn.

10. Tech Support
Tech Support

Lack of Tech Support drives higher churn.

11. Charges & Tenure
Monthly Charges Total Charges
Tenure

New customers and those with high monthly charges churn more.

🤖 Machine Learning Models
Models Implemented
Logistic Regression
KNN
Naive Bayes
Decision Tree
Random Forest
AdaBoost
Gradient Boost
Voting Classifier
Results after K-Fold Cross Validation
Model Evaluation

Best Model: Voting Classifier (~85% Accuracy).

Results after K fold cross validation:
📊 Model Performance Visualizations
Linear Regression

KNN

Naive Bayes

Decision Tree

Random Forest Adaboost Gradient Boost Voting Classifier

Confusion Matrix0
