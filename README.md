# Election-Analysis

### Project Overview

##### A Colorado Board of Elections needs to certify the vote count. An employee has been given the following tasks to complete the election audit of a recent local congressional election.

    * Calculate the total number of votes cast
    * For each county, calculate the number of votes they received and the their pecentage of the total number of votes.
    * Determine the county with the highest number of votes
    * For each candidate, calculate the numnber of votes they received and their percentage of the total number of votes
    * Determine the winner of the election based on popular vote


### Resources
#####     * Data Source: election_results.csv
#####     * Software: Python 3.8.3 and Visual Studio Code 1.49

### Election Audit Results

##### There were 369,711 total votes

##### There were 3 Counties, and the results are:
* Jefferson county had 10.5% of the votes and 38,855 number of votes
* Denver county had 82.8% of the votes and 306,055 number of votes
* Arapahoe county had 6.7% of the votes and 24,801 number of votes

The largest county turnout was Denver county

##### There were 3 candidates, and the results are:
* Charles Casper Stockham received 23.0% of the votes and 84,213 number of votes
* Diana DeGette received 73.8% of the votes and 272,892 number of votes
* Raymon Anthony Doane received 3.1% of the votes and 11,606 number of votes

##### The Winner of the election was:
Diane DeGette who received 73.8% of the votes and 272,892 number of votes

### Election Audit Summary
This script should be able to be easily reused for any election with minimal effort. One requirement is that the input file of the election results is in the same format, otherwise the script will need to be modified for the new format.

For each election, the variables "file_to_load" and "file_to_save" will need to be modified with the new path and names of the input and output files. Here is an example of the section of the code that needs to be modified:
```
   # Add a variable to load a file from a path.
   file_to_load = os.path.join("/Election-Analysis/Resources/","election_results.csv")

   # Add a variable to save the file to a path.
   file_to_save = os.path.join("/Election-Analysis/analysis", "election_results.txt")
```


