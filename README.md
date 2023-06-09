# Python Data Analysis

By creating a script in Python, I have created a powerful option for handling big data. The datasets for the projects are intentionally large to showcase one of the limits of Excel-based analysis. Each project below has its own script for the analysis. The script can be found in the Project's folder. Within each projects folder is a copy of the original data, in the sub-folder **Resources**. An export of each analysis is available in a textfile in the sub-folder **Analysis**. Websites used to inform my script for each project can be found in the folder **Support Documents**.

Each project successfully reads a csv file, analyzes the data, and displays the results in the terminal and a textfile. Other features in the projects include for loops, defining functions, lists, dictionaries, if statements, addition assignment, and basic arithmetic.

## PyBank

A financial records company needs help analyzing their budget. I was given the file, 'budget_data.csv', to analyze. The dataset contains two columns, 'Date' and 'Profit/Losses'. The goal of the project was to analyze the monthly data provided and calculate the following values:

* The total number of months included in the dataset
* The net total amount of 'Profit/Losses' over the entire period
* The changes in the 'Profit/Losses' over the entire period, and then the average of those changes
* The greatest increase in profits (date and amount) over the entire period
* The greatest decrease in profits (date and amount) over the entire period

The analyses in this script can be updated when additional months are added into the dataset by re-running the script. Below is a capture of the output:

![PyBank Results](https://github.com/sarsteg/python_challenge3/blob/d1e12e61ba80f76e281625d2b0a55632963ffd88/PyBank/Analysis/PyBank%20Results.png)

## PyPoll

A small-town needs help modernizing its vote-counting process. I was given a set of poll data ('election_data.csv') that had the following three columns: 'Voter ID', 'County', and 'Candidate'. The goal of the project was to create a Python script that would analyze the votes and calculate the following values:

* The total number of votes cast
* A complete list of candidates who received votes
* The percentage of votes each candidate won
* The total number of votes each candidate won
* The winner of the election based on popular vote

Some key features of this script are that it is built so that it could accommodate future polls with a change of the dataset. The names of the candidates are taken from the data and stored in a list. The votes cast for each candidate are stored in a dictionary.

The code could be further improved to allow the user to select the data file that they are interested in collecting the results of poll data using a library such as tkinter. In tkinter, a pop-up window could be created that allows the user to select the file of interest and then provides the path to the file for use in the rest of the script.

These two projects were completed as a part of UTSA's Data Analysis and Visualization Certification.

Below is a capture of the output:

![PyPoll Results](https://github.com/sarsteg/python_challenge3/blob/d1e12e61ba80f76e281625d2b0a55632963ffd88/PyPoll/Analysis/PyPoll%20Results.png)
