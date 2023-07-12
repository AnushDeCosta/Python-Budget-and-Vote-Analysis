# PythonDataAnalysis

![Main Iamge](./Images/Votes.jpg)

## Summary
The PythonDataAnalysis project focuses on performing data analysis tasks using Python. The project is divided into three main segments: Data Analysis and Text File Creation, PyBank Analysis, and PyPoll Analysis. Each segment involves different analysis tasks and utilizes Python to process the data and generate results.

## Introduction
This exercise unfolds in three main segments:
- Data Analysis and Text File Creation
- PyBank Analysis
- PyPoll Analysis

## Data Analysis and Text File Creation
The initial phase of the exercise entailed analyzing two provided data sets. These data sets were processed using Python to print results in the terminal and concurrently export the results to a text file. This segment of the task is representative of scenarios encountered in the real world.



## PyBank Analysis
The first segment of the exercise involved scripting a Python program named main.py for PyBank. This script reads the budget_data.csv file, which contains a company's financial data. It processes the data to compute and print several summary statistics, including the total months of data, the overall profit or loss, the average change in profit or loss over time, and the greatest increases and decreases in profit or loss. The summary statistics were also written to a text file named Financial_Analysis.txt. The final outcome mirrored the following format:

    Financial Analysis
    ----------------------------
    Total Months: 86
    Total: $22564198
    Average Change: $-8311.11
    Greatest Increase in Profits: Aug-16 ($1862002)
    Greatest Decrease in Profits: Feb-14 ($-1825558)

## PyPoll Analysis
Similar to the first segment, the second segment of the exercise involved scripting a Python program named main.py for PyPoll, aimed at election analysis. The script reads the election_data.csv file, containing election results, and processes the data to calculate the total votes, the names and vote count for each candidate, and the percentage of votes each candidate received. The results were printed in the terminal and also saved to a text file. The candidate with the most votes was declared the winner. The final outcome was crafted to resemble the following:

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

## Conclusion
Despite the challenges encountered during the exercise, it served as a practical exploration of Python for data analysis, underlining its capabilities in processing and interpreting complex datasets.

## Tools
- VS Code
- Python
- Excel
- Terminal

## Files 
- PyBank
    - [PyBank Script](./PyBank/main.py)
    - [Financial Analysis](./PyBank/analysis/Financial_Analysis.txt)
    - [Budget Data](./PyBank/Resources/budget_data.csv)
    
- PyPoll
    - [PyPoll Script](./PyPoll/main.py)  
    - [Election Results](./PyPoll/analysis/Election_Results.txt)
    - [Election Data](./PyPoll/Resources/election_data.csv)





