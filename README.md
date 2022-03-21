# About the dataset

The dataset comes from the one of UK debt collection system, and it is related to direct campaigns (phone calls/sms/agreements) and legal actions (lawsuits/obtaining the title/sending motion to bailiff) toward the debtors. 
The anonymised dataset consists of 3470 observations – each row representing one debt, with the variables below:
•	Client: age, gender, subregion etc.
•	Claim: vendor name, account balance, acquisition date etc.
•	Campaign: last contact with debtor, arrangement flag,  last inbound call date etc. 
•	Legal: lawsuit date, execution date, title date etc.
•	Others: payments information, system information

# Business Problem 

The binary target variable is set as 1 if there has been a positive payment on the account in the 3 months after the observation date; otherwise the target variable takes a value of zero.
The classification goal is to predict whether the debtor will pay within the observation period (1/0) with the secondary objective of predicting/maximising the cash. (Target amount)


