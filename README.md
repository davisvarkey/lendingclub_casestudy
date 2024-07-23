# Project Name
### Lending Club Case Study


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile.

Two types of risks are associated with the bank’s decision:

    If the applicant is likely to repay the loan, then not approving the loan results in
    a loss of business to the company

    If the applicant is not likely to repay the loan, i.e. he/she is likely to default,
    then approving the loan may lead to a financial loss for the company

 

The data given below contains the information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

In this case study, you will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.

https://cdn.upgrad.com/UpGrad/temp/7afbce98-8ecc-41c6-96d8-981cba7d343f/Loan_image.png

Figure 1. Loan Data Set

## Business Objectives

This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

 

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 

 

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

 

In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 


To develop your understanding of the domain, you are advised to independently research a little about risk analytics (understanding the types of variables and their significance should be enough).

## Data Understanding
 

Download the dataset from below. It contains the complete loan data for all loans issued through the time period 2007 t0 2011.

https://cdn.upgrad.com/UpGrad/temp/3ba74fb7-bd88-4854-8597-1c225a5aed99/loan.zip

You can access the data dictionary which describes the meaning of these variables from the provided link below:

https://cdn.upgrad.com/UpGrad/temp/af860da6-f838-47d6-ad97-551022550ee4/Data_Dictionary.xlsx

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- numpy version	: 1.23.5
- pandas version	: 2.1.4
- seaborn version	: 0.13.2
- Python version	: 3.10.13

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Conclusions

Driving features to be considered before approving loan :

1. Purpose of Loan – loan purpose has to be carefully considered, for e.g; going loan to “small_business” very risky, has the highest % of default  rate.
2. Annual Income - Lower the borrower’s annual income, Higher are the chances of  default.
3. Grade&Interest Rate – both of them are  positively correlated and as grade/int rate increases,  the loan default rate also increases. For e.g default rate is highest for grade “G” which also has the highest interest rate.
4. Loan Amount – Higher the loan amount , more is the loan default rate.
5. Term – Loans granted for 60-month term have higher default rate when compared  to loans with 36-month term.
6. Loan Issue Year - There could be some unpredictable factors which leads to default. For e.g higher percentage of defaulters are those who took loan on 2007. Because the year after that had faced the worst recession.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Acknowledgements


## Contact
Created by @davisvarkey - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->