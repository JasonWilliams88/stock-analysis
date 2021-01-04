# stock-analysis
##Hub of yearly stocks markets trends using refactored code.
---
---
# Overview
The following code uses arrays to analyze stock market trends on a per a year bases.
The stock market ticker, yearly volume, and the percent change in the stock is returned.
The code contains formatting and use of use additions.
Finally old code was refactored to increase efficiency.
---

## Results
### The following 2 PNGs are the outputs for 2018 and 2019
Outputs for stocks in 2017
![VBA_Challenge_2017.png](https://github.com/JasonWilliams88/stock-analysis/blob/main/VBA_Challenge_2017.png)

Outputs for stocks in 2018
![VBA_Challenge_2018.png](https://github.com/JasonWilliams88/stock-analysis/blob/main/VBA_Challenge_2018.png)

### The following 4 PNGs are the efficiency increase due to the refactoring
Original code for 2017

![2017Old](https://github.com/JasonWilliams88/stock-analysis/blob/main/2017Old.png)

Original code for 2018

![2018Old](https://github.com/JasonWilliams88/stock-analysis/blob/main/2018Old.png)

New code for 2017

![2017New](https://github.com/JasonWilliams88/stock-analysis/blob/main/2017New.png)

New code for 2018

![2018New](https://github.com/JasonWilliams88/stock-analysis/blob/main/2018New.png)


Main change from refactoring code.

![VariableArray.png](https://github.com/JasonWilliams88/stock-analysis/blob/main/VariableArray.png)

---
## Summary/Analysis

#advantages/disadvantages in general of refactoring

By refactoring code we saved man hours writing the code and headache of troubleshooting an entirely new code.
Issues can stem from old variable being left in the code resulting in troubleshooting.

#advantages/disadvantages of refactoring the current code

The refactoring of the code decreased the time the code ran 5 times faster greatly increasing its efficiency.
This time savings will be more obvious when running the code for the entire stock market as opposed to the 12 we observed today.
The old code was inefficient because we needed to loop through the entire code for every stock ticker. 
Using the variable arrays linked above, we were able to store the total, start, and end values in created variable arrays going through the data set once.
The tickerIndex variable gave us a way to access the stored info
