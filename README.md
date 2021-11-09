# Lending Club Case Study

Lending club is an online loan market platform, facilitating personal loans, business loans and loans for medical purposes. The objective of this case study is to identify the risky applicants who are likely to default and there by minimize the financial loss to the company by analysing the past data through Exploratory data analysis (EDA).



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information

The case study helps you in developing a basic understanding of risk analytics in banking and financial services and understand how data is used to minimize the risk of losing money while lending to customers. When a consumer finance company receives a loan application, the company must decide for loan approval based on the applicant’s profile. Two types of risks are associated with the company's decision. 

1. If applicant is likely to repay the loan, then not approving the loan will lead to loss of business to the company.
2. If applicant is likely to default the loan, then giving loan will result in financial loss to the company.
When a customer applies for a loan, the company can the following two decisions based on the candidate profile.

Loan accepted: If the company approves the loan, then there are 3 possible scenarios as described below:

a. Fully paid: The loan tenure is completed, and customer has fully paid the loan (Principal and interest)

b. Current: Applicant is paying the instalments and loan tenure is not completed. These candidates are not labelled as 'defaulted'.

c. Charged-Off:  Applicant has not paid the instalments in due time for a long period of time, i.e., he/she has defaulted on the loan.

2. Loan rejected: The company had rejected the loan after evaluating the candidate profile. Since loan is rejected, there is no transactional history of those applicants and hence data is not available with company.

Business Objectives:

Lending Club facilitates low interest rate loan through a fast online interface. Lending loans to 'risky' applicants is the largest source of financial loss. The borrowers who default causes the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. The company wants to understand the driving factors behind loan default, i.e., the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment, and thus minimise the risk of losing money while lending to customers.

## Conclusions

1. People having good grade/credit score have less tendency to default their loans.  Grading system is working as expected.
2. Loans having higher interest rate have more defaulters. Check the background of applicant thoroughly if interest rate is high.
3. Extra scrutiny must be done for the applicants whose annual income is low, as tendency to default is high.
4. When the loan is applied for small business purpose checking of applicant thoroughly as it has high tendency to default.


## Libraries Used
- Numpy – version: 1.20.1
- Pandas - version: 1.2.4
- Matplotlib - version: 3.3.4
- Seaborn - version: 0.11.1

## Contact
Created by @Harshulagarwal and @mikhil-varshney


## License
This project is open source and available under the Apache-2.0 Licence.

