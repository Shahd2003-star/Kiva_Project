# Kiva Project

Data Science for Good: Kiva Crowdfunding

Final Project in Introduction to Data Science and Data Analysis in R


Team Members - Shahd Khalil, Walaa Abu Shiban, Shaden Zoabi and Mariam Zedan
===================================

This markdown file describes the project structure and organization.

To reproduce the analysis, download the Kiva dataset and place the file kiva_loans.csv in the project directory. Then run the R scripts included in this repository.

The Kiva platform is a global crowdfunding platform that connects lenders with borrowers from different countries around the world. Borrowers request loans for different purposes such as agriculture, retail, education, food businesses, housing, clothing, manufacturing, and other economic activities.

Since there are many loan requests on the platform, lenders may not read every loan in detail. Instead, they may use simple and visible information, such as the loan sector, loan amount, repayment interval, and loan term, to decide whether to fund a loan.

Different loan sectors may attract different levels of interest from lenders. However, funding success may also depend on other loan characteristics, not only on the sector itself.

The purpose of this project is to investigate how the economic sector of a loan is associated with fundraising success on the Kiva platform, after considering loan amount, repayment interval, and loan term.

Research Question
===================================================================


How is the loan's economic sector associated with fundraising success on Kiva, after considering loan amount, repayment interval, and loan term?

Kiva is a global crowdfunding platform that connects lenders with borrowers from different countries around the world. Borrowers request loans for a variety of purposes, including agriculture, retail, education, food businesses, housing, clothing, manufacturing, and other economic activities.

Different sectors may have different chances of being fully funded. For example, some sectors may look more attractive or safer to lenders, while other sectors may require larger loan amounts, longer loan terms, or different repayment schedules.

For this reason, this project does not only compare the raw success rates between sectors. It also checks whether the sector is still related to funding success after including other loan characteristics in the analysis.

Data Description
=================================================================

The analysis is based on the Kiva Loans dataset obtained from Kaggle.

Each row in the dataset represents one loan request published on the Kiva platform.

The dataset contains information about loan characteristics, borrower information, repayment structure, funding outcomes, and the economic sector of each loan.

After cleaning and preprocessing the data, the final dataset used in the analysis contains 671,205 unique loans across 15 different economic sectors.


Data Feature List (Relevant Features)
==========================================================
sector: the general economic category of the loan. This is the main variable used in the analysis.

funded_amount: the amount of money successfully raised for the loan.

loan_amount: the total amount requested by the borrower.

FundingSuccess: a binary variable created for this project. It equals 1 if the funded amount is greater than or equal to the loan amount, and 0 otherwise.

activity: the specific business activity associated with the loan.

country: the country in which the borrower is located.

region: the local region or city of the borrower.

borrower_genders: the gender of the borrower or borrowers.

term_in_months: the repayment period of the loan in months.

repayment_interval: the repayment schedule of the loan, such as monthly, weekly, irregular, or bullet repayment.

Project Goal
===============================================================
The goal of this project is to examine whether different loan sectors are associated with different levels of fundraising success.



The analysis includes:

Data cleaning and preprocessing  
Exploratory Data Analysis (EDA)  
Data visualization  
Logistic regression analysis  
Model evaluation  
Analysis of funding success across loan sectors  
Analysis of loan amount, repayment interval, loan term, and borrower gender as control variables  

The project first looks at the general funding success rate in the data. Then it compares funding success across different sectors and other loan characteristics.

After that, a logistic regression model is used because the target variable, FundingSuccess, has only two possible values: funded or not fully funded.

The model helps us understand whether the loan sector still plays a role in funding success after considering other factors such as loan amount, repayment interval, loan term, and borrower gender.

Main Findings

The descriptive analysis shows that most loans on Kiva are fully funded, but there are still some loans that are not fully funded.

The results also show that funding success is not the same across all sectors. Some sectors have higher average success rates, while other sectors have lower success rates.

However, these simple differences between sectors are not enough to explain the full picture, because sectors may also differ in loan amount, repayment interval, and loan term.

For this reason, the project uses logistic regression to check the relationship between sector and funding success while controlling for other loan features.

The model results show that some sectors have higher odds of full funding compared to Agriculture, while other sectors have lower odds.

This means that the loan sector may still be connected to funding success, even after adding other loan characteristics to the model.

Conclusion

This project shows that the economic sector of a loan is associated with fundraising success on Kiva.

The results suggest that lenders may use the loan sector as a simple signal when deciding whether to fund a loan.

At the same time, the analysis shows that funding success is also related to other loan features, such as the loan amount, repayment interval, and loan term.

Overall, this project helps explain how loan sector and loan structure are related to crowdfunding success on the Kiva platform.

Future Work

Future work can use the results of this project to help improve the loan posting process on Kiva.

For example, a simple decision support system could be developed to identify loans that may have a higher risk of not being fully funded before they are published.

Such a system could suggest possible improvements, such as reducing the loan amount, changing the repayment interval, or adjusting the loan term.

This could help borrowers improve their chances of successful fundraising.

Dataset Source

The dataset used in this project is available on Kaggle:

Data Science for Good: Kiva Crowdfunding

https://www.kaggle.com/datasets/kiva/data-science-for-good-kiva-crowdfunding

