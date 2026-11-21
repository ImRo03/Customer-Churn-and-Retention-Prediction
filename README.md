# Customer Churn and Retention Prediction

## Project Overview

This project focuses on analysing customer churn and building machine learning models to predict which customers are likely to leave a company.

The goal is to understand customer behaviour, identify patterns related to churn and suggest possible ways to improve customer retention.

## Dataset

- **Dataset:** IBM Telco Customer Churn
- **Total records:** 7,043 customers
- **Total features:** 21 columns
- **Target variable:** Churn

The dataset contains customer information such as tenure, contract type, internet service, monthly charges and payment method.

## Project Workflow

1. Data loading and understanding
2. Data cleaning and preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature preparation
5. Model building
6. Model evaluation and comparison
7. Feature importance
8. Customer retention recommendations

## Machine Learning Models

The following models were trained and compared:

- Dummy Classifier (Baseline)
- Logistic Regression
- Balanced Logistic Regression
- Random Forest
- XGBoost

## Model Results

| Model | Accuracy | Churn Precision | Churn Recall | Churn F1-score |
|---|---:|---:|---:|---:|
| Dummy Classifier | 73.46% | 0.00% | 0.00% | 0.00% |
| Logistic Regression | 80.55% | 65.72% | 55.88% | 60.40% |
| Balanced Logistic Regression | 73.81% | 50.43% | 78.34% | 61.36% |
| Random Forest | 78.42% | 62.15% | 47.86% | 54.08% |
| XGBoost | 80.34% | 66.33% | 52.67% | 58.72% |

## Key Findings

- Month-to-month contract had the highest importance score in the XGBoost model.
- Fiber optic internet and tech support were also among the important features.
- Customers who left had shorter average tenure than customers who stayed.
- Customers who left also had higher average monthly charges.
- Month-to-month customers had a higher churn rate than customers on longer contracts.

## Customer Retention Recommendations

- Offer suitable benefits to encourage longer-term contracts.
- Provide better support to new customers.
- Review monthly pricing and available plans.
- Make technical support and online security services easier to access.
- Check customer feedback about internet service.

These are suggestions based on patterns in the dataset and should be tested before being treated as proven solutions.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

## Conclusion

This project helped me understand customer churn, work with real-world customer data and apply different classification algorithms. It also helped me compare model performance and understand how machine learning can support customer retention decisions.
