# Challenge1
Kickstarter Analysis

# Kickstarting with Excel

## Overview of Project

### Purpose
In this project, I analyzed kickstarter campaign data to study different elements of campaigns. The purpose of this analysis was to learn how launch date and financial goals impacted the success of fundraiser campaigns. My client, Louise, was particularly interested in the theater/plays category/subcategory. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
I started the analysis by reviewing the relationship between theater campaign outcomes and the month in which they launched. I started by adding column to the table and using the YEARS() function to return the year of the campaign based on the mm/dd/yyyy structure. Next, I created a pivot table to organize the campaign outcomes by month and added a filter so my client could look specifically at Theater campaigns. Finally, I created a graph for a more visually appeal view of the data.

![Theater Campaign Outcomes Based on Launch Date](/Resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
For the second part of my analysis I looked at the number of outcomes (successful, failed, canceled) based on the financial goal of the campaign. I created a table with incremental goal values. Then I wrote counifs functions to narrow down the data to only plays and then count the results based on outcomes within each financial braket. Finally, I created a graph to easily look at the trends across different goal brackets. 

![Play Campaign Outcomes Based on Financial Goal](/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
For the Analysis of Outcomes Based on Launch Date, I only ran into a minor issue. I forgot to sort the outcome columns in reverse alphabetical order within the pivot table. Upon reviewing my work, I noticed the example grid in the module was reverse alphabetical so I was able to change my pivot to match. 

For the Analysis of Outcomes based on goals, I struggled to get my graph to match the one within the challenge module. I checked my countifs multiple times and even reviewed them randomly throughout two days to see if I could find the issue. Ultimately, I totalled up each column within my table, compared it to the count of items on the main kickstarter tab and I was missing roughly 300 items! I finally realized that I was > and < indicators when I should have been using >= and <=. It was such an easy fix but it took me forever to find!

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?