# Election_Analysis

## Overview of Election Audit Project

The project aims at automating the counting of Election Results and arrive at the following metrics of the election conducted by the Colorado Board of Elections.
* total count of votes casted
* complete list of candidates who received votes
* total count of votes each candidate received
* percentage of votes for each candidate 
* winner of the election based on popular vote
* percentage of votes from each county
* voter turnout for each county
* county with the highest turnout

## Dataset
The analysis was performed on the following dataset
Data Source: [election_results.csv](https://github.com/gopivasanth/Election_Analysis/blob/e7dc84908fb2d2e15ec2209bd34c4bbb30203f4a/Resources/election_results.csv). The dataset had the voting information for 3 counties based on which the script was developed.

## Election Audit Results
There were a total of ****369,711**** votes casted in the Colorado Board of Elections. 

The following are the list of candidates :
1. Charles Casper Stockham
2. Diana DeGette
3. Raymon Anthony Doane

who contested in the election in the below counties
1. Jefferson
2.  Denver
3.  Arapahoe

The following is the summary of the election results across the following parameters

![Election Results](https://github.com/gopivasanth/Election_Analysis/blob/e7dc84908fb2d2e15ec2209bd34c4bbb30203f4a/Resources/election_results.png)

## ****Election-Audit Summary****

![PyPoll_Challenge.py](https://github.com/gopivasanth/Election_Analysis/blob/e7dc84908fb2d2e15ec2209bd34c4bbb30203f4a/PyPoll_Challenge.py) script has been developed to automate the counting of elections results for selected counties within Colorado where the results are published in the format as mentioned in the section Dataset. 

This is a powerful script that is scalable and can be used to automate other election audits at provincial and federal levels. 