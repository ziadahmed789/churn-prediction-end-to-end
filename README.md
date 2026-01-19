# Customer Churn Prediction – End-to-End Data Science Project

## 📌 Business Problem
Customer churn directly affects company revenue.  
This project aims to predict customers who are likely to churn and provide actionable business insights to reduce churn.

## 📊 Dataset
- Telco Customer Churn Dataset
- 7,043 customers
- Target variable: Churn Value (0 = Not Churned, 1 = Churned)

## 🧠 Project Workflow
1. Exploratory Data Analysis (EDA)
2. Data Cleaning & Feature Selection
3. Handling Missing Values
4. Encoding & Scaling
5. Logistic Regression Baseline Model
6. Model Evaluation & Interpretation

## ⚙️ Machine Learning
- Model: Logistic Regression
- Handling class imbalance: `class_weight='balanced'`
- Recall (Churn): **0.78**
- ROC-AUC: **0.85**

## 📈 Key Insights
- Month-to-month contract customers are more likely to churn.
- Longer customer tenure significantly reduces churn probability.
- Customers using electronic check payment method have higher churn risk.
- Technical support reduces churn likelihood.

## 💡 Business Recommendations
- Target high-risk customers with retention offers.
- Focus retention efforts on customers in their first year.
- Improve service quality for fiber optic customers.

## 🛠️ Tech Stack
- Python
- pandas, NumPy
- scikit-learn
- matplotlib, seaborn

## 🚀 Future Improvements
- Threshold tuning
- Advanced models (Random Forest, XGBoost)
- Cost-sensitive evaluation

## 📊 Dashboard Preview
![Dashboard](DashBoard/Dashboard%201.png)
![Dashboard](DashBoard/Dashboard%202.png)
![Dashboard](DashBoard/Dashboard%203.png)
