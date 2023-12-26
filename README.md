
## Predicting Customer Churn using Machine Learning Model

The objective of this project is to construct a machine learning model for analyzing customer attrition in the Vodafone telecom company. Leveraging any available dataset, the model will produce predictions by effectively discerning whether a customer is inclined towards churning or not. This endeavor is designed to yield significant insights into customer behavior, enabling the early identification of potential churn and facilitating strategic interventions to retain customers proactively. The anticipated outcome of this project is expected to enhance customer relationship management at Vodafone by providing a more informed and proactive approach to addressing customer churn.


I express gratitude to Azubi Africa for granting me access to the dataset used in this project. The data has been segmented into three separate parts. The primary dataset was housed in a Microsoft SQL Server, and I established a remote connection to it utilizing the pyodbc library. The second dataset, formatted as a CSV file, was retrieved from a GitHub repository. The third dataset, designated as the test dataset, was located on OneDrive, also presented in CSV format.


## Project Tools

# Programming Language:
Python

# Integrated Development Environment (IDE):
VSCode: A general-purpose IDE with robust support for Python development.

# Libraries and Frameworks:
scikit-learn
Pandas
NumPy

# Data Visualization:
Matplotlib
Seaborn

# Version Control:
Git: Essential for version control, collaboration, and tracking changes in code.

The dataset encompasses information on various aspects, including:

# 1.Customer Churn:

The presence of customers who have left the company is indicated by the "Churn" column.

# 2.Services Subscribed by Customers:

Details about the services each customer has signed up for, such as phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies.

# 3.Customer Account Information:

Customer account details include tenure (how long they've been a customer), contract type, payment method, paperless billing preference, monthly charges, and total charges.

# 4.Demographic Information:

Demographic data includes gender, age range, and whether the customer has partners and dependents.

Additional details about the demographic information are as follows:

CustomerID: A unique identifier for each customer.

Senior Citizen: Indicates if the customer is a senior citizen (Yes/No).

Dependents: Indicates if the customer lives with any dependents (Yes/No), where dependents could be children, parents, grandparents, etc.

Tenure in Months: Represents the total number of months the customer has been with the company.

Total Charges: Calculated as the product of tenure and monthly charges.
Multiple Lines: Indicates whether the customer subscribes to multiple telephone lines with the company (Yes/No).
