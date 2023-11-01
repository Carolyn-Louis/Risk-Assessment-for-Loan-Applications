# <div align="center"><strong>Risk Assessment for Loan Applications</div></strong>

## Problem Statement

<p style="text-align:justify;">The loan providing companies find it hard to give loans to people due to their insufficient or non-existent credit history. Some consumers take advantage of this situation by becoming defaulters. If you work for a consumer finance company specializing in lending various types of loans to urban customers, your task is to use Exploratory Data Analysis (EDA) to analyze the data's patterns. This analysis will help ensure that applicants capable of repaying the loan are not rejected.

When the company receives a loan application, it must decide on loan approval based on the applicant’s profile. This decision carries two types of risks:

1. If the applicant is likely to repay the loan, not approving it results in a loss of business for the company.
2. If the applicant is not likely to repay the loan (i.e., likely to default), approving the loan may lead to a financial loss for the company.

The data provided contains information about the loan application at the time of applying for the loan. It includes two scenarios:

<strong>1. The client with payment difficulties:</strong> They had late payments of more than X days on at least one of the first Y installments of the loan in the sample.

<strong>2. All other cases:</strong> These are cases when the payments are made on time.

When a client applies for a loan, there are four types of decisions that could be taken by the client/company:

<strong>1. Approved:</strong> The company has approved the loan application.

<strong>2. Cancelled:</strong> The client cancelled the application sometime during the approval process. This can happen if the client changed their mind about the loan or, in some cases, due to a higher risk of the client, they received worse pricing, which they did not want.

<strong>3. Refused:</strong> The company rejected the loan (e.g., because the client did not meet their requirements).

<strong>4. Unused offer:</strong> The loan was cancelled by the client at different stages of the process.

The goal of this case study is to use EDA to understand how consumer attributes and loan attributes influence the tendency to default.</p>

## Business Objectives

<p style="text-align:justify;">This case study aims to identify patterns which indicate if a client has difficulty paying their instalments which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc. This will ensure that the consumers capable of repaying the loan are not rejected. Identification of such applicants using EDA is the aim of this case study.
In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment.
To develop your understanding of the domain, you are advised to independently research a little about risk analytics - understanding the types of variables and their significance should be enough.</p>


This dataset has 3 files as explained below: 

1. 'application_data.csv'  contains all the information of the client at the time of application.
The data is about whether a client has payment difficulties.
2. 'previous_application.csv' contains information about the client’s previous loan data. It contains the data on whether the previous application had been Approved, Cancelled, Refused or Unused offer.
3. 'columns_description.csv' is data dictionary which describes the meaning of the variables.
