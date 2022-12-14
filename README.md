# Election_Analysis

## Project Overview
A Colorado Board of Education member has asked us to complete the following tasks to complete an election audit of a recent congressional election election. 

1. Total number of votes cast
2. Number of votes and the percentage of total votes for each county in the precinct
3. County with the largest number of votes cast
4. Number of votes and the percentage of the total votes each candidate received
5. The winner of the election with their vote count and their percentage of the total votes

## Resources
- Data Source: election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1

## Election-Audit Results
The analysis of the election show that:
1. There were 369,711 total votes cast
2. Votes and % of votes for each county:
  - Jefferson received 10.5 and (38,855)
  - Denver received 82.8 and (306,055)
  - Arapahoe received 6.7 and (24,801)
3. The county with the largest number of votes was Denver county. 
4. Votes and % of votes for each candidate: 
  - Charles Casper Stockham: 23.0% (85,213)
  - Diana DeGette: 73.8% (272,892)
  - Raymon Anthony Doane: 3.1% (11,606)
5. The winner of the election was candidate Diana Degette with 272,892 votes and 73.8% of the total vote.

## Election-Audit Summary
This code could easily be used for any election. As shown below, our code runs through each line of data in the election results spreadsheet to easily count the total number of votes for each candidate and for each county. 
![ForLoopCode](https://github.com/nicole-tough/Election_Analysis/blob/main/ForLoopCode.PNG)

Our code could easily be modified in future elections to find further results.
1. The code could incorporate findings about voter turnout if some additional information was included in the election results data. The additional information needed would be the population of eligible voters in each county. If provided this information, our code could include voter turnout for each county.
2. Our code could also provide demographic information about the populaiton of voters in this election given the information was provided in the election results. We could add additional conditionals to our code to find out which portions of the population voted more than others. This key information could aid campaigns in creating a more strategic plan of action for future elections.
