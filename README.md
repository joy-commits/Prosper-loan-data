# Prosper Loan Data Exploration
## by Ufuoma Ejite


## Dataset and Data Source

[Prosper](https://www.prosper.com/) was founded in 2005 as the first peer-to-peer lending marketplace in the United States. Since then, Prosper has facilitated more than $21 billion dollars in loans to more than 1,300,000 people. <br />
The data consists of information regarding 113937 loan listings. The dataset can be found [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv),
with features documentation available [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0).

## Tools Used <br>
- Pandas🐼 <br>
- Seaborn <br>
- Matplotlib <br>
- Jupyter

## Summary of Findings

In this exploration, I observed that there was a strong relationship between the
borrower's APR and lender's yield (the higher the APR, the higher the lender's 
yield and vice versa). Also, the smaller loan amounts had higher APRs compared 
to the larger loan amounts. Loans that have a Loan Term of 36 months have more 
number of investors compared to loans of 12 months and 60 months.
Furthermore, the higher the Prosper Score, the lower the Borrower APR, the
Borrower Rate and the Lender Yield.
Most persons took loans between the range of $3000 and $5000. Year 2013 had the 
highest number of borrowers and the state with the highest number of borrowers was California (CA).
Most of the borrowers are employed and earned within the range of $50000 and $74999. 
On the basis of Listing Category, most loans were collected on the basis of 
debt consolidation. Most of the loans had a Prosper Rating of C, which indicates 
medium risk associated with the loan listing.
The loan term with the highest distribution is 36 months. Most of the loans had Prosper scores of 
4.0, 6.0 and 8.0. 
Majority of the loans have an interest rate of 31%. Most loans had an annual percentage rate (APR) of 35%.
The higher the APR, the higher the lender's yield and vice versa. The smaller loan amounts had higher APRs compared to the larger loan amounts. Loans that have a Loan Term of 36 months have more number of investors 
compared to loans of 12 months and 60 months
The higher the Prosper Score, the lower the Borrower APR, Borrower Rate and Lender Yield


## Key Insights for Presentation

The key insights gotten from exploratory analysis on Prosper Loan data is as follows: <br>
1. Most loans had an annual percentage rate (APR) of 35%.
2. The higher the Borrower APR, the higher the lender's yield and vice versa.
3. The higher the Prosper Score, the lower the Borrower APR, the Borrower Rate and the Lender Yield
