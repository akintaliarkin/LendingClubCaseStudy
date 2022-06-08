# Project Name
> Underwriting risk analysis for a diversified consumer finance company catering to urban customers.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
This project deals with the underwriting risk analysis for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

* If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

* If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

The objective here is to find the driving factors (or driver variables) behind loan default. These factors will be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

This analysis uses the complete loan data for all loans issued through the time period 2007 t0 2011 by the company.


## Conclusions
- Customers who are revolving their credit more are more likely to default.
- The shorter the tenure of the loan, more is the likelihood of default.
- Number of customers defaulting loan is almost increasing by double every year, which states the need to bring in better loan approval mechanism.
- Maximum numbers of loans are approved towards the end of year
- Customers with previous bankruptcy records are more likely to default
- The defaulters are more for interest rate of around 15%

## Technologies Used
- Pandas - Version 1.3.4
- matplotlib - Version 3.4.3
- Seaborn - Version 0.11.2

## Acknowledgements
- This project mainly applies the concepts of EDA (Exploratory Data Analysis) in Data Science.
- The data dictionary provided by the client was used for understanding the data.
- Resources on the web were consumed to understand various terminologies associated with consumer lending.

## Contact
Created by [@akintaliarkin] and [@nikhilanilbansal] - feel free to contact us!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
