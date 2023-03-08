# Lending-Club_Case-Study
In this case study, we use EDA to understand how consumer attributes and loan attributes influence the tendency of default. 
## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

<br><br> The dataset `loan.csv` contains information about past loan applicants and whether they ‘defaulted’ or not. <br><b><i>The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.</i></b><br>

<br>When a person applies for a loan, there are two types of decisions that could be taken by the company:
> **Loan accepted**: If the company approves the loan, there are 3 possible scenarios described below:<br>
> - Fully paid: Applicant has fully paid the loan (the principal and the interest rate)<br>
> - Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.<br>
> - Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan.<br>

> **Loan rejected**: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

## Conclusions
Key Observations:
 - Borrowers who have request for higher loan amounts have to pay off their debts at a higher interest rate tend to default
 - Generally borrowers who apply for lower grade loans tend to default.
 - Small Businesses tend to get charged off more often these are generally applicants who have taken a loan for small business and the loan amount is greater than 14k
 - When employment length is 10yrs and loan amount is 12k-14k, they tend to default.
 - Borrowers belonging to grade lower than E, are more likely to default.
 - Purposes involving categories other than ‘home’ or ‘renewable energy’, show more signs to default. Hence, extra caution must be taken.
Other Observations:
 - Borrower from CA, FL or NY states have a higher chance to default
 - Borrowers opting for 60 month term are more likely to default than 30 month terms
 - Employees with longer working history got the loan approved for a higher amount.


## Technologies Used
- library - pandas
- library - numpy
- library - matplotlib
- library - seaborn


## Contact
Created by [@howxl] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->