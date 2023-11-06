# SQL_Challenge

# The Challenge
It’s been two weeks since you were hired as a new data engineer at Pewlett Hackard (a fictional company). Your first major task is to do a research project about
people whom the company employed during the 1980s and 1990s. All that remains of the employee database from that period are six CSV files.For this project, you’ll 
design the tables to hold the data from the CSV files, import the CSV files into a SQL database, and then answer questions about the data. That is, you’ll perform 
data modeling, data engineering, and data analysis, respectively.

# The Process
For this SQL challenge, I initially started creating tables manually within my PostgreSQL Database that I had made for this assignment. This was tedious and I kept 
receiving all kinds of errors, examples being: Syntax errors using any data type other than VARCHAR, Duplicate Primary key errors, issues using dates. I used multiple 
different methods to try and remedy these issues and was unsuccessful. I deleted my tables over and over again making minor adjustments each time and trying to import 
the csv using different tweaking even within a csv file at one point. I figured this must not be a necessary method and decided to start from scratch.
I then decided to use coding to help me create my tables and though it worked quite a bit of the time, it did not work 100% of the time. Importing the csv files still
weren't working and I was feeling lost. So, I asked Chatgpt for help, I used Stack Overflow, I watched YouTube videos, I googled a lot. Finally I came to the realization
that maybe my tables weren’t working because it was using the top row as part of the data and not the header. I then was enlightened and decided, why not use code to also
help me import these csv files? So that is exactly what I did. I had to change the settings for my csv files, so that PostgreSQL had permission to read each csv. Then I 
copied the pathways for each file and included it in my code. Once I did that my code was running seamlessly and I was able to produce all the results that are required 
for this challenge.

# What’s included?
Within this repo you will find my sketch of the Entity Relationship Diagram of the tables titled Data_Modeling_QuickDBD_Graph.png and the code I used for Quick DBD to 
create it titled: Data_Modeling_QuickDBD_Code.txt. You can find the code I used to create my different tables and import each csv file that correlates with these tables.
This is titled: Data_Engineering_Module_9_SQL.sql. Also included is the code I used to answer all the Data Analytics questions, this is titled: Data_Analysis_Module_9_SQL_.sql.

# Sources
For this challenge I utilized Youtube, Google, ChatGPT, fellow students, Stack Overflow, and Class recordings.
