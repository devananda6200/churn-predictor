## Customer Churn Prediction

Customer attrition or churn, is when customers stop doing business with a company. It can have a significant impact on a company's revenue and it's crucial for businesses to find out
the reasons why customers are leaving and take steps to reduce the number of customers leaving. One way to do this is by identifying customer features that are at risk of making them leave such as Phone service(in case 
of a telecom company), previous accusations, rumours, bad service etc. and implementing retention strategies to keep them. Also, by using data and machine learning techniques, companies can predict which customers are likely
to leave in the future and take actions to keep them before they decide to leave.


![image](https://github.com/user-attachments/assets/d9484a2f-42e6-48c5-b6d9-2b3a3f9be507)


We are going to build a basic model for predicting customer churn using [Telco Customer Churn dataset](https://www.kaggle.com/blastchar/telco-customer-churn) using  classification algorithms models and identify the reaso for customers leaving, using Python tools such as pandas,scikit-learn for data manipulation and matplotlib for visualizations.

## Installation

To get started, clone the repository and install the required packages:
git clone https://github.com/devananda6200/churn-predictor.git

cd customer-churn

pip install -r requirements.txt

## Steps Involved to Predict Customer Churn
- Importing Libraries
- Loading Dataset
- Exploratory Data Analysis(EDA)
- Outliers using IQR method
- Cleaning and Transforming Data
    - One-hot Encoding
    - Rearranging Columns
    - Feature Scaling
    - Feature Selection
- Prediction using Logistic Regression
- Prediction using Support Vector Classifier
- Prediction using Decision Tree Classifier
- Prediction using KNN Classifier


