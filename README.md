
# Prosper Loan Data Analysis

## by Success Osakioduwamen Obazee


## Dataset

 This dataset contains information on peer to peer loans facilitated by a credit or a loan company called Prosper in the United States. Prosper makes personal loans easy. The dataset can be downloaded here:  https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv
This project is divided into two major parts:
* In the first part, we will conduct an exploratory data analysis on some main feature of the dataset.
* In the second part, we will make use of some findings from the exploration and convey them through an explanatory analysis.
Since our main aim here is Exploratory Data Analysis, so we will merge assessing and cleaning steps into one to make it concise and simple.

### Data Assessing and Cleaning

*  Choose Subset of Features of Interest
*  Drop Duplicated Rows Based on Listing Number
*  Convert LoanOriginationDate to datetime datatype and separate date and time
*  Convert ListingCategory (numeric) into their names and Rename to ListingCategory



## Summary of Findings

 The EmploymentStatus was analysed with some factors such as the loan status and term to find out the Employment Status of the borrowers. The Listing Category, borrower's rate and Loan original amount  were the most important features in predicting some various features.
 
*  The majority of borrowers are currently employed and work full-time.

*  Most of the loans in the Loan Status are actually current loans while Past due loans are split in several groups based on the length of payment delay and Other big part is completed loans, defaulted loans compromise a minority, however chargedoff loans also comporomise a substanial amount

*  There are only 3 loan terms, and the majority of loan term is for the 36 months

*  The defaulted and chargedoff credits tend to be smaller than completed credits ones in the Loan Status Vs Loan Amount.

*  The full time employed borrowers have almost completed their loans

*  The Full time employed borrowers have a longer term loan of 36 months.

*  Majority of the employed borrowers used their loan for debt consolidation reasons.

*  More employed borrowers in California

*  The full time employed borrowers have a higher amount of loan than the others

*  Employed workers has the highest Completed Loan in the loan amount

*  There is a strong positive correlation between the Stated Monthly Income and Loan Original Amount in the employment status category

NOTE: The majority of loans are actually current loans. Since our main goal is to define driving factors of outcome of loan we are not interested in any current loans, so we adjusted it


## Key Insights for Presentation

*   Defaulted and chargedoff credits tend to be larger than completed and most of the defaulted credits comes from individuals with low Prosper rating.

*  The highest borrower rate is Other and Not-employed borrowers

*  LoanOriginalAmount and MonthlyLoanPayment is having a strong positive relationship which states that the increase in the loan amount leads to the increase in monthly payment

*  The highest borrower APR is Other, Not Employed and self-employed borrowers

*  The Self-Employed borrowers have the highest monthly income

*  Retired employees has the lowest borrower APR on a 12 month loan term
