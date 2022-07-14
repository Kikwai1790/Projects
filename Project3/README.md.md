**Data Description**

"On November 24, 2008, the SEC found Prosper to be in violation of the Securities Act of 1933. As a result of these findings, the SEC imposed a cease and desist order on Prosper ... In July 2009, Prosper reopened their website for lending ("investing") and borrowing after having obtained SEC registration for its loans ("notes"). After the relaunch, bidding on loans was restricted to residents of 28 U.S. states and the District of Columbia. Borrowers may reside in any of 47 states, with residents of three states (Iowa, Maine, and North Dakota) not permitted to borrow through Prosper".

### What is the structure of our Dataset?

There are 113937 loans in the dataset and 25 features(LoanStatus,BorrowerAPR,Occupation,EmploymentStatus etc.).Three are 12 numeric
variables(DebtToIncomeRation,Term,BorrowerRate,ProsperScore etc.),one bool variable(IsBorrowerHomeowner) and 8 categorical variables
with three ordered(IncomeRange, ProsperRating(Alpha) and CreditScore)

    CreditScore: Poor,Fair,Good,Very Good
    ProsperRating(Alpha): $0, $1-24,999, $25,000-49,999, $50,000-74,999, $75,000-99,999, $100,000+
    IncomeRange: HR, E, D, C, B, A, AA

### What is/are main feature(s) of your interest in your dataset?

my interest are features affecting LoanStatus

### What features in the dataset do you think will help support your investigations into your feature(s)of interest?

To help with my investigations I strongly believe BorrowerAPR,EmploymentStatus,Term,Occupation,LoanOriginationAmount will affect
LoanStatus with some other features

**Findings**

From the plot majority of loans are performing very Good and Good while a very small numbure of loans perform pororrly and Fairly
From IncomeRange loan anlaysis a number of loans borrowers falls between (25,000-49,999) followed  by  (50,000-74,999)
Majority of loan borrowers prefer loan payment of 36 months(3 years)
From the LoanStatus analysis we see a number of loans borrowers are  servicing,followed by fully serviced loans as completed with
chargeoff comming third
Califonia(CA) is the leading state,followed by Texas(TX) with Newyork(NY) and Florida(FL) closing on the top 4 biggest states
with loans
Employed person are the most loan borrowers with Full-time comming second
From the transormed distribution,there are anumber of spikes around 4k,10k,15k,this is insighful

From the LoanStatus vs Borrower past dues loans have higher Annual Rate
From the plot 36 months still the most prefered payment plan per the loan status from the three most LoanStatuses,Very good 
rating score tops the currentstatus followed by Good scores.The employed are the active and many borrowers with current loans
while full-time employees are many who have completed their loans.
Analysis from the IncomeRange shows a number of current loans are borrowers with income range of $ 50,000-74,999.
IncomeRange of 25,000-49,999 borrowers are majority who have cleared their loan

we can see that as the a negative relationship in the current loan status loan amount increases  the Annual rate 
increases
Past Due loans have higher Annual interest(BorrowerAPR) in all types of employment status


```python

```
