# Defaulting Credit Card Payment Prediction

________________________________________________________
By Jose Antonio Villegas

April 2022

![image](https://user-images.githubusercontent.com/95902075/162502681-9c2ef8f1-219b-4e7b-896d-ef6a527578e0.png)


--------------------------------------
## Project Description
--------------------------------------

Credit Cards


A credit card is a card issued to consumers that is used to make purchases, with the agreement that the cardholder will ultimately pay back the card issuer for the cost of the items purchased, along with any agreed upon fees and interest, should they be assessed. Essentially, a credit card acts as a loan that allows you to make purchases now and pay them back (often with interest) later.

A credit card, used wisely, is one of the most effective financial payment tools available to consumers of all ages. You usually have a grace period between 21 and 30 days after the close of the billing cycle to pay back any money without interest.

After that, you may accrue interest depending on your card (unless your card offers a 0% interest promotional rate for a period of time). Credit cardholders will be charged interest on the amount borrowed and will be expected to make (at least) minimum monthly payments until the balance is paid off.

How Credit Cards Work
Credit cards come with a maximum amount of money (known as a credit limit) which can be used over a specific period of time. That credit limit is determined in large part by the credit cardholder's credit scores and reports, which the credit card company will review before granting approval to the credit card applicant.

When using the card to buy goods or services, the cardholder is authorizing the credit card company to make the purchase for them, with the promise to pay the exact amount back at a later date.

Credit card companies will log the purchase and add it to the credit cardholder's statement and issue a bill at the end of the billing period tallying all the credit cardholder's purchases, the amount of each purchase, and the total amount owed on those purchases.

The card issuers will add an interest charge to any account balance that isn't paid on or before the invoice due date. Added interest is a detriment to cardholders, as that interest compounds over time, as long as there is an unpaid balance.


---------------------------------------
# Objective
_____________________________

  The objective of this project is to predict credit card holders who will default on their monthly payments based on data gathered on each cardholder. 

  
## Dataset Source

Source : https://www.kaggle.com/surekharamireddy/credit-data



## Feature and Description

### CARDHLDR      -1 if application for credit card accepted, 0 if not 
### DEFAULT       -1 if defaulted 0 if not (observed when CARDHLDR=1, 10,499 observations)
### AGE           -Age in years plus twelfths of a year
### ACADMOS       -months living at current address
### ADEPCNT       -number of dependents
### MAJORDRG      -Number of major derogatory reports
### MINORDRG      -Number of minor derogatory reports
### OWNRENT       -1 if owns their home, 0 if rent
### INCOME        -Monthly income (divided by 10,000)
### SELFEMPL      -1 if self employed, 0 if not
### INCPER        -Income divided by number of dependents
### EXP_INC       -Ratio of monthly credit card expenditure to yearly income
### SPENDING      -Average monthly credit card expenditure (for CARDHOLDER = 1)
### LOGSPEND      -Log of spending


__________________________________________________________

# Correlation of Data Features to the Target Default

____________________________________________________________


![image](https://user-images.githubusercontent.com/95902075/162658858-feab66d8-45d9-467a-9ff9-ab24495c624a.png)


### The correlation matrix shows no strong positive or negative correlations between numeric data.


Other Graphs/Variables that show imbalance in Data
