# (Prosper Loan Data Exploration)
## by (MATHIAS ETIM)


## Dataset

The dataset can be found in this online storage service where it has been uploaded by udacity [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1581581520570000),
with feature documentation available [here](https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&ust=1554486256024000).

## Summary of Findings


At the end of this exploration, i was able to deduce that those who satisfy the following conditions are more likely to complete their loans.

1. Employed: whether full time, part time, employed
2. Loan taken for personal reasons.
3. Average credit score between 650 and 750
4. Recommedations >=10

Apart from the main variable of interest, i also observed some relation between some of the numeric variables such as the recommendation count and the count of investment from friends in which i noticed that the more recommendations there are, the more friends invested in the loan.
Also, the `average credit score range` (which was obtained from taking the average of the upper credit score range and the lower credit score range) and the `amount of principal payments made before charged off` also have slight correlation.


## Key Insights for Presentation

For the presentation, i focused on the `employment status`, `Average credit score` and `Recomendations count`.
I started by looking at the distribution of the variable of interest `LoanStatus` followed by the `employment` status distribution.

I also investigated the other variables one by one plotting their distribution with histograms.
Finally, i investigated the effect of these variables on the interaction between loan status and emploment status using both boxplot and point plot.

