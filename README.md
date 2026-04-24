# Customer Retention Strategy Using Machine Learning
### AWS Machine Learning Engineer Capstone Project

## 📌 Project Overview
In the highly competitive telecommunications sector, the cost of acquiring a new customer is significantly higher than retaining an existing one. This project develops a predictive model to identify "at-risk" customers (Churn Prediction) using the **Telco Customer Churn** dataset. The goal is to provide actionable insights for management to implement proactive retention strategies.

## 🛠️ Technologies & Tools
* **Language:** Python 3.x
* **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn.
* **ML Algorithm:** **XGBoost** (optimized for high F1-Score).
* **Environment:** Google Colab / AWS SageMaker.

## 📊 Methodology
1. **Exploratory Data Analysis (EDA):** Identified key churn drivers such as contract type and monthly charges.
2. **Data Preprocessing:** Handled imbalanced classes and performed feature scaling.
3. **Model Selection:** Evaluated Logistic Regression, Random Forest, and XGBoost.
4. **Hyperparameter Tuning:** Used `GridSearchCV` to optimize XGBoost parameters for better recall and precision.

## 💡 Key Business Insights
* **Contract Impact:** Customers with **Month-to-month** contracts are at the highest risk of churning.
* **Tenure:** New customers (short tenure) require more engagement and loyalty incentives.
* **Incentives:** Proactive loyalty discounts can significantly reduce the churn rate for high-value customers.

## 📂 Project Structure
* `Capstone_Project.ipynb`: Full Python code for analysis and modeling.
* `Project_Proposal.pdf`: The initial design and academic references for the project & Comprehensive documentation of results.

*Developed by Ghaida Alharbi*
