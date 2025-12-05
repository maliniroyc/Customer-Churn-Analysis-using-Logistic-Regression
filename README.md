### 1. Project Title:
 ## Customer Churn Prediction Using Logistic Regression – Telco Dataset

### 2. Problem Statement / Objective:

The objective of this project is to analyze customer behavioral and service-related data to understand the key factors that drive churn in a telecommunications business. The goal is to build a Logistic Regression model that predicts whether a customer is likely to churn, enabling data-driven strategies to improve customer retention.

### 3. Data Source:

- The dataset used in this project is the Telco Customer Churn dataset, publicly available on Kaggle. Link : https://www.kaggle.com/datasets/blastchar/telco-customer-churn
- It includes customer demographic details, account information, service usage patterns, billing details, and churn status.

### 4. Tools & Technologies Used:

- Python

- Jupyter Notebook

- Pandas, NumPy, Scikit-learn

- Matplotlib, Seaborn

- Machine Learning – Logistic Regression

### 5. Tasks Performed (Step-by-Step):
**Step 1: Data Import and Initial Exploration**

I imported the dataset into Python and reviewed the structure of the data, examined available columns, and identified missing or inconsistent values. I also checked the overall shape of the dataset and verified data types for further processing.

**Step 2: Data Cleaning and Preprocessing**

I performed data cleaning by handling missing values, correcting data types, removing duplicates, and preparing the dataset for modeling. I converted categorical variables into numerical formats using encoding techniques and standardized numerical fields to improve model performance.

**Step 3: Feature Engineering**

I engineered additional features such as tenure groups and transformed certain billing variables to better capture customer behavior. I also converted the target variable (Churn) into a binary numerical format suitable for Logistic Regression.

**Step 4: Exploratory Data Analysis (EDA)**

I conducted EDA to understand churn patterns and visualized key trends using charts and graphs. This included analyzing distributions of tenure, contract types, payment methods, monthly charges, and identifying the characteristics of customers with higher churn probability.

**Step 5: Model Development**

I split the data into training and testing sets and built a Logistic Regression model. I trained the model on the cleaned and processed data, tuned hyperparameters where necessary, and prepared the model for evaluation.

**Step 6: Model Evaluation**

I evaluated the model using metrics such as accuracy, precision, recall, F1-score, confusion matrix, and ROC-AUC. These metrics helped assess how well the model could distinguish between customers who churn and those who stay.

**Step 7: Model Interpretation & Insights**

I interpreted the Logistic Regression coefficients to understand which factors most strongly influence churn. I documented the high-risk customer groups and generated insights useful for business decision-making and customer retention improvement.

### 6. Key Insights or Results:

- Customers with month-to-month contracts showed significantly higher churn rates compared to long-term contract holders.

- Customers paying via electronic check had a higher likelihood of churn.

- New customers with low tenure were more likely to churn than long-term subscribers.

- The Logistic Regression model performed well and clearly highlighted risk drivers, enabling actionable retention strategies.

### 7. Project Duration:

- Estimated Weekly Hours: 6–8 hours/week

- Total Duration: 3–4 weeks

- Overall Time Spent: Approximately 24–32 hours


