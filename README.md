# Lending Club Default Loan Drivers Detection
>  Given a dataset from a large online loan marketplace 
where people can avail loans easily. The data is about 
customers who are either currently paying their loan, or 
already paid their loans or the ones who defaulted on 
their loans.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Given the dataset from a large online loan company from where people can take loans easily
- The dataset has financial information containing lot of consumer and loan attribues
- It contains data about above active, fully paid and defaulted loans
- The goal is detect vital driving factors which increases the frequency of default
- The dataset used here is loan.csv containing around 30k rows and 100+ columns

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Loans with high interest rate tend to get defaulted more. Since interest rate compounds and overall repayment amount gets big exponentially over time, loans given at lower interest rate could be safer.
- Long term loan(60 months) tends to get default. Applications for long term loan should be more scrutinized.
- Lending club assigned loan grades based on consumers' attributes is very useful. The default frequency increases from grade A towards G, thus loan applications going - from A towards G should be approved very carefully.
- In a particular grade, the default frequency increases from 1 to 5 subgrades with exceptions. But as a general thumb of rule, the higher subgrade increases the chances of default.
- Loans titled 'Small business loan' are risky and should be approved carefully understanding that the chances of default could be high.
- Loans taken for the purpose of small businesses are risky as we know from the title of the loans as well. Loan with this purpose should be approved understanding the amount of risk involved.
- Consumers belonging to Missouri(MO) and Florida(FL) have defaulted more on their loans. Loan applications with consumers from these states should be more scrutinized
- As late as the month is issued in a US fiscal year, the chances of default increases. Loan applications coming late in the fiscal year cycle should be approved carefully. Specially May and December

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.9.12
- numpy - version 1.21.5
- pandas - version 1.4.2
- matplotlib - version 3.5.1
- seaborn - version 0.11.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was done for a case study


## Contact
Created by @IamVib - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
