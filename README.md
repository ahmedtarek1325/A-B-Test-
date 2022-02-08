# Visualization-for-Prosper-Loan-Data
This project is done as a part of Udacity's third project in Advanced Data Analysis nanodegree.  The data description as illustrated by udacity: This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. 


#### Dataset 
- The used data set was ProsperDataLoan one of <a href="https://docs.google.com/document/d/e/2PACX-1vQmkX4iOT6Rcrin42vslquX2_wQCjIa_hbwD0xmxrERPSOJYDtpNc_3wwK_p9_KpOsfA6QVyEHdxxq7/pub">the data set options</a>. You can find the download 
link <a href="https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&amp;sa=D&amp;ust=1581581520570000">here</a>. 
- I have added a csv file named ”tidy_loan.csv” that file has all the 
outliers deleted in addition it includes only the features used in the finalpresentation.inpy 

 

#### Main findings  
- A direct realtionship between the Prosper Rating and loan status was observed. as the rating 
improves the Loan status is more lickley to be completed 
- it's more likely to have their loan status 
o Completed if LoanOriginalAmount < 15k and the monthly Income> 10k 
o Defauted if LoanOriginalAmount > 15k 
- Surprisingly, all the loan amounts that was greater than 15k was defaulted. Even if the 
customer has a prsoper score equals to 10 – from the best cutomers –. 
- Find at the end that there is a threeshold for accepting or rejecting the loan request which is 
depednt on both the loan amount and customer prinicpal Payments. Where for a loan to be 
completed, the customer has to have principal payments greater than the loan amount by 
one thousand dollars.
