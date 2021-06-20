# Introduction

From the practice challenge hosted at: *https://datahack.analyticsvidhya.com/contest/practice-problem-loan-prediction-iii/*


## Problem Statement

Dream Housing Finance company deals in all types of home loans. They have presence across all urban, semi urban and rural areas. Customers first apply for home loan after which the company validates the customers' eligibility for loan.

The company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have given a problem to identify the customers segments, those are eligible for loan amount so that they can specifically target these customers.

## The Data and Datasets

The datasets (*train.csv* and *test.csv*), can be obtained from the above provided link. there is similarity between the datasets except the Loan_Status which is missing in the test dataset. The model to be built will predict the Loan_Status using the train data.

| Variable         | Description   |
| -------------    | ------------- |
| Loan_ID          | Unique Loan ID  |
| Gender           | Male/Female  |
| Married          | Applicant Married (Y/N)  |
| Dependents       | Number of Dependents |
| Education        | Applicant education (Graduate/Undergraduate) |
| Self_Employed    | Self employed(Y/N)  |
| ApplicantIncome  | Applicant income  |
| CoApplicantIncome| Coapplicant income  |
| LoanAmount       | Loan amount in thousands |
| Loan_Amount_Term | Term of loan in months  |
| Credit_History   | Credit history meets guidelines  |
| Property_Area    | Urban/SemiUrban/Rural  |
| Loan_Status      | Loan approved (Y/N)  |

Various techniques, using Python various libraries, have been applied to come up with the best modelling algorithm:
1. Logistic Regression
2. Decision Tree
3. Random Forest
4. XGBoost
