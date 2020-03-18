# powerquery-functions
A repository with useful custom power query functions.

The following functions are available:

<h2>getStartDateFromWeekinYear</h2>
File: powerquery-getStartDateFromWeekinYear
Description:  

<h2>getEndDateFromWeekinYear</h2>
File: powerquery-getEndDateFromWeekinYear
Description: 

<h2>roundNearestByInterval</h2>
File: powerquery-roundNearestByInterval
Description: Return nearest rounded number by the provided interval
Example 1: number 2.15 with interval 0.25 will be rounded to 2
Example 2: number 2 with interval 0.25 will be rounded to 2
Example 3: number 2.35 with interval 0.25 will be rounded to 2.5

<i>Parameters</i>
    inputNumber: number that needs to be rounded. The number can be decimal
    inputInterval: interval to be taken account in the rounding. The number can be decimal

https://community.powerbi.com/t5/Power-Query/Rounding-Numbers-up-in-increments-of-0-25/m-p/979914#M33695

<h2>Custom function from others</h2>
* Maxim Zelensky created 2 custom functions to get date from ISO week or to get ISO week from a date 
They can be found here https://gist.github.com/r-k-b/18d898e5eed786c9240e3804b167a5ca
* Imke Feldmann,aka the BIaccountant, created a custom functions to get date the number days between 2 dates taking care into account week-ends and other holiday days. The custom function with a great explanation can be found here https://www.thebiccountant.com/2020/02/20/date-networkdays-function-for-power-query-and-power-bi/




