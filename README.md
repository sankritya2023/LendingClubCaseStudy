# Project Name
> Outline a brief description of your project.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
The data given below contains information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

In this case study, we have used EDA to understand how consumer attributes and loan attributes influence the tendency of default.

When a person applies for a loan, there are two types of decisions that could be taken by the company:
Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:
Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 
Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)


Objective : To understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
1. Charged off loans have slightly higher loan amounts than fully paid ones
2. Charged-off loans contribute a higher proportion of overall loans in 60 months term compared to 36 months term
3. Charged off loans is associated with significantly higher interest rate than fully paid ones
4. Lower grade loans have a higher chance of default
5. Members who defaulted on loans have on an average slightly lower annual incomes than full ypaid loans
6. Members who have taken loans for small_business have slightly higher chance of default, though not significant enough
7. Loans given to NE (Nevada?) state residents have a significantly higher chance of default
8. Members having higher debt-to income ratio have higher chance of defaulting as observed from the box plots mean and 75th percentiles
9. Higher revolving utilization correlates with a higher charged off loans
10. lower the total number of credit lines currently in the borrower's credit file,  more chances of charged off loans. This is counter-intuitive
11. the more a member has a public record of bankrupcies, more probability of the loan default

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- libraries - pandas, numpy, matplotlib.pyplot, seaborn, warnings, plotly.express

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by UPGRAD


## Contact
Created by @sankritya2023


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
