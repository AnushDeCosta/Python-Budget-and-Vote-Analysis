# python-challenge
# BootCamp - Module 3 Challenge

Student Name - Anush De Costa
Module 3 Challenge Name - PyBank and PyPoll Challenge

# Main Instructions to Follow:

In this project, I was given two data sets for analysis and printing out the outcome in the terminal as well as exporting a txt file.
Applying python concepts to run analysis of PyBank and PyPoll file. Both of these challenges encompass a real-world situation.

# PyBank:

In the first part of this week’s challenge, I have used a script for PyBank (main.py) that reads in a CSV file called budget_data.csv that contains financial data for a company, 
and uses this data to compute and print several summary statistics, such as the total number of months of data, the total amount of profit or loss, 
the average change in profit or loss over the entire time period, and the greatest increase and decrease in profit or loss. 
It also writes these summary statistics to a text file called Financial_Analysis.txt to match the following.

    Financial Analysis
    ----------------------------
    Total Months: 86
    Total: $22564198
    Average Change: $-8311.11
    Greatest Increase in Profits: Aug-16 ($1862002)
    Greatest Decrease in Profits: Feb-14 ($-1825558)

# PyPoll:

In the second part of the weeks challenge similar to the first I have used a script for PyPoll (main.py) for an election analysis. It reads in a CSV file containing the election results, 
and then processes that data to calculate the total number of votes, the names and number of votes for each candidate, and the percentage of votes each candidate received. 
The script then prints the results to the terminal and saves them to a text file. The winner of the election is determined by the candidate who received the most votes. The output was
scripted to match the following.

    Election Results
    -------------------------
    Total Votes: 369711
    -------------------------
    Charles Casper Stockham: 23.049% (85213)
    Diana DeGette: 73.812% (272892)
    Raymon Anthony Doane: 3.139% (11606)
    -------------------------
    Winner: Diana DeGette
    -------------------------

# Main Issues Faced

1.  One of the main challenges I faced was limiting the decimal count to 3 decimals in the PyPoll challenge... After many tests it was discovered that I was missing a simple " . " in my script. 

2.  Another big challenge was to match the PyPoll output in the same order of candidates. At first to resolve this issue I wrote the output script for each candidate, but this would have meant that if a 4th
    candidate was added to the CSV then the script would not run. Therefore, I settle to use the sorted function instead. This ensured the candidates would always be put in alphabetical order

Files Uploaded

1. PyBank Folder
    1.1 Resources Subfolder
        1.1.1 budget_data.csv
    1.2 analysis Subfolder
        1.1.2 Financial_Analysis.txt
    1.3 main.py
2. PyPoll Folder
    2.1 Resources Subfolder
        2.1.1 election_data.csv
    2.2 analysis Subfolder
        2.1.2 Election_Results.txt
    2.3 main.py