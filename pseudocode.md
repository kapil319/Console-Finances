# Console-Finances Pseudocode

## You have been given a dataset composed of arrays with two fields, Date and Profit/Losses.

1. Array of 2 fields: "Date" , "Profit/Losses"
2. Calculate total no. of months included in dataset
3. Net total amount of Profit/Losses over entire period
4. Average of the changes in Profit/Losses over entire period
5. Log the total no. of changes in Profit/Losses are from month to month and find the average (`Total/(no. of months - 1)`) 
6. Greatest increase in P/L (date and amount)
over entire period.
7. Greatest decrease in P/L (date and amount)
over entire period.

8. When you open your code in the browser your resulting analysis should look similar to the following:

  ```text
  Financial Analysis 
  ----------------
  Total Months: 86
  Total: $38382578
  Average Change: -2315.12
  Greatest Increase in Profits/Losses: Feb-2012 ($1926159)
  Greatest Decrease in Profits/Losses: Sep-2013 ($-2196167)
  ```

The final code should print the analysis to the console.