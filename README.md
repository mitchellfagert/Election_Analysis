# Election_Analysis

## Project Overview
I have been tasked to assist and complete an audit of a local election for the Colorado Board of Elections. To complete this task I have used the programmatic tools of Python, Visual Studio Code, and Git.

To complete this audit/project I have done the following:
1. Calculated the total number of votes casted.
2. Compiled a complete list of candidates who received votes.
3. Cacluated the total number of votes each candidate received.
4. Calculated the percentage of votes each candidate received.
5. Determined the winner of the election based on the popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Studio Code, Git

## Audit Election Summary
The analysis of the election will show that:
- There were 369,711 total votes casted in the election.
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were:
  - Charles Casper Stockham received 23.0% of the votes and 85,213 total votes.
  - Diana DeGette received 73.8% of the votes and 272,892 total votes.
  - Raymon Anthony Doane received 3.1% of the votes and 11,606 total votes.
- The winner of the election was:
  - Diana DeGette, who received 73.8% of the vote and 272,892 of the total votes.

In addition to data listed above, I have written additional code to further provide a breakdown of voting data based on county information.

This additional analysis will show that:
- The counties of the elecetion are:
  - Jefferson County
  - Dener County
  - Arapahoe County
- The county results were:
  - Jefferson County received 10.5% of the votes and 38,855 total votes.
  - Denver County received 82.8% of the votes and 306,055 total votes.
  - Arapahoe County received 6.7% of the votes and 24,801 total votes.
- The County with the largest number of votes: Denver County

Below is the output of the election audit findings which is produced by the python code and printed into a text file.

![Election_Audit_Results](https://user-images.githubusercontent.com/107579508/177593520-e262cb4b-1fac-4165-83df-b373912b8c8b.png)

## Election-Audit Summary

In summary, you can see the which candidate won the election (based on the popular vote) and which county contained the most votes. This code is proven to be immensely useful, reading and analyzing thousands of rows of data contained in a CSV file and saving countless hours of manual arithmetic and human error.

In addition, this code is flexible and can be applied to other scenarios and not just political elections. This code can read and analyze a multitue of scenarios such as:

  - Reading and determining the most popular company in a given area
  - Reading and determining the most popular athlete of a given sport
  - Reading and determining the most popular band of a given time period
  
Overall this code can read, organize, and breakdown a number of different voting scenarios and shouldn't be limited to just political elections.
