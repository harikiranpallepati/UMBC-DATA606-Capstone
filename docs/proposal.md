# 1. Title and Author

- **Project Title:** Customer Churn Prediction in Banking
- **Prepared for:** UMBC Data Science Master Degree Capstone by Dr. Chaojie (Jay) Wang
- **Author:** Harikiran Pallepati
- **GitHub:** https://github.com/harikiranpallepati/
- **LinkedIn:** https://www.linkedin.com/in/harikiran-pallepati-a37b99167/
- **PowerPoint Presentation:** 
- **YouTube Video:** 

# 2. Background

 Bank churn prediction involves using data and machine learning models to predict whether customers are likely to leave or "churn" from a bank. Customer churn is a 
 critical concern for banks, as retaining existing customers is often more cost-effective than acquiring new ones.The significance of Bank Churn Prediction lies in 
 its direct impact on a bank's financial health and customer relationships. Customer churn not only results in revenue loss but also diminishes the bank's 
 competitive position in the market. By accurately predicting churn, banks can implement targeted retention strategies, improve customer service, and tailor 
 offerings to individual needs, ultimately fostering long-term customer loyalty and financial stability.

 **Research Questions:**
1. What factors contribute to customer churn in the banking industry?
2. How effectively can machine learning models predict customer churn in the banking sector based on historical data and customer attributes?
3. What strategies can banks implement to reduce churn and enhance overall customer retention?

# 3. Data

## Data Source:
- Source: kaggle
- Source Link : https://www.kaggle.com/datasets/willianoliveiragibin/bank-churn-prediction

## Data Size
- Size of the dataset is 37MB( 4375700 elements in the dataframe).
- It consists of 175028 rows and 25 columns
- Each row in the dataset likely represents a customer of a bank, with various attributes recorded for each customer

## Data Dictionary
* Surname: Last name of the customer.
* CreditScore: The credit score of the customer.
* Age: Age of the customer.
* Tenure: Number of years the customer has been with the bank.
* Balance: Bank balance of the customer.
* NumOfProducts: Number of bank products the customer is using.
* HasCrCard: Whether the customer has a credit card (binary, 1 or 0).
* IsActiveMember: Whether the customer is an active member (binary, 1 or 0).
* EstimatedSalary: Estimated salary of the customer.
* Exited: The target variable indicating whether the customer exited (churned) or not (binary, 1 or 0).
* Surname_tfidf_0 to Surname_tfidf_4: Features representing TF-IDF values for the customer's surname.
* France, Germany, Spain: Categorical variables indicating the customer's country.
* Female, Male: Categorical variables indicating the customer's gender.
* Mem__no__Products: A combination of membership and number of products.
* Cred_Bal_Sal: A derived feature combining credit score, balance, and salary.
* Bal_sal: A derived feature combining balance and salary.
* Tenure_Age, Age_Tenure_product: Derived features.

## Target variable
The numerical column named 'Exited' column in the dataframe is our target variable which indicates whether customer will churn or not. The binary representation as follows churn(1) or not (0).

