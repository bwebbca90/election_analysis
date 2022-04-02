# Election Analysis
![Image of Election Outcome](<./resources/Election_Results.png>) 

## Overview of Election Audit
The Colorado Board of Elections requested an audit regarding a recent election for a congressional election. They have requested the following:
1) Calculate the total number of votes cast.
2) Get a complete list of candidates who received votes.
3) Calculate the total number of votes each candidate received.
4) Calculate the percentage of votes each candidate won. 
5) Determine the winner of the election based on popular vote.
6) Calculate the voter turnout for each county.
7) Calculate the percentage of votes each county contributed to the election.
8) Determine which county had the largest turnout.

### Purpose
The purpose of this analysis is to verify the winner of the popular election across three counties and the counties' participation in said election. Post-election audits are necessary for ensuring the accuracy of the results. 


### Election-Audit Results
- 369,711 total votes were cast in this congressional election across three counties in the precinct.
- Results by County Breakdown: 
 1) Arapahoe had the lowest votes in the precinct, 6.7% with 24,801 total votes. 
 2) Jefferson had 10.5% of the precinct's votes at a total of 38,855 votes. 
 3) Denver had the largest participation of the precinct at 82.8% and a total vote number of 306,055.
- Denver had the the highest number of votes in the precinct at 306,055.
- Results by Candidate Breakdown: 
 1) Raymon Doane received 3.1% of the precinct's votes for a total of 11,606 votes. 
 2) Charles Stockham received an even 23% of the precinct's votes for a total of 85,213 votes.
 3) Diana DeGette received the remaining 73.8% of the precinct's votes for a total of 272,892 votes.
- With 272,892 total votes and 73.8% of the precinct's support, Diana DeGette won the popular vote in this congressional election. 

## Election-Audit Summary
This Python script could be used for a multitude of other election-related activities. For one, this script could be used to determine participation in voting districts to equalize access to polling places. In the event that a precinct has to be restructured to make more polling places available rather than risk overcrowding, one can determine the highest-traffic polling places by moving the counties to a dictionary and adding lists for the particular polling places within those dictionaries and requesting the return of percentage polling places receiving votes. ALternatively, it could be expanded to cover multiple congressional districts by segmenting the counties into lists and creating congressional district dictionaries, thus returning the results of each district for the total congressional election for the state. 
