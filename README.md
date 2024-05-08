# Loan-Prediction
### What is Loan?
A loan is a credit transaction under which one party—a borrower—obtains from another—the lender—something, usually money or assets, that the borrower must subsequently repay with interest to the lender over a given period of time. Loans may be either short-term or long-term, disbursed to individuals, businesses, and governments for various purposes, such as to purchase real estate, automobiles, consumer goods, finance education, establish or expand a business, or for other, emergency, needs. The terms of a loan usually incorporate the amount of principal (the initial amount lent), the interest rate (the cost of the loan), repayment terms, such as the frequency and length of the period of time in which interest and principal must be paid back, and the conditions that are linked to the loan.

## Introduction

For this loan prediction model using LendingClub's dataset from 2007 to 2010, **Decision Trees** and **Random Forests** were employed as the chosen machine learning algorithms. Following data preprocessing and feature engineering, the dataset was split into training and testing sets. The Decision Trees and Random Forest models were trained on the training data and tuned for optimal performance, leveraging techniques like cross-validation. Model evaluation was conducted using metrics such as accuracy, precision, recall, and F1-score. Additionally, feature importance analysis aided in understanding the key factors influencing loan prediction. Finally, the trained model was deployed and monitored in a production environment to ensure ongoing effectiveness and reliability.


## Dataset 
We will use lending data from 2007-2010 and be trying to classify and predict whether or not the borrower paid back their loan in full. 

You can download the data from [here](https://www.lendingclub.com/info/download-data.action) or just use the csv already provided. 

It's recommended you use the csv provided as it has been cleaned of NA values.

### Columns:
* **credit.policy**: 1 if the customer meets the credit underwriting criteria of LendingClub.com, and 0 otherwise.
* **purpose**: The purpose of the loan (takes values "credit_card", "debt_consolidation", "educational", "major_purchase", "small_business", and "all_other").
* **int.rate**: The interest rate of the loan, as a proportion (a rate of 11% would be stored as 0.11). Borrowers judged by LendingClub.com to be more risky are assigned higher interest rates.
* **installment**: The monthly installments owed by the borrower if the loan is funded.
* **log.annual.inc**: The natural log of the self-reported annual income of the borrower.
* **dti**: The debt-to-income ratio of the borrower (amount of debt divided by annual income).
* **fico**: The FICO credit score of the borrower.
* **days.with.cr.line**: The number of days the borrower has had a credit line.
* **revol.bal**: The borrower's revolving balance (amount unpaid at the end of the credit card billing cycle).
* **revol.util**: The borrower's revolving line utilization rate (the amount of the credit line used relative to total credit available).
* **inq.last.6mths**: The borrower's number of inquiries by creditors in the last 6 months.
* **delinq.2yrs**: The number of times the borrower had been 30+ days past due on a payment in the past 2 years.
* **pub.rec**: The borrower's number of derogatory public records (bankruptcy filings, tax liens, or judgments).

## Contacts
If any better changes can be done to the code, pls contact me!

Email: mukundangopalachary@gmail.com

Linkedin: [Mukundan Gopalachary](https://www.linkedin.com/in/mukundan-gopalachary-997075283/)
