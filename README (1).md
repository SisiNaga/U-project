# (Dataset Exploration of the Loan Data From Prosper )
## by (Osasenaga Oriakhi)


## Dataset

>  This data set is called the Loan Data from Prosper.It contains 113,937 loans with 81 variables on each loan.It contains details about the borrowers' employment status,whether or not their income can be verified,whether or not they own homes,whether or not they have taken a Prosper loan before,their credit score range,their occupation,the purpose of the loan, etc. The variables also include the loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.

>The dataset can be found here:(https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1581581520570000)
>Its feature documentation can be found:(https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&ust=1554486256024000)
 

## Summary of Findings
> From the plots(bar and pie plots),it looks like the most common reason for the loan was to pay off a debt.About 58% of people that took the loan, gave debt consolidation as their reason for acquiring the loan.
> I discovered from the exploration that whether or not the borrower was a home owner was not a factor that affected the borrower getting the loan.The percentage of borrowers that were home owners and those that weren't was equal.
> There were only a few borrowers who defaulted in their payment.4.5% were defaulters.
> Looks like most people(77%) preffered the three years loan term to the five years and the one year loan term combined.
> From the data exploration of the available data(as only about 22,000 entries were available) ,looks like a large amount of borrowers,about fifteen thousand are taking the Prosper loan for the first time.  
> It looks like loans were given out more to people with income that could be verified.This was discovered when I plotted a barchart of borrowers with the variable "incomeverifiable".This will be part of my explanatory presentation.
> Also, borrowers who have completed the loan payment have more people that dont have homes.Those who are currently paying off their loans have more people who are home owners.
> More employed people are home owners, more self employed people and unemployed people did not have homes. 
> Looks like borrowers who have completed their payment, in the final payment progress or currently servicing the loan earn more than those who defaulted in their payment. 
> The set of borrowers who had more peple with incomes that could be verified were those who were employed.This was seen from the multivariate plot above where I plotted employment status against stated monthly income and set hue as income verifiable.I will incorporate this plot into my presentation.
> It was also discovered from the exploration that borrowers who were employed took out larger amounts as seen in the barplot where employment status was plotted against loan original amount.
> Finally ,from the scatter plot, it seems like borrower's interest rate and borrower's annual percentage rate had a positive correlation.i.e an increase in one may reflect in an increase in the other.  
This last two findings will form the final portion of my explanatory presentation. 



## Key Insights for Presentation

> Select one or two main threads from your exploration to polish up for your presentation. Note any changes in design from your exploration step here.
I focus on the category of borrowers that seemed to have been favored in terms of them getting the loan offers.I do this by showing the barplot that shows that loans were given more to people with incomes that can be verified.
I also focus on a few factors that mighty have contributed to them being favored over others in the acquiring of the loans. I will show this  by displaying a plot that shows that the set of borrowers that had more people with incomes that could be verified were the employed borrowers. I will also show that these set of borrowers took out larger amounts than others. 
Lastly, I show the relationship between the interest rate for the loan and the annual percentage rate with a scatter plot.