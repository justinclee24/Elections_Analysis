# Elections Analysis

## Overview of Election Audit
A Colorado Board of Elections employee has assigned the tasks given below to complete the election audit of a relevant local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Get a list of counties with number of votes and percentage of total votes.
4. Determine the county with the highest voter turnout.
5. Calculate the percentage of votes each candidate won.
6. Calculate the total number of votes each candidate won.
7. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Studio (VS) Code 1.57.1

## Election-Audit Results
The analysis of the local congressional election shows:
- There were 369,711 votes cast in the election.
- The counties were:
   - Jefferson County
   - Denver County
   - Arapahoe County
- The county results were:
   - Jefferson: 10.5% (38,855)
   - Denver: 82.8% (306,055)
   - Arapahoe: 6.7% (24,801)
- The county with the largest vote turnout was : Denver
- The candidates were:
   - Charles Casper Stockham
   - Diana DeGette
   - Raymon Anthony Doane
- The candidate results were:
   - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
   - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
   - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
- The winner of the election was:
   - Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.

(See image below for Election Results text file.)

<img width="317" alt="Screen Shot 2021-07-02 at 10 23 06 AM" src="https://user-images.githubusercontent.com/85330159/124303446-b1e55d00-db1f-11eb-91ba-5e2b90b74710.png">

## Election-Audit Summary
In conclusion, it is possible for this script to be used on any other future election, as needed, saving election offices significant amounts of time by speeding up the counting process. In order to convert the script to be used in other elections, the data that is being referenced within the code needs to be updated to align with whichever new election is utilizing the script. Also, if the election is dealing with anything higher than local congressional district level, there needs to be script added to account for the state and national level to show results for these portions of the process. However, this script is a solid foundation to give future elections a kickstart on their counting process.  
