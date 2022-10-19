# Exploration of Prosper Loan Data set¶

## Data Set

The 113,937 loans in this data collection have an average of 81 variables, such as loan amount, borrower rate (or interest rate), current loan status, borrower income, and many more.

## Summary of Findings

I used the employment status of borrowers, stated monthly income, and the prosper risk score associated with each loan to explore this data set with a focus on loan status and borrowers' rates, and I found some interesting relationships. First, I noticed that there was a strong negative relationship between the prosper risk score and borrowers' rate. Additionally, I found that there was a relationship between the prosper risk score and stated monthly income. In addition, after creating some multivariate graphs, I found some intriguing trends.

I found that for defaulted, completed, and charged-off loans, the risk score for unemployed borrowers always trails that of all employed borrowers. This indicates that the riskiest defaulted, completed, and charged-off loans are collected by unemployed borrowers, whereas the riskiest past-due loans were collected by employed borrowers because the risk score for employed borrowers is the smallest. Finally, I saw that we have relatively low prosper scores within a specified monthly income at high borrowers rates, which is a sign of dangerous loans for nearly all income levels.

## Key Insights for Presentation

I concentrated on the Prosper risk score and the impact of work status on borrower rates and loan status for the presentation. I began by outlining the distribution of the borrower rate, loan status, employment status, and prosper risk score. Next, I used a boxplot and bar chart to demonstrate the relationship between the aforementioned variables. Finally, I used a grouped bar plot to demonstrate the multivariate relationship between the employment status effect on the prosper risk score and the loan status above, respectively.

```python

```
