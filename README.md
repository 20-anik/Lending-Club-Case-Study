# Lending Club Case Study
> The case study is done to give insights to an investor and help the investor determine whether to give the loan applicant the loan or not.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- Provide general information about your project here.

    ```The case study is done to give insights to an investor and help the investor determine whether to give the loan applicant the loan or not.```
- What is the background of your project?

    `EDA`
- What is the business probem that your project is trying to solve?

    ```The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment.```
- What is the dataset that is being used?

    `loan.csv`

## Conclusions
- If the applied loan amount is high there's a slight chance that the person will default.
- Chances of defaulting slightly increases when funded amount is less than applied loan amount.
- A lower rate of interest is likely to be fully paid than charged off.
- Chances of defaulting increases when the loan repayment term is 60 months.
- Chances of deafulting are much higher for grades B and C followed by D compared to other grades. Also, chances of Fully paiying is comparatively higher for grades B and A whose corresponding default percentage is lower. Therefore Grade A followed by B has lower chance of defaulting.
- Ratio of Appllicants fully paying to defaulting is much higher at sub grades A4, A5, A3, B1, A2. Therefore this five sub grades has lower risk of defaulting.
- Chances of defaulting is comparatively the same as chances of paying fully based on employment length, except applicant with 10+ and 7 years of employment length where the risks of defaulting is slightly higher.
- Chances of defaulting is slightly higher for applicants who have home as rented.
- Applicants with anual income of 100000 and higher is likely to pay the loan amount whereas applicants with anual income of 50000 and lesser is likely to default. Applicants with a annual income ranging from 50000 - 75000 has 50-50 chances of paying and defaulting.
- Applicants with verification status as not verified are likely to pay the loan amount, wheareas applicants with a verfication status of verified are likely to default. Applicants with verification status as Source Verified has 50-50 chances to pay or default.

## Technologies Used
- python - version 3.9.12
- pandas - version 1.5.3
- numpy - version 1.21.0
- matplotlib - version 3.6.3
- seaborn - version 0.12.0
- plotly - version 5.13.

## Acknowledgements
Give credit here.
- This project was inspired by upGrad
- This project was based on [this tutorial](https://www.upgrad.com).


## Contact
Created by [@20-anik] - feel free to contact me!