# Lending Club Case Study
> To develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimize the risk of losing money while lending money to customers.



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

- This analysis is for a consumer finance company which specializes in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. <br>
Two types of risks are associated with the bank’s decision:
  - If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
  - If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.

Risks:
- Business Risk: Losing business from rejected repayers.<br>
- Financial Risk: Incurring losses from approved defaulters

AIM:
-   To identify these risky loan applicants using EDA.
-   Understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.

DATASET USED : loan.csv 


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- From the loan amount distribution it is observed that there are spikes near multiples of 5000s. This is because of rounding off from borrowers where if there is a necessity of loan amounts of for example 4676, they take a round amount of 5000.

- There is a good correlation between total interest received and total payment received. It is observed that the charged off loans lie in the lower total payment range.

- The chances of customers not paying off the loan is higher for those customers who have atleast 7 times 30+ days past-due incidences of delinquency in the borrower's credit file for the past 2 years.

- The most number of defaulters had done their last payment in the month of October 2012. Most defaults have happened in 2012. Some event has occurred in 2012 which might have lead to many people not being able to continue their due installments.
- On an average higher amount of loans get charged off. The spread of charged off loans goes towards the higher loan amounts. The 75th percentile is above 15000 for charged off loans whereas it is lesser than 15000 for fully paid loans. 
The average loan amount which gets charged off is 12277.23.
- The total % of borrowers who default is higher for borrowers who have homeownership type is 'OTHER'. But following that the next highest % of defaulters are from borrowers who take house on 'Rent'. Thus these 2 categories are hot spots to look at when giving a loan.
- The only person who has 70 credit lines has defaulted. But we cannot take that as a definitive fact due to lesser number of data. But overall people who have either 60 credit lines or 3 credit lines seem to have defaulted with a good percentage. So these are few indicators to check whether loan should be given.
- There seems to be higher percentage of defaulters in employees who have worked for more than 10 years. It is quickly followed by an employment length of 7 years. It maybe the case that after 7 years of working people tend to apply loans for various categories like house loan, car loan or even loan for their businesses but after that are unable to pay back the same. Overall there is no stark difference for any category
- It is observed that there is a difference in the higher grades F and G. When the amount of interest received is high (6000 and above) those loans tend to get fully paid. If the interest received is around 4000 or lesser, those loans tend to get defaulted. Hence this is an indicator on when the loan might get defaulted.



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas
- numpy
- matplotlib
- seaborn
- datetime

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements


## Contact
Created by @maalolankannan1 - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
