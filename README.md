# Election_Results

## Overview of Project

### Purpose
The election commission has requested the election result analsysis to be extended to include details on
candidate results and details about the voter turnout in each county.

The Election audit will need to provide a summary regarding the votes per candidate along with providing a result
of the winning candidate but also provide an analysis on votes provided by each county including thhe following:
 - The total number of votes for each county
 - The county with the highest number of votes
 - The percentage of votes each county received out of the total votes for the state

## Election Audit Results
After reviewing the [analysis of the election data](/analysis/election_analysis.txt) the following outcomes have been determined:
 - A total of 369,711 votes were cast in the congressional election
 
	![Total Vote Count](/analysis/Total_Votes.PNG)
 - The total vote count for each county is as follows
	- Jefferson: 10.5% (38,855 votes)
	- Denver: 82.8% (306,055 votes)
	- Arapahoe: 6.7% (24,801 votes)
	
	![Per County Vote Count](/analysis/County_Votes.PNG)
 - The County with the largest number of votes is Denver with a total of 306,055 votes  
	![County with the largest turnout](/analysis/largest_county_turnout.PNG)
 - The total vote count for each candidate is as follows:
	- Charles Casper Stockham: 23.0% (85,213 votes)
	- Diana DeGette: 73.8% (272,892 votes)
	- Raymon Anthony Doane: 3.1% (11,606 votes)  
![Candidate Vote Count](/analysis/candidate_votes.PNG)
 - The results show Diana DeGette won the election with the following results:
	- Winning Vote Count: 272,892
	- Winning Percentage: 73.8%  
![Winning Candidate](/analysis/winning_candidate.PNG)
	
## Election Audit Summary
The script can be adjusted to cater for the entire election process  including the county, state presedential and house elections rather than only catering for the county elections.
This would result in the voting results for the entire election process being more accurate and the results process being more effecient. 

In order to cater for different types of elections the following adjustements could be made to the script:
 - The script could be adjusted to take the votes for each county within a state in order to determine the winning party/candidate for each state
 - The script could be further adjusted to apply the criterea required to determine the winer of the presedential election based on the electoral college system