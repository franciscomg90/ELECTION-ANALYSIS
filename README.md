# ELECTION-ANALYSIS

## Overview
The purpose of this analysis is to get a complete election audit which results will sort by county and candidate the total votes and percentage of each one as well as the winner of both categories.

## Election Audit Results
>**_Total vote count_** might be the easiest calc made in this excersise using just a for loop in the csv file till the last filled row.

![Total_votes](https://github.com/franciscomg90/ELECTION-ANALYSIS/blob/main/Resources/TOTAL%20VOTES%20Results.PNG)
![Total_code](https://github.com/franciscomg90/ELECTION-ANALYSIS/blob/main/Resources/TOTAL%20VOTES.PNG)

>**_County votes segregation_** was a bit more complicated since I needed to declare several variables through the code and calculate total  and percentage for each county, but as well as the total votes calc, "for" iterations works great for this purpose.

![results_by_county](https://github.com/franciscomg90/ELECTION-ANALYSIS/blob/main/Resources/results%20by%20county.PNG)

![code_by_county](https://github.com/franciscomg90/ELECTION-ANALYSIS/blob/main/Resources/variables%20county.PNG)

>**_The largest_ county** resulted to be!

![largest county](https://github.com/franciscomg90/ELECTION-ANALYSIS/blob/main/Resources/largest%20county.PNG)

Code demostration:

![largest county code](https://github.com/franciscomg90/ELECTION-ANALYSIS/blob/main/Resources/county%20summary%20code.PNG)

>**_Candidate votes segregation_** is as follows:

![candidate segregation](https://github.com/franciscomg90/ELECTION-ANALYSIS/blob/main/Resources/candidate%20segregation.PNG)

**_Winner Candidate_** resulted to be!

![winner candidate](https://github.com/franciscomg90/ELECTION-ANALYSIS/blob/main/Resources/winner%20candidate.PNG)
## Election Audit Summary
As a **business proposal** I would say this code could be perfectly applied to any local election. As the code doesn't have any county or candidate name printed inside, it can be used to similar audit as long as the data provided CSV file have the same format, if not, **_I would propose_** new variables to find out where the candidate name and county column is located and input these variables in the row count calculation. 

![row count](https://github.com/franciscomg90/ELECTION-ANALYSIS/blob/main/Resources/row%20count.PNG)

As a **_second proposal**, it can be adapted to manage more data for each vote id as Gender, Age, Race or other demographic info by adding the same structure as the county and candidate and refactoring the code to make it more efficient

![structure script](https://github.com/franciscomg90/ELECTION-ANALYSIS/blob/main/Resources/county_code.png)
