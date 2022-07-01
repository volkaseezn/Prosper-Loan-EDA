# ProsperLoan Dataset Exploration
## by Volker Felvic Katche Tachin


## Dataset

> This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.
> Dataset can be found here (https://www.google.com/url?q=https://www.google.com/url?q%3Dhttps://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv%26amp;sa%3DD%26amp;ust%3D1581581520570000&sa=D&source=editors&ust=1656646934459543&usg=AOvVaw39GC5mrViQ7GyZunX_bQYv)
> An overview of the data features can be found at (https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0)

> My selected features for exploration are `ListingCreationDate, CreditGrade, Term, LoanStatus, ProsperRating (numeric), ProsperScore, ListingCatergory, EmploymentStatus, IncomeRange, TotalProsperLoans, TotalProsperPaymentsBilled, Recommendations`


## Summary of Findings

- The BorrowerAPR and BorrowerRate column appears to be mostly normally distributed. Most of the loans have a credir grade between C, D, and B A little short of 48% of loans are current. 32% of them are completed
- Most loaners are employed, followed by full-time. Most loanees have received loans a total of once, or twice. 
- Most loans are done over a 36 month period. 
- The lower prosper scores seem to have higher Borrower rates compared to the higher prosper scores
- The lower credit grades seem to have higher borrower APRs, while the higher credit grades have the lower borrower APRs
- The Not employed group of loanees have the highest median statistic for borrower rate.
- The lower prosper scores seem to have higher Borrower rates compared to the higher prosper scores The lower credit grades seem to have higher borrower APRs, while the higher credit grades have the lower borrower APRs
- The loanees with the shortest loan terms have the lowest borrower rates, with the lowest beign from the fulltime employed loanees. The highest borrower rate is taken by the loanees without employments, with a 36 month plan


## Key Insights for Presentation

> I focused on Borrower Rate for presentation. Relationships are made between other features and these two in the presentation. Changes I made to my design include legend titles, axis labels, and titles.
