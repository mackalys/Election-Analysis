# Election_Analysis

## Project Overview
A colorado Board of Elections employee has given you the following task to complete the election ausit of a recnt locla congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who recieved received.
3. Calculate the total number of votes each candidate recieved.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Soure: election_results.csv
- Software: Python 3.10, Visual Studio Code, 1.63.2

## Election Audit Results
The analysis of the election show that:
- There were 369,711 votes cast in the election.
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were:
  - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
  - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
- The winner of the election was:
  - Diane DeGette, who received 73.8% of the vote and 272,892 number of votes.
- The total number of votes and percentages for each county were:
  - Jefferson County had 38,855 votes, making up 10.5% of the total votes.
  - Denver County had 306,055 votes, making up 82.8% of the total votes.
  - Arapahoe County has 24,801 votes, making up 6.7% of the total votes.
- The County with the largest voter turnout was:
  - Denver County had the largest voter turnout with a total of 306,055 votes, making up 73.8% of the total votes.

![election_analysis_screenshot](https://github.com/mackalys/election-analysis/blob/main/analysis/election_analysis_screenshot.png)

## Election Audit Summary
After the initial analysis of the winning candidate using total number of votes and percentage of the total votes for each candidate, we added a breakdown of the votes and vote percentages for each county. By looking at how many votes were placed in each county, it shows which counties are the most important for the candidates to win over. From the analysis we conducted, we can see that Denver County has the largest voter turnout compared to Jefferson County and Arapahoe County. This would mena that the candidates should focus on winning over Denver County because it makes up 82.8% of the votes.

The script we have created could be used any election. All that needs to be done is to switch out the counties for city or even states. As long as there is a .csv file to run, the script can make an analysis of the voting data.
