Lending Club Case Study

A short case study of a loan lending company to identify driving factors (or driver variables) behind loan default.


## Table of Contents
* [Problem Statement](#problem-statement)
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)



## General Information
- Lending Club is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 
- Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters
- Our Objective is to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilize this knowledge for its portfolio and risk assessment. 
- Datasets used - Lending Club loan data. It contains the complete loan data for all loans issued through the time period 2007 t0 2011.

 
## Conclusions
- From our analysis so far we can consider the below mentioned variables to be indicators of loan-default.
- Strong Indicators
- Loan Grade: Lower grades(G means lowest A means highest grade of loan) with higher loan amount are very risky and have been  shown to become defaulted.
Home Ownership :  Higher Loan amounts  given to people who have mortgage on their homes are more likely to get charged off.
Purpose of the Loan: Loans taken for purposes like small business, renewable energy, debt consolidation, home improvement, credit card and education have higher chances of getting default.
Interest Rate : Loans with high interest rates are prone to default as primary purposes are debt consolidation and higher interest rates adds to the problem due to which applicants default on the loan amount.
Revolving Utilization: Loans given to applicants with High revolving utilization(>15%) have higher likelihood of default.
Derogatory Public records: Loans given to applicants who have 1-2 number of derogatory records have higher likelihood of default.
Public Bankruptcy records: Loans given to applicants who have 1-2 number of bankruptcy records have higher likelihood of default.
- Mild Indicators
- Loan Term: Loan amounts ith 60 months term are somewhat likely to get defaulted.
Lower Annual Income : Loans given to applicants with lower annual income are somewhat likely to get defaulted.
DTI : Loans given to applicants with higher dti are somewhat likely to get defaulted.
Address State  : Loans given to applicants who are from NV, SD, AK, FL, TN, WY are somewhat likely to get defaulted.
Number of Delinquency  in last 2 years: Loans given to applicants with higher incidences of delinquency  have some likelihood of default.
Issue Month : Loans given to applicants on the months of December , September and May have some likelihood of default.




## Technologies Used
- [Python - Version 3.11.5]
- [numpy - Version 1.26.0]
- [pandas - Version 2.1.1]
- [matplotlib - Version 3.7.2]
- [seaborn - Version 0.12.2]
- [Jupyter Notebook - Version 6.5.4]


## Acknowledgements

- References Used
- Upgrad study materials 
- https://stackoverflow.com/questions/23377108/pandas-percentage-of-total-with-groupby



## Contact
Created by [] - feel free to contact me!

