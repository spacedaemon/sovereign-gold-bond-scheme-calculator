# Sovereign Gold Bond Scheme Calculator

The idea for building this code is credit to the author of this article:
https://profitsolo.com/sovereign-gold-bond-calculator-sovereign-gold-bond-sbi-calculator/
the articles explains about prediction of returns from Soverign Gold Bond Scheme.
## What is Sovereign Gold Bond Scheme (SGBS)?
A investment scheme by Government of India and issued by Reserve Bank of India. To know more about Soverign Gold Bond Scheme (SGBS) just do a self service doing Google Search.

## What this program do?
I was learning OOP on python and managed to build this program. 

The program predicts the expected returns on investing in the SGBS. It predicts the price movement as per the historical CAGR value of Gold in past 5 years.
A user can change the value of CAGR. In the examples I have taken the value 9.2%.

The syntax for the code is:
> test = SoverignGoldBond(ISSUE_PRICE, UNITS, CAGR, YEAR).

The meaning of the variables are and how input the variables.
ISSUE_PRICE = the price at which the Government has issued the bond. Generally, it is pegged to the current gold price.
UNITS = the number of units the buyer wants to purchase. The input value should be a whole number.
CAGR = the compounded annual growth rate (CAGR) of the Gold Price. It is generally, the price at which price of gold increase in a 5-year period or 10-year period. It is upto the user to determine the cagr. The input value should be in float.
YEAR = The value should be in whole number, meaning 5, 10 or 12. User should now use the calander year such as 2020, 2022 or 2025.

## How to view the prediction results?

For viewing the prediction results, after initialization of the code. 

You can use the following inputs:

> test.GenerateTable()

this will generate a table with 6 coloumns. The inspiration of the coloumn structure is taken from the profitsolo page mentioned above.

The another table which gives the final verdict of the prediction is as below:

> test.FinalAssessmentTable()

the result will output the return earned, the final value of the bond while invested and the ROI earned by the investor.

https://www.linkedin.com/in/nishit-paul-76357868/
