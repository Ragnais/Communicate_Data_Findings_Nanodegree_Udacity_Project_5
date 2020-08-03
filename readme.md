# Udacity Project: Prosper Data Exploration

## by Aisulu Raganina


## Dataset

The dataset contains 113937 entries. The dataset is stored in a csv document 'prosperLoanData.csv'. This [data dictionary](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0) explains the variables in the data set.
The project objective is expected to explore variables which effect the Loan Status as Completed or Defaulted.

## Summary of Findings

1. After excluding the Status 'Current', the percentage of the Completed Loans is at  69.7% while Defaulted at 3.6%.
2. The distribution of Employment Status shows that a high percentage of the loan takers are Employed, full-time and Self-Employed.
3. The Employed and Full-time statuses cover most of the Completed loans. On the other hand, the PostDue loan status only includes the Employed group. Also, from the top 3 Employed Statuses, there are more Defaulted loans for the Self-employed.
4. The variable Stated Monthly Income showed the very right skewed distribution because of the outliers. The most of the salaries are in the range between 0 and 10000 which have a normal distribution.
5. The distribution of Loan Original Amount is a right skewed distribution with the peak at around 4800.   The Loan original amount also has a positive correlation of 0.28 with Stated Monthly Income.
6. The mean of Completed loans for Stated Monthly Income is slightly higher than for the Defaulted, while the mean of Completed and Defaulted for the Loan Original Amount is the same.

7. The shape of the Borrower APR and Borrower Rate distributions shares some similarities and, as it was expected, there is a positive correllation between two variables.
8. There is a negative correlation of -0.25 between the "BorrowerAPR" and "Loan original amount" and -0.18 between "BorrowerAPR" and "StatedMonthlyIncome".

9. Prosper Rating shows an effect on the Loan Status: the highest Prosper Rating AA shows a few defaulted cases than the lower Prosper rating groups. The most of the Completed loans have the rating D. There also are less Defaulted cases for the Prosper Rating AA with the Borrower APR around 0.1. 


## Key Insights for Presentation

For this presentation, I focus on the features using univariate, bivariate, and then multivariate plots to show what effects the Loan Status.

1. The Loan Status in percentage
2. The Employment Status
3. The Stated Monthly Income
4. The Loan Original Amount
5. The Borrower APR
6. The Loan Status vs Employment Status 
7. The Loan Status vs Stated Monthly Income and Loan status vs Loan Original Amount
8. The Stated Monthly Income vs Loan Original Amount
9. The Loan Status vs Prosper Rating
10. The Loan Status vs Borrower APR
11. The Loan Status vs LoanOriginalAmount vs EmploymentStatus  
12. The Loan Status vs LoanOriginalAmount vs StatedMonthlyIncome 
13. The Loan Status vs ProsperRating vs Borrower APR
14. The Borrower APR vs Loan Original Amount vs Stated Monthly Income 

## References

1. https://towardsdatascience.com/introduction-to-data-visualization-in-python-89a54c97fbed  
2. https://towardsdatascience.com/formatting-tips-for-correlation-heatmaps-in-seaborn-4478ef15d87f 
3. https://www.lendacademy.com/prosper-review/
4. https://towardsdatascience.com/ways-to-detect-and-remove-the-outliers-404d16608dba
5. https://seaborn.pydata.org/generated/seaborn.heatmap.html
6. https://towardsdatascience.coxm/data-visualization-using-seaborn-fc24db95a850
7. https://seaborn.pydata.org/generated/seaborn.FacetGrid.html
8. https://www.kaggle.com/residentmario/multivariate-plotting
9. https://seaborn.pydata.org/generated/seaborn.lmplot.html