# Election-Analysis

### Project Overview

##### The Colorado Board of Elections needs to certify a vote count for an election. An employee has been given the following tasks to complete the election audit of a recent local congressional election.

   - Calculate the total number of votes cast
   - For each county, calculate the number of votes they received and the their pecentage of the total number of votes.
   - Determine the county with the highest number of votes
   - For each candidate, calculate the numnber of votes they received and their percentage of the total number of votes
   - Determine the winner of the election based on popular vote


### Resources
#####     * Data Source: election_results.csv
#####     * Software: Python 3.8.3 and Visual Studio Code 1.49

### Election Audit Results

##### There were 369,711 total votes

##### There were 3 Counties, and the results are:
* Jefferson county has 10.5% with 38,855 votes
* Denver county has 82.8% with 306,055 votes
* Arapahoe county has 6.7% with 24,801 votes

The largest county turnout was Denver county

##### There were 3 candidates, and the results are:
* Charles Casper Stockham has 23.0% with 85,213 votes
* Diana DeGette has 73.8% with 272,892 votes
* Raymon Anthony Doane has 3.1% with 11,606 votes

##### The Winner of the election is:
Diane DeGette who received 73.8% with 272,892 votes

### Election Audit Summary
This script should be able to be easily reused for any election with minimal effort. One requirement is that the input file of the election results is in the same format, otherwise the script will need to be modified for the new format.

For each election, the variables "file_to_load" and "file_to_save" will need to be modified with the new path and names of the input and output files. Here is the section of the code that needs to be modified:
```
   # Add a variable to load a file from a path.
   file_to_load = os.path.join("/Election-Analysis/Resources","election_results.csv")

   # Add a variable to save the file to a path.
   file_to_save = os.path.join("/Election-Analysis/analysis", "election_results.txt")
```


