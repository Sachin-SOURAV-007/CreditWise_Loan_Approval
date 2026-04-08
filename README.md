In this repository, I have used Machine Learning to automatically determine wheter a person gets loan or not based on historical data.

                                                               CreditWise Loan System – (Problem Statement)

A mid-sized financial company, SecureTrust Bank, offers personal and home loans to customers across both urban and rural regions of India. Every day, hundreds of customers apply for loans through online platforms as well as branch applications.

Until now, SecureTrust Bank has relied on a manual verification process, where loan officers evaluate applications by checking income proofs, employment details, credit history, and other supporting documents. This process is:

Time-consuming
Prone to human bias
Inconsistent in decision-making

As a result, the bank faces two major challenges:

Good customers sometimes get rejected, leading to loss of potential business.
High-risk customers sometimes get approved, resulting in financial losses.
Proposed Solution

To address these issues, the bank aims to introduce an intelligent loan approval system powered by Machine Learning. This system will:

Automatically analyze applicant details
Predict whether a loan should be Approved or Rejected
Assist in decision-making before final human verification
Your Role

You are hired as a Machine Learning Engineer to design and develop this intelligent system using historical loan application data.

The system must:

Learn hidden patterns from past customer records
Provide accurate and fast predictions
Ensure unbiased and consistent loan approval decisions

DATASET DESCRIPTION

Column Name	Description

Applicant_ID  -	Unique applicant ID

Applicant_Income	- Monthly income of the applicant

Coapplicant_Income -	Monthly income of the co-applicant

Employment_Status	- Employment type (Salaried / Self-Employed / Business)

Age	Applicant's - age

Marital_Status -	Marital status (Married / Single)

Dependents -	Number of dependents

Credit_Score -	Credit bureau score

Existing_Loans -	Number of currently active loans

DTI_Ratio	- Debt-to-Income ratio

Savings	- Savings balance of the applicant

Collateral_Value -	Value of collateral provided
Loan_Amount	- Loan amount requested
Loan_Term	- Loan duration (in months)
Loan_Purpose -	Purpose of loan (Home / Education / Personal / Business)
Property_Area -	Location type (Urban / Semi-Urban / Rural)
Education_Level -	Education level (Graduate / Postgraduate / Undergraduate)
Gender -	Gender of the applicant (Male / Female)
Employer_Category	- Employer type (Govt / Private / Self)
Loan_Approved (Target) -	Loan approval status (1 = Approved, 0 = Rejected)
