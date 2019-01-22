*Business problem*:
A bank is losing money due to high default rate on its loans. When a customer's loan application has been approved
but the customer is subsequently unable to re-pay his/her loan (via monthly payments), we say s/he has defaulted.
How can the bank reduce its losses/increase its profits?

*Available data*: records of previously approved bank loans; some of them defaulted, some didn't. 
It is reasonable to assume that the records are independent (belong to unrelated people). 
In this notebook, we will basically exmplore and clean the data.

*Data Understanding*: the data consists of **65,000** previously approved bank loan applications stored in a CSV file. 
Each application is described by the following **15 attributes** :
1. **defaulted**: whether the borrower is more than 90 days late, after 2 years of the loan.  This is the target variable.
2. **ID**: Applicant's unique identifier at this bank
3. **gender**: whether the applicant is male or female
4. **marital_status**: whether the applicant single, married, divorced, or widowed.
5. **age_group**: young, middle_aged, senior_citizen
6. **age**: applicant's age in number of years.
7. **nb_dependents**: Number of family members – people who “depend” on the applicant (spouse, children, parents, etc.)
8. **monthly_income**: person's monthly income from various sources (job salary, independent business, etc.)
9. **debt_ratio**: total monthly bills divided by monthly income.
10. **credit_card_balance_ratio**: Total credit card debt divided by credit limit.
11. **nb_open_loans**: Total number of open loans (e.g. car loan, house loan) and credit cards.
12. **nb_special_loans**: Number of mortgage and real estate loans ...
13. **nb_late_payments_1month**: Number of times the borrower was one month late in making monthly payment during the last 2 years.
14. **nb_late_payments_2months**: Number of times the borrower was late by 2-3 months in making monthly payment during the last 2 years.
15. **nb_late_payments_3+months**: Number of times the borrower was more than 3 months late in making monthly payment during the last 2 years. 
