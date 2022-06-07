# Lending club case study
> This case study aims to find driving factors behind loan default.


## Table of Contents
* [General Info]
* [Technologies Used]
* [Conclusions]
* [Acknowledgements]


## General Information
Lending Club is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.


## Conclusions
Based on univariate analysis, there is high probability of defaulting for following condition -

*Applicants who use the loan to clear other debts
*Applicants who receive interest at the rate of 13-17%
*Applicants who have an income of range 31k - 58k
*Applicants who have 20-37 open_acc
*Applicants with employement length of 10
*When funded amount by investor is between 5000-10000
*Loan amount is between 5k to 10k
*Dti is between 12-18
*When monthly installments are between 145-274.
*Term of 36 months
*When the loan status is Not verified
*When the purpose is 'debt_consolidation'
*Grade is 'B'
*Loan is issued in December month.

Based on Bivariate Analysis, there is high probability of defaulting for the following conditions -

*Applicants taking loan for 'home improvement' and have income of 60k -70k
*Applicants whose home ownership is 'MORTGAGE and have income of 60-70k
*Applicants who receive interest at the rate of 21-24% and have an income of 70k-80k
*Applicants who have taken a loan in the range 30k - 35k and are charged interest rate of 15-17.5 %
*Applicants who have taken a loan for small business and the loan amount is greater than 14k
*Applicants whose home ownership is 'MORTGAGE and have loan of 14-16k
*When grade is F and loan amount is between 15k-20k
*When employment length is 10yrs and loan amount is 12k-14k
*When the loan is verified and loan amount is above 16k
*When the loan term is 60 Months

## Technologies Used
*jupyter notebook(anaconda3)
*EDA
*python
*pandas
*numpy
*seaborn
*matplotlib



## Acknowledgements

- This project was inspired by Exploratory data Analysis module


## Contact
Created by https://github.com/Tanisha123
