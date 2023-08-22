# Console-Finances
Financial analysis using javascript


//<-- Pseudo Code -->//

You have been given a dataset composed of arrays with two fields, Date and Profit/Losses.

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

Your final code should print the analysis to the console.

console.log (finances)
console.table (finances)

let months = finances.length
console.log (months)

let total = 0
let change = 0
let average; = 
let analysis;
let net = 0
let netarray = [];
let netChangeSum = 0
//least min
// greatest max
// least list 
// greatest list = []

for (let index = 0; index < finances.length; index ++) {
    for (let index2 = 0; index 2 < finances[index].length; index2++) {
        console.log(index2)
        
        if(typeof finances[index2] !== `string`) {
            //        0  +  867884
            total += finances[index][index2] 
            console.log(total);
            change = finances[index][index2] - net;
            net = finances[index][index2];
            netArray.push(change);

            console.log(`total: ${total}`);
            console.log(`change: ${change}`);
            console.log(`net: ${net}`);
            console.log(`netArray: ${netArray}`);
        }
    } 
    
}

for(let index =0; index < netArray.length; index ++) {
    netChangeSum += netArray[index]; 
}

console.log(netChangeSum);

average = Math.round((netChangeSum / 86) * 100) / 100;

console.log(average);

analysis = `Financial Analysis` + `\n` + `-----------------` + `\n` + `Total Months` + momths + `\n` +
`Total: $` + total + `\n` +
`Average Change: ` + average + `\n`
`Greatest Increase in Profit:` + greatest[0] + `: $` + greatest[1] + `\n`
`Greatest Decrease in Profit: ` least[0] + `\n`;


console.log(analysis)

analysis = 
Financial Analysis
-------------------
Total Months: $(months)
Total: $ $(total)
Average Change: $(average)
Greatest Increase in Profit: 




Your task is to write JavaScript code that analyzes the records to calculate each of the following:

* The total number of months included in the dataset.

* The net total amount of Profit/Losses over the entire period.

* The average of the **changes** in Profit/Losses over the entire period.
  * You will need to track what the total change in Profit/Losses are from month to month and then find the average.
  * (`Total/(Number of months - 1)`)

* The greatest increase in Profit/Losses (date and amount) over the entire period.

* The greatest decrease in Profit/Losses (date and amount) over the entire period.

When you open your code in the browser your resulting analysis should look similar to the following:

  ```text
  Financial Analysis 
  ----------------
  Total Months: 86
  Total: $38382578
  Average Change: -2315.12
  Greatest Increase in Profits/Losses: Feb-2012 ($1926159)
  Greatest Decrease in Profits/Losses: Sep-2013 ($-2196167)
  ```

Your final code should print the analysis to the console.


****************************************

Rock Paper Sissors Game

1. Array of choices rock "r", paper "p", scissors "s"
2. Prompt choices for "r", "p", "s"
3. Random choice selected for r, p, s
4. Alert for Win/Lose/Draw combinations "you win", " you lose', "draw"

    If user selects "r", computer selects "s" then user wins
    If user selects "r", computer selects "p" then user loses 
    If user selects "r", computer selects "r" then user draws

    If user selects "p", computer selects "s" then user loses 
    If user selects "p", computer selects "r" then user wins
    If user selects "p", computer selects "p" then user draws 

    If user selects "s", computer selects "p" then user wins
    If user selects "s", computer selects "r" then user loses 
    If user selects "s", computer selects "s" then user draws

5. Alert Result "you win" , "you lose" , "draw" or "error" for undefined entry
6. Prompt Play Again
7. Total Score after 10 rounds



*******************************************

var and let create variables that can be reassigned another value.

const creates "constant" variables that cannot be reassigned another value.

developers shouldn't use var anymore. They should use let or const instead.

if you're not going to change the value of a variable, it is good practice to use const.

