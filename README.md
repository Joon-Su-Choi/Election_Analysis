# Election_Analysis

## Table of Contents

#### 1. Overview of Election Audit
#### 2. Election-Audit Results
#### 3. Election-Audit Summary

###### 1. Overview of Election Audit

  A Colorado Board of Elections employee wants us to analyze the election audit of a recent local congressional election. The information we are looking for are the voter turnout for each county, the percentage of votes from each county out of the total count, and the county with the highest turnout.
  
###### 2. Election-Audit Results

![election_result_outcomes](https://user-images.githubusercontent.com/95505596/149633831-cf097f40-525a-4d0b-994f-d02bae3de88b.png)
  - This congressional election had 369,711 votes casted.

![total_vote_code](https://user-images.githubusercontent.com/95505596/149634264-f9267d38-ced9-4608-8e02-af347430fb80.png)
  - The number of votes and their percentages in each county are presented as the following:
    - Jefferson: 10.5% (38,855)
    - Denver: 82.8% (306,055)
    - Arapahoe: 6.7% (24,801)

![largest_county_votes](https://user-images.githubusercontent.com/95505596/149634154-c6a23d9e-25ed-457c-ad72-cc2987f607db.png)

  - Denver had the largest number of votes.

![largest_county_turnout](https://user-images.githubusercontent.com/95505596/149634350-6c3c7b99-672f-462e-bfcd-df3ea61ea61b.png)
  - The number of votes and their percentages each candidate received are presented as the following:
    - Charles Casper Stockham: 23:0% (85,213)
    - Diana DeGette: 73.8% (272,892)
    - Raymon Anthony Doane: 3.1% (11,606)

![candidate_results](https://user-images.githubusercontent.com/95505596/149634391-cf224b4b-1540-43fe-90aa-2db814498137.png)
  - The winner of the election was Diana DeGette with a vote count of 272,892 (73.8% of the total votes).
 
![winning_candidate](https://user-images.githubusercontent.com/95505596/149634427-5a94523a-b258-4c67-b4a0-e51be979f4d9.png)

###### 3. Election-Audit Summary

  This script should save the election commission time for future elections. The code should run showing the same data we have as the first image posted in this readme given that the excel file provided remains in the same format with column A (ballot ID), column B (county), and column C (candidate). All we need to do is replace the columns with the current election data and run the code.

  The script could be improved by showing how many and what percentage of votes from each specific county went to each of the candidates. This shows where each county's priorities lie from which candidate they prefer. Adding onto this idea and the script, we could also display which county preferred which candidate.
