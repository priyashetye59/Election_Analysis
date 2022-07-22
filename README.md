# Election_Analysis
Perform analysis of Election data to declare winner of election
# Election Audit
## Overview of Election Audit
In this section, you will find the background and purpose of the project.
### Background of Project
Election commission has to perform election audit by taking into consideration of Ballot Id, county and candidate data to figure out the winning candidate and winning county. For this, Tom and Seth are helping on the election analysis project to perform necessary coding in python.
### Purpose of Election Audit
Purpose of the election analysis project is to find out winning candidate and country from large voting data set to assist election commission to declare necessary results. 
## Election-Audit Results
In this section, we will do inspection of election audit results by examining the codes and output that Tom & Seth's team has performed in python terminal.
- How many votes were cast in this congressional election? 
![Total votes of Election audit](Total votes of Election audit.png) 
As per above screenshot of election_analysis.txt, total votes of all county and for all candidates are 369,711. This are identified by first initializing total_votes and then performing code i.e. total_votes = total_votes + 1
- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
**County Votes:
Jefferson: 10.5% (38,855)
Denver: 82.8% (306,055)
Arapahoe: 6.7% (24,801)**
Above text from election_analysis.txt file is for reference to give breakdown of country votes and percentage of votes. Denver country has gained 306,055 votes for it's candidates which is 82.8% of total votes. Jefferson and Arapahoe has 10.5% and 6.7% of total votes for it's candidate respectively.
- Which county had the largest number of votes?
![Winning county with votes](Winning county and votes.png)
Denver county has largest number of votes i.e. 306,055 out of 369,711 which is 82.8% for all candidates in that county.
- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
Out of total votes of all candidates within three county, Raymon Anthony Doane received 11,606 which is lowest and on the other hand, Diana DeGette noted with highest votes 73.8% of total votes of 369,711. Charles Casper Stockham has less than 25% of total votes i.e. 85,213 of total votes.
- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
![Winning Candidate summary](Winning county and votes.png)
From screenshot of code run in PyPoll_Challenge.py file, Tom and Seth has identified winner of election commission in Denver, Jefferson and Arapahoe county is Diana DeGette with winning vote count of 272,892 and with winning percentage of 73.8%.
## Election-Audit Summary
Initializing the list and dictionary and creating a loop for votes, counts along with conditional for used for fining winner, these codes can be used by election commission to run election audit for any other country. Also script to save output to txt file can get modified with some more editors to present it more professionally in txt file.
