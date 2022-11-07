# Prosper Loan Data Exploration

## Ahmed Unshur


The following project is a data visualization project that was completed as part of [Udacity’s Data Analyst Nanodegree](https://www.udacity.com/course/data-analyst-nanodegree--nd002) program.

The project explores and visualizes loan data from [Prosper](https://www.prosper.com/) which is a peer-to-peer lending company based in San Francisco, CA, USA. The dataset contains 113,937 loans with 81 variables on each loan, including loan amount, borrower's Annual Percentage Rate (APR), borrower's income range, loan term, and many others. The dataset can be downloaded from this [link](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv). Also, see this [dictionary](https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&ust=1554486256024000) to understand its variables.

We conducted a preliminary wrangling, and the cleaned dataset consists of 84853 rows and 8 columns. Then, we performed performed exploratory analysis producing univariate, bivariate, and multivariate visualizations. Finaly, we generated explanatory data visualizations.

Visualizations revealed the following findings:
1.  Majority of borrower's Annual Percentage Rates (APR) for the loan fall between 0.15 (15%) and 0.25 (%25)
2.  Majority of borrowers take loans with a length of 36 months (3 years).
3.  Most of borrowers get Prosper score of between 4 and 8.
4.  Number of borrowers that own a home is slightly higher than that of those who don't.
5.  Individuals with an income range of `$50,000-74,999` are the ones who take loans the most.
6.  There is a negative relationship between borrower APR and loan amount.
7.  There is a negative relationship between borrower APR and Prosper score.
8.  Borrowers that own a home tend to take large loan amounts compared to those who don't own a home.
9.  Borrowers with higher income ranges tend to take larger loans.
10.  Lenght of the loan doesn't affect borrower APR and Prosper score.
11.  Borrowers that take loans of 60 months tend to have higher income ranges and take large loans.
12.  Borrowers that take loans of 60 months tend to own a home and take large loans.

To complete this project, we have used Anaconda, Python and some of its packages and libraries (NumPy, Pandas, Matplotlib, Seaborn) and Jupyter Notebook.

