"Hello World!"" We are Isabel and Daniza. 

Primary question: What is the Revenue deficit(the difference(subtracted) of total revenue and total expenditure) for the U.S. urban and rural states during the stock market crash from 2008 and 2010 and the their debt at the end of the fiscal year?

For our project, we are displaying data analyses on annual findings of finances from 12 US states (Urban and Rural) during the stock market crash from 2008 to 2010, focusing on Revenue deficit and Debt at end of fiscal year.

First, we gathered and download three separate data sets based on year (2008, 2009, 2010). We encountered an issue where R could not recognize the values due to the format and layout of the data set. So, we transposed, combined into one master data set, and transformed the data in a way where the variables are in columns and States are under 1 column and in rows with the numerical values. Now, R is able to successfully understand our master data set.

We decided to only focus on 12 urban and rural states based on their high number of population and some variables i.e., Total revenue, total expenditure, and Debt at end of fiscal year.So, we subset data using the filter and select function to easily plot the graph with our desired variables and created a new data frame. We did some quick calculation to find the revenue deficit by subtracting total expenditure from total revenue. Then, we created the difference in its own data frame and combined to the subset data frame. And we plot the data using the ggplot function.

The data shows revenue deficit for all Urban and Rural States from 2008 to 2010, to investigate the financial loss or how much government spending(expenditure) exceeded its revenue during the stock market crash. So, if a state government has a significant revenue deficit, then it means that their income/revenue is not sufficient to cover its basic services. We can see that Urban states are greatly more affected than the Rural states because Urban states are economically developed than Rural states and are more likely to encounter financial loss.

Then another data shows the debt at end of fiscal year to show how much the states owe from 2008. 