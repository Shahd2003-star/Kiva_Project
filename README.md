# Kiva Project

Data Science for Good: Kiva Crowdfunding

Final Project in Introduction to Data Science and Data Analysis in R


Team Members - Shahd Khalil, Walaa Abu Shiban, Shaden Zoabi and Mariam Zedan
===================================

This markdown file describes the project structure and organization.

To reproduce the analysis, download the Kiva dataset and place the file kiva_loans.csv in the project directory. Then run the R scripts included in this repository.

The Kiva platform is a global crowdfunding system that connects lenders with borrowers from different countries around the world. Borrowers request loans for various purposes such as agriculture, retail, education, food businesses, housing, and other economic activities.

Different loan sectors may attract different levels of interest from lenders. Understanding these differences can provide insights into funding behavior and help identify factors associated with successful fundraising.

The purpose of this project is to investigate whether the sector of a loan influences its funding success on the Kiva platform.

Research Question
===================================================================

Does the loan sector affect funding success on Kiva?
Kiva is a global crowdfunding platform that connects lenders with borrowers from different countries around the world. Borrowers request loans for a variety of purposes, including agriculture, retail, education, food businesses, housing, and other economic activities.

Different loan sectors may attract different levels of interest from lenders. Understanding these differences can provide insights into funding behavior and help identify factors associated with successful fundraising.

The purpose of this project is to investigate whether the sector of a loan influences its funding success on the Kiva platform.

Data Description
=================================================================

The analysis is based on the Kiva Loans dataset obtained from Kaggle.

Each row in the dataset represents a single loan request published on the Kiva platform.

The dataset contains information regarding loan characteristics, borrower information, funding outcomes, and lender participation.


Data Feature List (Relevant Features)
==========================================================
sector:the general category of the loan,this is the primary variable used in the analysis.


funded_amount:the amount of money successfully raised for the loan.

loan_amount:the total amount requested by the borrower.

activity:the specific business activity associated with the loan.

country:the country in which the borrower is located.


region:the local region or city of the borrower.


lender_count:the number of lenders who contributed to the loan.


borrower_genders:the gender of the borrower or borrowers.

term_in_months:the repayment period of the loan in months.

repayment_interval:the repayment schedule of the loan.


Project Goal
===============================================================
The goal of this project is to examine whether different loan sectors are associated with different levels of funding success.

The analysis includes:

Data cleaning and preprocessing
Exploratory Data Analysis (EDA)
Data visualization
Statistical analysis of funding outcomes across loan sectors

The findings may help better understand how loan characteristics influence fundraising performance on the Kiva platform and which loan sectors tend to achieve greater funding success.
