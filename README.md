# Lending Club Case Study
> Lending Club is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface.
> Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.

> So, the objective of this project is  to identify these risky loan applicants using Exploratory Data Analysis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
  The objective is identify the factors leading to loan default using EDA. The company can utilise this knowledge for its portfolio and risk assessment. 
  
- What is the background of your project?
  This is a case study taken as a part of AI&ML Jan 2024

- What is the business probem that your project is trying to solve?
  Identifying the driving factors behing loan default.

- What is the dataset that is being used?
  loan.csv - This file contains complete loan data for all loans issued through the time period 2007 t0 2011.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Loans for Debt consolidation, Small Business, credit card and home improvement applicants should be checked properly or Loans can be provided with lower rate of interest to these applicants as there are more no of defaulters in these categories.
- Loans also taken for purpose as “other” need to be verified properly.
- Default rate was high for verified loan applicants. So, Verification process strictly needs to be amended else there could be higher loss to LC/investors.
- Lower annual income applicants should be avoided for big loan amounts with higher interest rates.
- Loan approvals must be utmost taken care in the months of November and December as there are higher no of defaulters in these months.
- Loans approval for applicants from states located along the border of the USA exhibit a higher default rate and hence applicants from these areas should be properly verified.
- Applicants of work experience >=10 years and have applied loan for debt consolidation and lived in rented or mortgage houses are more prone to defaulters. Hence, these type of applicants should be properly handled.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas library - version 2.0.3
- numpy library - version 1.24.3
- seaborn library - version 0.12.2
- matplotlib library - version 3.7.2
- plotly library - version 5.9.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was taken as a part of AIML - Jan2024 EDA case study
- References: 
- Plotly template refered from https://levelup.gitconnected.com/using-python-for-geographical-plotting-d9328fb8cfab
  



## Contact
Created by [@smarunkumar]/[@mansisharmapb] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
