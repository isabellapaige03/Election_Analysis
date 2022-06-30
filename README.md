# Election_Analysis

## Overview of Project
Originally this project was to create a vote count report based on the election ballots for a Colorado election commisssion. Instead of using excel, the manager wanted to know if we could use python to automate the process. After completing this report, the election commission asked for new data to finish the audit. In this analysis you will find the total number of votes cast, the county with the largest turnout and the winning candidate along with their total vote count and their precntage of the total votes.


## Results
• The total number of votes for this election is 369,711.  To get the total number of votes counted I initialized a total vote counter. 

![This is an image]()<img width="211" alt="Total vote counter" src="https://user-images.githubusercontent.com/106712521/176578790-6d845ff6-8805-4cf3-854c-515e4acffa58.png">

• There were three different counties in the election, Arapahoe, Denver and Jefferson. Here is a list of the total percentage of votes each county received along with the total number of votes.

    o	Denver: 82.8%   Total Votes = 306,055
    o	Arapahoe: 6.7% Total Votes = 24,801
    o	Jefferson:10.5% Total Votes = 38,855
              
 We used the following code to calculate the percentages for each county.
	
	
![This is an image]()<img width="347" alt="percentage of votes" src="https://user-images.githubusercontent.com/106712521/176578976-ce319967-4d37-4065-924a-0179da889dfb.png">


• The county with the largest number of votes was Denver with 306,055 votes. To find the county with the largest turnout I started by tracking largest county and county voter turnout. 



![This is an image]()<img width="296" alt="Intialized turnout " src="https://user-images.githubusercontent.com/106712521/176578240-112d8641-8b34-46dd-b846-61bc9849ab0d.png">


Then I wrote a decision statement that would add the county with the largest vote count to the two variables I created above. 

![This is an image]()<img width="424" alt="IF Statement" src="https://user-images.githubusercontent.com/106712521/176576404-d0eaea6a-fea6-4e2c-8dfb-5b10720c5125.png">

• Here is a list of candidates with their percentage of the total votes they received and the total amount of votes they received.
	o Charles Casper Stockham: 23.0%   Total Votes = 85,213
	o Diana DeGette: 73.8%   Total Votes = 272,892
	o Raymon Anthony Doane: 3.1%   Total Votes = 24,801


To find the percentage of the total votes for each candidate I used the code below.


![This is an image]"()<img width="344" alt="candidate vote precentage" src="https://user-images.githubusercontent.com/106712521/176583689-0e549807-595f-4754-8a67-544031e711af.png">

• The winner of this Congressional election is Diana DeGette with a total of 272,892 votes and 73.8% of the total votes. 


![This is an image]()<img width="160" alt="Winner" src="https://user-images.githubusercontent.com/106712521/176583879-52a59004-ad38-41e8-8038-cc943abf8f71.png">


To determine the winner and the get the voting percentages I used the following code.

![This is an image]()<img width="394" alt="Winning vote " src="https://user-images.githubusercontent.com/106712521/176584028-beb6d260-9758-4e11-b3e9-d2829bea255c.png">

## Summary 
  This script can be modified to audit all elections the commission has. One way you can customize this script for a new election is to change the source of your data. 


![This is an image]()<img width="553" alt="file to load" src="https://user-images.githubusercontent.com/106712521/176586510-0e04c9b7-68a8-4993-aed0-f72505cb05f0.png">

You can change the data easily by replacing (“Resources”, “election_results.csv”) with a different file path. 

If the data was provided, we could modify this script to add the population size of each county to further our analysis.

