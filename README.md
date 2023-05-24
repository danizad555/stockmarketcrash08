"Hello World!" We are Isabel and Daniza. 

Primary question: What is the Revenue deficit(the difference(subtracted) of total revenue and total expenditure) for the U.S. urban and rural states during the stock market crash from 2008 and 2010 and the their debt at the end of the fiscal year?

For our project, we are displaying data analyses on annual findings of finances from 12 US states (urban and rural) during the stock market crash from 2008 to 2010, focusing on Revenue deficit and Debt at end of fiscal year.

First, we gathered and download three separate data sets based on year (2008, 2009, 2010). We encountered an issue where R could not recognize the values due to the format and layout of the data set. So, we transposed, combined into one master data set, and transformed the data in Excel where the variables are in columns and States are under 1 column and in rows with the numerical values. Now, R is able to successfully understand our master data set.

We decided to only focus on 12 urban and rural states based on their highest number of population and some variables i.e., Total revenue, total expenditure, and Debt at end of fiscal year. So, we subset data using the filter and select function to easily plot the graph with our desired variables and created a new data frame. We did some quick calculation to find the revenue deficit by subtracting total expenditure from total revenue. Then, we created the difference in its own data frame and combined to the subset data frame. And we plot the data using the ggplot function. The same goes for the second data plot for debt at the end of the fiscal year.

The data shows revenue deficit for all urban and rural States from 2008 to 2010, to investigate the financial loss or how much government spending(expenditure) exceeded its revenue during the stock market crash. So, if a state government has a significant revenue deficit, then it means that their income/revenue is not sufficient to cover its basic services. We can see that urban states are greatly more affected than the rural states because urban states are economically developed than rural states and are more likely to encounter financial loss. Then, another data shows the debt at end of fiscal year to show how much the state governments owe during 2008-2010. It displays the total amount of outstanding borrowing by the state government during the stock market crash.

Resources:

Three raw data sets: https://corgis-edu.github.io/corgis/blockpy/finance/

How we chose to subset 12 urban and rural US states (based on highest number of population): 
  1) Rural: https://www.nationalpopularvote.com/rural-states-are-almost-entirely-ignored-under-current-state-state-system 
  2) Urban: https://www.newgeography.com/content/005187-america-s-most-urban-states 
 
 Finding the Revenue deficit: https://www.business-standard.com/about/what-is-revenue-deficit
 
 Understanding national debt/debt at end of fiscal year: https://fiscaldata.treasury.gov/americas-finance-guide/national-debt/
 
 Access to data visualizations generated in R:
  1) Revenue deficit in 12 urban and rural states during the stock market crash from 2008 to 2010: https://rpubs.com/danizad/stockmarketcrash08
  2) Debt at the end of the fiscal year for 12 urban and rural states during the stock market crash from 2008 to 2010: https://rpubs.com/danizad/stockmarketcrashdebt

Video presentation link: 
 
 *NOTE* 
 
 If you plant to run the code, do not forget to change your file path. You can set your working directory to the folder where the CSV file is located and insert "/state_finances.csv". For example: 
 
 Windows: "C:/Users/daniz/Downloads/PBLab/Biostatistics/Project PROPEL/stockmarketcrash08/processed data/state_finances.csv" shorten version but first set working directory to the folder Biostatistics: "../Project PROPEL/stockmarketcrash08/processed data/state_finances.csv"
 
 Mac: /Downloads/state_finances.csv or set working directory to the folder where the file is. On the console section in R, copy file path and insert "/state_finances.csv"
