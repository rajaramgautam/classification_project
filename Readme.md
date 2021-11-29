# Hopper-Classification-Project on Telco Churn
 

## About the Project 
Given the access to telco_churn database, we were supposed to acquire data from the telco_churn database and determine the driving factor for customer churn with suitable models whose accuracy will be more than baseline accuracy.

### Goals
Goal of the project is to identify driving factors for churn in customers of Telco Inc and support our argument with classification model whose accuracy will be more than baseline accuracy. I will make recommendations for changes so that it will reduce the monthly customer churn rate and increase customer retention. Thus, we need to find way to retain customers, increasing revenue and with minimum retention cost possible. 


### Project Description
Customers these days have technology in their finger tips to make a decision. They can decide which telecommunication services are best for them based on their needs, budget and deals available on the market. So before customers takes their decision to switch the company for better deals based on their needs and budget. Being data scientists of Telco Inc, we need to use for knowledge of data analysis to suggest company by finding out reasons for customer's churn before its too late. We need to work together with sales and marketing department to bring suitable sales and marketing schemes to increase customer retaation rate. Our decision should be based statistical tools that is supported by data. Our decision should be based on data.


### Initial Questions
- Is gender the driving factor for churn?
- Is internet service type driving factor for churn?
- Is monthly charges driving factor for churn?
- Is payment type driving factor for churn?
- Is senior citizen driver for churn? 

### Data Dictionary
- customer_id: unique identifier for each customer
- senior_citizen: (int) 1 indicates the customer is a senior citizen, 0 indicates they are not
- partner: (int) 1 indicates they have partners, 0 indicates they don’t have partners
- dependents: (int) 1 indicates they have dependents, 0 indicates they don’t have dependents
- tenure: (int) length customer has been with the company in months
- phone_service: (int) 1 indicates they have phone service, 0 indicates they don’t have phone service
- multiple_lines: (int) 1 indicates they have multiple lines, 0 indicates that they don’t
- online_security: (int) 1 indicates customers opted in for online security service, 0 indicates they havent
- device_protection: (int) 1 indicates customers have device protection, 0 indicates they dont
- tech_support: (int) 1 indicates customers have tech support, 0 indicates they dont
- streaming_movies: (int) 1 indicates customers have streaming movie service, 0 indicates they dont
- paperless_billing: (int) 1 indicates customers have enrolled in paperless billing, 0 indicates they havent
- monthly_charges: (int) monthly charge of a customer
- total_charges: (float) total charges customers have paid
- churn: (int) 1 to represent customers that have churned, 0 represent they havent
- partner_dependents: (bool) to represent if customers have both partner and dependents
- phone_and_multiple_lines: (bool) to represent if customers have both phone and multiple lines
- streaming_tv_movie: (bool) to represent if customers have both streaming tv and movie
- online_security_and_backup: (bool) to represent if customers have both online security and back up
- payment_auto: (int) 1 indicates customers have automatic payment, 0 indicates they have not
- month-to-month: (int) 1 indicates customers are with month to month, 0 indicates they have other form of contract
- one year: (int) 1 indicates customers are with one year, 0 indicates they have other form of contract
- two year: (int) 1 indicates customers are with two year, 0 indicates they have other form of contract
- DSL: (int) 1 indicates customers have DSL, 0 indicates they have other form of internet
- fiber optic: (int) 1 indicates customers have fiber optic, 0 indicates they have other form of internet


### Steps to Reproduce

1. An env.py file that contains the hostname, username and password of the mySQL database is created which contains the telco_churn database. env.py file will be stored locally only so that it will never be pushed on github for sercurity purpose. 
2. clone my repo (including the acquireTitanic.py and prepare.Titanic.py) (confirm .gitignore is hiding your env.py file)
3. libraries used are pandas, matplotlib, seaborn, numpy, sklearn. 
 





### Project Planning

### Data Acqusition:

- Acquire data from CodeUp database. You are required to have credentials to access the data base.
- Create a cache in your local repository in order to prevent from having to access the database every time you re-work on the project
- Create acquire.py for reproducibility.

### Data Preparation:
- Summarize data
- Check for duplicates, removed duplicates if present
- Check for null values, missing values, and get count of them
- Check the data types
- Perform feature engineering
- Perform data types conversion/Use Dummy variables
- Drop redundant/useless columns
- Split data into Train, Test, and Validate
- Create prepare.py

### Data Exploration:
- Explore various features and relationships
- Vizualize data
- Impute missing values
- Test different hypothesis

### Model Building
- Try various algorithms(Logit, Random Forest, KNN, Decision Tess) on Train data
- Perform model evaluation
- Pick top 3 perfomring models
- Validate top 3 models on validate data and evaluate their performance
- Pick best performing model on validate data
- Use the top model with test data set and evaluate your model

### Conclusion
- Summarize the process
- Summarize findings
- Make recommendations


