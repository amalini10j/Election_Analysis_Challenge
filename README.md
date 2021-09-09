# Election_Analysis_Challenge
A new repository created for submitting the election analysis challenge for Module 3
## Overview of Election Audit 
A Colorado Board of Elections Employee has given the task to complete the election audit of a recent congressional election by following steps below:
1. Calculate the total no. of votes cast
2. Get a complete list of counties where votes were cast
3. Calculate the vote turnout for each county
4. Calculate the percentage of votes each county received
5. Determine the county that received had the highest vote turnout
6. Get a complete list of candidates who received votes
7. Calculate the total no. of votes each candidate received
8. Calculate the percentage of votes each candidate received
9. Determine the winner of the election based on popular vote

## Resources
**Data Source:** election_results.csv
**Software:** Python 3.8, Visual Studio Code 1.59

## Election Audit Results
There were a total of 369,711 votes cast in the election between three counties and 3 candidates. The data below helps in identifying the the winning county and the winning candidate

### County Election Results
The counties voting results are as follows:
- Jefferson county received 38,855 votes which was 10.5% of the votes
- Denver county received 306,055 votes which was 82.8% of the votes
- Arapahoe county received 24,801 votes which was 6.7% of the votes

From the above data, **Denver** county received the **highest voter turnout of 83.8%**

### Candidate Election Results
1. The following candidates participated in the election:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
2. The results of each candidate are as follows:
    - Charles Casper Stockham received 85,213 votes which was 23.0% of votes 
    - Diana DeGette received 272,892 votes which was 73.8% of votes
    - Raymon Anthony Doane received 11,606 votes which was 3.1% of votes

From the above candidate data, the winner of the election was **Diana DeGette with 272,892 votes which made up 73.8% of votes**

## Election Audit Summary
The current election audit script is flexible to be used for any other election result with varying no. of counties and/or candidates. It can also be used to perform analysis for a nationwide election by looking into state wise election turnout.

1. Nation wide election audit - The data would have states mentioned for each county and the script could be modified to roll up the county vote turnout at a state level to determine which states are leading in terms of the national votes.

2. Understanding candidate vote share in each county - The script can be modified to add code to determine which candidate belongs to which county. This would give a detailed audit result to understand the vote share between the candidates within each county.


