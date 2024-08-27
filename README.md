# Credit_Card_Approval_Prediction
## Project Overview:
A bank's credit card department is one of the top adopters of data science. A top focus for the bank has always been acquiring new credit card customers. Giving out credit cards without doing proper research or evaluating applicants' creditworthiness is quite risky. The credit card department has been using a data-driven system for credit assessment called Credit Scoring for many years, and the model is known as an application scorecard. A credit card application's cutoff value is determined using the application scorecard, which also aids in estimating the applicant's level of risk. This decision is made based on strategic priority at a given time Customers must fill out a form, either physically or online, to apply for a credit card. The application data is used to evaluate the applicant's creditworthiness. The decision is made using the application data in addition to the Credit Bureau Score, such as the FICO Score in the US or the CIBIL Score in India, and other internal information on the applicants. Additionally, the banks are rapidly taking a lot of outside data into account to enhance the caliber of credit judgements.

## Project Objective:
The main objective of this assignment is to minimize the risk and maximize the profit of the bank. Bank has to make a decision based on the applicant's profile to minimize the loss from the bank's perspective. Bank considers the applicant's over their nature of work, income range and family orientaion details to take any decision to approve or reject a credit card application. The customer Credit card data contains many features and a classification approach to identify the credit worthiness of an applicant.

In this project we are utilizing the exploratory data analysis (EDA) as a data exploration technique to acquire knowledge, discover new relations, apply new methodologies and unravel patterns in data. It is important to apply the necessary rationale behind each step to address the main objective of the study.

So, The primary objective of this project is to develop a machine learning model for Credit Card Approval Prediction.

## Feature Understanding
Dataset name: (Credit_Card.csv)

Ind_ID: Client ID
Gender: Gender information
Car_owner: Having car or not
Propert_owner: Having property or not
Children: Count of children
Annual_income: Annual income
Type_Income: Income type
Education: Education level
Marital_status: Marital_status
Housing_type: Living style
Birthday_count: Use backward count from current day (0), -1 means yesterday.
Employed_days: Start date of employment. Use backward count from current day (0). Positive value means, individual is currently unemployed.
Mobile_phone: Any mobile phone
Work_phone: Any work phone
Phone: Any phone number
EMAIL_ID: Any email ID
Type_Occupation: Occupation
Family_Members: Family size
Another data set (Credit_card_label.csv) contains two key pieces of information

ID: The joining key between application data and credit status data, same is Ind_ID
Label: 0 is application approved and 1 is application rejected.