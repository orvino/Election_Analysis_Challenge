# Election_Analysis

## Challenge Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentag of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.10.1, Visual Studio Code 1.63.2

## Summary
The analysis of the election. show that:
- There were 369,711 votes cast in the election.
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
  
- The candidate results were as follows:
  - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
  - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
  
- The winner of the election was:
  - Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.

- Election audit summary:
  - The creation of this program file, can be used in other elections.  While currently, this is serving to perform this task given three variables; ballots,         candidates, and counties.  We can expand on this to other degrees.
  - If we would like to change from known counties to known voting districts, we can take the original code:
  
  <img width="690" alt="Screen Shot 2022-01-03 at 2 07 39 PM" src="https://user-images.githubusercontent.com/91889241/147975196-42497c20-1407-4339-aab0-13888ccaace1.png">
  
   - And change the county references to districts:
    
  <img width="620" alt="Screen Shot 2022-01-03 at 2 11 56 PM" src="https://user-images.githubusercontent.com/91889241/147975586-816bb4c8-1b46-4a49-8649-f98d35b203c7.png">

  - We can also expand the selection to add cities or additional variables to the program.  For example, if we needed to add political party affiliation (presented as if in column 4 of the csv file) to the candidate, we would first need to create new variables to hold any forseeable party affiliations to the candidate.  Along with a new set of lists and dictionaries to contain them.  And then we would expound on the for loop statement to include the party with the candidate in its own if statement.  This will allow us to create more information with flexibility.

<img width="329" alt="Screen Shot 2022-01-03 at 2 28 20 PM" src="https://user-images.githubusercontent.com/91889241/147977078-6d23c1b0-224f-4bcb-ab99-fa3d2f56bba1.png">

<img width="436" alt="Screen Shot 2022-01-03 at 2 28 34 PM" src="https://user-images.githubusercontent.com/91889241/147977093-48b0624b-93f2-4652-9923-49234af2427a.png">

<img width="562" alt="Screen Shot 2022-01-03 at 2 34 47 PM" src="https://user-images.githubusercontent.com/91889241/147977594-97fbbc52-960b-43a7-80c5-041ce924f405.png">
