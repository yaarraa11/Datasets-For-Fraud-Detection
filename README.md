# Datasets-For-Fraud-Detection

* yara aldossary
* nouf almalki



![TLC logo](https://m.eyeofriyadh.com/directory/images/2020/03/15d36be8f5f3f.jpg)



#  Description

This selected data from the famous data site kaggle represents one of the important data in the detection of financial fraud, and to clarify harmful behavior in evaluating the performance of financial fraud detection methods .



# Data 


 Using a simulator that simulates real financial transactions transferred from a mobile phone within one month in an African country.
 This data contains 6 million rows and 11 columns .
 
 
 
 #  The goal of the  model
 
  Control of huge transfers so that the process is stopped and illegal transfers are reported.
  


# Headers


step - maps a unit of time in the real world. In this case 1 step is 1 hour of time. Total steps 744 (30 days simulation).

type - CASH-IN, CASH-OUT, DEBIT, PAYMENT and TRANSFER.

amount - amount of the transaction in local currency.

nameOrig - customer who started the transaction

oldbalanceOrg - initial balance before the transaction

newbalanceOrig - new balance after the transaction

nameDest - customer who is the recipient of the transaction

oldbalanceDest - initial balance recipient before the transaction. Note that there is not information for customers that start with M (Merchants).

newbalanceDest - new balance recipient after the transaction. Note that there is not information for customers that start with M (Merchants).

isFraud - This is the transactions made by the fraudulent agents inside the simulation. In this specific dataset the fraudulent behavior of the agents aims to profit by taking control or customers accounts and try to empty the funds by transferring to another account and then cashing out of the system.

isFlaggedFraud - The business model aims to control massive transfers from one account to another and flags illegal attempts. An illegal attempt in this dataset is an attempt to transfer more than 200.000 in a single transaction.




# Tools 


pandas - numpy - patsy - seaborn
- matplotlib - sklearn 