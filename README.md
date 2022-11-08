# Prosper Loan Data Exploration
## by Chizaram Emenyonu


## Dataset

> The Prosper loan dataset comprises of 113937 loan entries with 81 attributes on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others, from the year 2009-2014. There are two main categories:<br/>
>- Borrower information: Basic attributes of the borrowers such as annual income, condition of employment, interest rate, loan status, etc.
>- Loan performance information: Metrics evaluating the risk associated with the loans such as Prosper score and bank card utilization, etc. 
> There were some elements that need to be fixed, in order to create interesting and trustworthy analyses and visualizations. Variables with missing values were dropped to make the Dataset more accurate.  
> This investigation will be analyzing factors that could influence borrower's APR and what loans were taken by what type of borrowers.

## Summary of Findings

> After analyzing each variables. it was observed that 21317 loans were given out to borrowers that did not disclose their oppcupation they instead selected Others as their occupation. I filled rows with empty Occupation values with Not Specified, and it is also surprising to see that these individuals had access to loans (Not Specified - 1333). I however did not see any need to do transformations.
>Also, a lot of people didn't specify why they requested for loans and some other people specified Other as their reason. This wasn't a major issue as they didn't make up majority of the population.
>Adding that that, borrower' Scores (given from 0 to 11) gave the strongest negative relationship with borrower's APR.<br/>
>Borrowers with different letter ratings were also analyzed. It came out that borrowers with the lowerest rating(HR) received higher APR percentage, and borrower with high rating A(A) received lowers APR percentage. This differentiate groups of people in terms of APR received based on their rating and scores.

## Key Insights for Presentation

> First, histogram plot were created to visualize the distribution of different selected variables. After exploring some variables related to BorrowerAPR, it was observed that Borrower APR reduces as the Income Range of borrowers increase. This means that borrrowers that have high income enjoy lower interest rates on the platform. This make sense becasue people with higher income tend to be more reliable and therefore given lower BorrowerAPR.<br/>
> Also, plots showed the lowerest rating(HR) of borrowers received the highest APR percentage, and borrowers with highest rating (AA) received the lowerst APR percentage.