# Prosper-Loan-Analysis
The primary objective of this investigation is to conduct a comprehensive exploratory data analysis (EDA) on a loan dataset to uncover key trends, patterns, and relationships among various loan attributes. By visualizing and analyzing the data, we aim to gain insights into loan performance, borrower characteristics, and market dynamics. These findings will inform strategic decision-making, risk assessment, and the development of targeted loan products.

## About the dataset
On November 24, 2008, the SEC found Prosper to be in violation of the Securities Act of 1933. As a result of these findings, the SEC imposed a cease and desist order on Prosper ... In July 2009, Prosper reopened their website for lending ("investing") and borrowing after having obtained SEC registration for its loans ("notes"). After the relaunch, bidding on loans was restricted to residents of 28 U.S. states and the District of Columbia. Borrowers may reside in any of 47 states, with residents of three states (Iowa, Maine, and North Dakota) not permitted to borrow through Prosper.

## Example of question-visualization-observations
### 1. Does Loan status have unusual loan original amount?
![Untitled](https://github.com/user-attachments/assets/6637c930-73d4-4f77-ad28-051a8afcaa82)

> All loan statuses have outliers, indicating some loans are significantly larger than most others in their respective categories.

> Completed loans exhibit the most outliers, suggesting a wide variation in loan amounts within this category.

> Charged-off loans also show a considerable number of outliers.

> Current Loans, The highest upper outliers are observed in the current loan status, indicating some very large loans are currently active.



### 2. How does the Original Amount of Loan change over time?
![Untitled](https://github.com/user-attachments/assets/14b7d466-57c8-4fc0-bbb8-f965dc122a32)

> There is a noticeable increase in loan amounts over the years, suggesting that borrowers have been taking out larger loans as time progresses.

> Interestingly, the year 2009 stands out with some of the highest loan amounts, indicating that during this period, there were notably larger loans compared to other years.

### 2. How do different terms group with the selected variables?
![Untitled](https://github.com/user-attachments/assets/bd5265d8-4a3b-49df-93d3-5e3de39c1ed5)

> Longer terms (36 and 60 months) tend to be associated with higher loan original amounts.

> There doesn't seem to be a strong relationship between term and borrower APR or debt-to-income ratio.

> Loan Original Amount vs. Borrower APR have a weak positive correlation, suggesting that larger loans might have slightly higher APRs.
