# Election_Results

## Overview of Project

### Purpose
The election commission has requested the election result analsysis to be extended to include details on
candidate results and details about the voter turnout in each county.

The Election audit will need to provide a summary regarding the votes per candidate along with providing a result
with the winning candidate but also provide an analysis on votes provided by each county including thhe following:
 - The total number of votes for each county
 - The county with the highest number of votes
 - The percentage of votes for each county out of the total count

## Election Audit Results
After reviewing the [analysis of the election data](/analysis/election_analysis.txt) the following outcomes have been determined:
 - A total of 369,711 votes were cast in the congressional election
 - The total vote count for each county is as follows
	- Jefferson: 10.5% (38,855 votes)
	- Denver: 82.8% (306,055 votes)
	- Arapahoe: 6.7% (24,801 votes)
 - The County with the largest number of votes is Denver with a total of 306,055 votes
 - The total vote count for each candidate is as follows:
	- Charles Casper Stockham: 23.0% (85,213 votes)
	- Diana DeGette: 73.8% (272,892 votes)
	- Raymon Anthony Doane: 3.1% (11,606 votes)
 - The results show Diana DeGette won the election wit hthe following results:
	- Winning Vote Count: 272,892
	- Winning Percentage: 73.8%
	
![analysis of the election data](/Resources/election_analysis.PNG)
	
## Election Audit Summary
The analysis script is not limited to analysisng data for congressionsal elections and can be modified slightly 
for other elections such as senate, federal or even presidential elections.
The current sctipy is limited to analysis data at a congressional level but can be modified to accomodate
not just per county votes but also determine the electoral college for the presidential elections.

In order to cater for different type of election the following adjustements would need to be made to the script:
 - The script would need to be adjusted to analyize votes made for each candidate and which party the candidate is aligned with
 - The script would be modified to take the winning candidate from each county in a state and determine the winning party by analysing the party with the majority of winnning candidates that represent that party