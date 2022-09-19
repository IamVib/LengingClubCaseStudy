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
- Given the dataset from a financial company, I performed several analysis based on various EDA techniques
- This is based on a dataset from a loan providing company with financial information containing lot of consumer and loan attribues
- The goal is detect vital driving factors which increases the frequency of default
- The dataset used here is loan.csv containing around 30k rows and 100+ columns

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Factors like high interest rate, long term loans increases the frequency of default
- Consumers who paid small amount of their loans, or if their last payment towards their loan is small, they tend to default more
- Loans with LC assigned grades as A and B are lot less likely to default
- As the category moves from A to F, the frequency of default increases
- Loans taken for small businesses tend to default more
- Loans taken by consumers from states NV, AK and SD have coparatively higher default ratio

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
