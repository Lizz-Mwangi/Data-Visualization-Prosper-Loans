# Prosper Loans Dataset Exploration
## by Lizz Mwangi


## Dataset

This document explores a data set containing 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. I used a subset of the data with the main loan features that I would use in the analysis.Most importantly, I merged CreditGrade (for loans prior to 2008) and ProsperRating (Alpha) (for loans after 2009)columns to ProsperRating since they contained the same data.

## Summary of Findings
I observed that the borrower APR is negatively correlated with original loan amount.Large Loan amounts have a low Borrower APR. The lenders/investors are more likely to earn more from borrowers that borrow small amounts. Also, Borrower's prosper rating determines the loan amount they are likely to get. The better the prosper rating a borrower has, the more likely they are to get a large amount of loan given to them.
Another observation was that from a Borrower's Prosper Rating, you can predict whether they will complete or default. I observed that most of the defaulted loans were from the borrowers with a High Risk Prosper Rating. Also, the lowest number of borrowers that have completed paying their loans have a High Risk Rating.
Looking at the employment status of a borrower, Employed borrowers get larger amounts of loans as compared to any other group.
Stating your employment status as 'Other' reduces your chances of getting a large loan amount.

Outside of the main variables of interest, I noticed that there are borrowers with good prosper ratings, A and C to be specific, whose loans are past their due date. Surprisingly, their loan amounts are very low, 2500 and below. I would expect these borrowers to clear their loans in time, especially because they are small amounts and they have a pretty good prosper rating.


## Key Insights for Presentation

For the presentation, I focus on the main features of interest that could affect the borrower APR, which are Loan Original Amount, Prosper rating and Employment Status. 
I'll start investigating the distribution of borrower APR. Using boxplots, I'll then show the relationship between BorrowerAPR, LoanOriginalAmount, Prosper Rating and Employment Status. Showing the effect of Prosper Rating on Borrower's APR and Loan Original Amounts using point plots follows.

Outside the main variables of interest, I investigated the association between Prosper Rating, Loan Original Amount and Loan Status