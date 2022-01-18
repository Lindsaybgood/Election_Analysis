# Overview of Election Audit
Tom, a Colorado Board of Elections employee, needs assitance with the following tasks to complete the election audit of a recent local congressional election.
1.	Calculate the total number of votes cast.
2.	Get a complete list of counties that had a turnout.
3.	Calculate the voter turnout for each county.
4.	Calculate the percentage of votes each county cast.
5.	Determine the county with the highest turnout.
6.	Get a complete list of candidates who recieved votes.
7.	Calculate the total number of votes each candidate recieved.
8.	Calculate the percentage of votes each candidate won.
9.	Determine the winner of the election based on popular vote.
Tom's manager wants to automate the process of generating a vote count report using Python.
## Election-Audit Results
The analysis of the election shows that:
*	There were 369,711 total votes cast in this congressional election.
*	The county results for the precinct:
    *	Jefferson cast 10.5% of the vote and 38,855 votes.
    *	Denver cast 82.8% of the vote and 306,055 votes.
    *	Arapahoe cast 6.7% of the vote and 24,801.
*	Denver county had the largest number of votes.
*	The candidate results were:
    *	Charles Casper Stockham recieved 23.0% of the vote and 85,213 votes.
    *	Diana DeGette recieved 73.8% of the vote and 272,892 votes.
    *	Raymon Anthony Doane recieved 3.1% of the vote and 11,606 votes.
*	The winner of the election was Diana DeGette, who recieved 73.8% of the vote and 272,892 votes.
See the output of the code below:

 ![Election Results](https://user-images.githubusercontent.com/96216509/149854966-7007627f-7995-4710-a63f-20a6a4290728.png)
## Election-Audit Summary
I think, with some alterations, the PyPoll_Challenge.py script can be used for other elections. With some modifications the code can be used for any election results.
For example, the program can be modified to determine what percentage of each county voted for each candidate by adding an if-statement to the code. The programmer will also no longer have to inspect the data in order to ensure that script is reading the correct columns. 
## Resources
•	Data Source: election_results.csv
•	Software: Python 3.9.7, Visual Studio Code, 1.63.2
