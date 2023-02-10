# Data Scientist Coding Challenge
This page contains a coding challenge for Data Scientist roles at Circle K.

# Purpose
The goals of this test are threefold:
- evaluate your coding abilities
- judge your technical experience
- understand how you design a solution

# How you will be judged
You will be scored on:
1. coding standards, comments, and readability of your code
2. how you approached the problems
3. overall solution design (i.e. if the problem is solved)
4. appropriate use of source control

# Instructions
- You are writing code that only other data scientists will see. No UI is required, but all your work and results must be viewable.
- You may use any Open Source solution for storing work and results, but a Jupyter Notebook or Jupyter Lab are particularly suited for these tasks. Jupyter Notebook comes with the Anaconda installation of Python. There are also other online versions where you can work (see: https://www.tutorialspoint.com/jupyter/jupyterlab_installation_and_getting_started.htm#:~:text=Visit%20https%3A%2F%2Fjupyter.org,and%20tabs%20and%20settings%20view.) Pick one.
- Once the test is completed, please email **a single PDF version** of the .ipynb file to Rich Lucas (rich.lucas@circlek.com) so he can review your work. Alternatively, the candidate may upload their final Jupyter Notebook into a code repository hosted on Github (it can be public or private). Please include details on how to access the repo so we can see your work.


# Challenge #1 – User Accounts and Viewing History

Data
Table 1: table_video_viewing.csv
Table 2: table_account_info.csv


### Create solutions using SQL, Python, or R that answer the following regarding Tables 1 and 2:
- Q1a: Write a query that will return the first title watched for each user.
- Q1b: Write a query that will give me total viewing time in minutes of each title in September 2021.
- Q1c: Write a query that will give me the share of minutes (as a percentage) Ruthless was viewed in September 2021.
- Q1d: Write a query that will give me the share of minutes viewed (as a percentage) with a premium account.


# Challenge #2 - Manipulating Strings with Python

### Create solutions using Python that answer the following:
- Q2a: Given the input s1 = "bbabcabcbb", find the length of the longest repeating substring. ('abc' and 'bb' are the two substrings.)
- Q2b: Write a function that will find the length of the longest repeating substring for:
- i. s1 = "bbabcabcbb" 
- ii. s2 = "bbbbb"
- iii. s3 = "pwwkew"


# Challenge #3 - Machine Learning

Background
- A company has a fleet of devices transmitting daily telemetry readings. They would like to create a predictive
maintenance solution to proactively identify when maintenance should be performed. This approach promises cost
savings over routine or time-based preventive maintenance, because tasks are performed only when warranted.

The Task
- You are tasked with building a predictive model using machine learning to predict the probability of a device failure. You may use Python or R.
When building this model, be sure to minimize false positives and false negatives. The column you are trying to
predict is called 'failure' in Table 3. The 'failure' column has a binary set of values, 0 for non-failure, and 1 for failure. You are allowed to apply any relevant machine learning methods. Build a model to predict 'failure'. Show your work and support your decisions/conclusions.  

Data
- Table 3: predictive_maintenance.csv


# Bonus point
- Demonstrating deep learning implementations for Challenge 3.
