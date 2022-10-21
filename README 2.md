# Prosper Loan Data Exploration

### By Victor Somadina

## An Analysis Focused on the Exploration of the Prosper Loan Dataset 

### Aim

**Supplement statistics with visualizations to build understanding of data.**

**Choose appropriate plots, limits, transformations, and aesthetics to explore a dataset, allowing you to understand distributions of variables and relationships between features.**

**Use design principles to create effective visualizations for communicating findings to an audience.**

**Create Univariate, Bivariate and Multivariate plots to get understanding of data.**

**Generate at least 15 insights in exploration.**

### Libraries Used

#### NumPy
#### Pandas
#### Matplotlib
#### Seaborn

## About Dataset Used


The PropserLoanData dataset have 113,937 rows and 81 columns. The data wrangling stage was a bit hectic as I subsetted the relevant columns which reduced the columns to 28 columns. So many null values were present as well. After dealing with the null values, I finally have 77,557 rows dataset. I looked into the datatypes and ensure I dealt with it appropriately. After which I now saved my new clean dataset as Prosper_Loan_data dataset.

### Summary of Findings

#### Main Findings


Pharmacist, Doctors and judge are the 3 occupations with the highest loan original amount. These are top professionals so its normal that a larger loan amount is allocated to them.

Number of investors and risk score (Prosper score) directly have a positive impact in the amount of loan given to a borrower. 

 As monthly loan payment increases, original loan amount increases. Most recorded loan amount are currently ongoing as of the time of entry. Lenders risk score are moderate as the top risk scores are between 4, 6 and 8. Distribution above shows that most loans are at the range of 4000, 10000, and 1500.

There is no relationship between monthly loan payment and the borrowes stated monthly income.


### key Insights generated

For the presentation, my main focus is on the Loan original amount variable and other variables that affects it. 
First, on visualizing occupation by Loan amount, I found out pharmacist, Doctors and Judge are the 3 profession allocated the highest loan amount.
Also, I was able to find out that some variables like investors and monthly loan payment had a positive impact on the loan amount variable, which means that as this two variables (investors and monthly loan payment) increases, loan amount also increase. Employed followed by self employed borrowers owns a house and are allocated the highest loan amount. The Lenders risk score inversely affects the loan original amount


```python

```
