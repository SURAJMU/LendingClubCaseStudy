# Lending Club Case Study
> Solving this assignment will give us an idea about how real business problems are solved using EDA. In this case study, apart from applying the EDA techniques, we will also develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* 
<!-- You can include any other section that is pertinent to your problem -->

## General Information
- You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile.
  Two types of risks are associated with the bank’s decision:
    1. If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
    2. If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
- Using the data given which is about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.
- Company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 
- Dataset that is being used here is the loan.csv - It contains the complete loan data for all loans issued through the time period 2007 t0 2011.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Loans with higher amount are less in number and are more prone to be charged off, we should set a threshold
for our loan values and install some more complex processes to approve such huge loans
- Longer termed loans are due to higher loan amount and are more prone to getting defaulted
- Charged off loans on average have higher interest rates compared to paid ones and hence we should continue
to use the algorithm that is rightly assigning a higher interest rate to risky loans
- Also as observed, if the purpose of the loan is to set up small business, the recommendation here is to
investigate into the business plan a bit and estimate profitability of the borrower’s business idea, because we
see them contributing to 8.5% of charged off loans
- Customers with Annual income below $40,000 are more likely to default, the recommendation is to check such
customers even more thoroughly
- Verified customers are more likely to default which is counter intuitive, one reason being their DTI is high
compared to those who don’t default on the loans, also maybe the 3rd party whose verifying these customers
need to reinvestigate their process as to why they are approving such faulty customers
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python 3
