# An Analysis of Kickstarter Campaigns

## Overview of Project

The main objective of “An Analysis of Kickstarter Campaigns” is to carry out a comparative analysis to help our client identify performance trends based on launch dates and funding goals of the targeted Kickstarter campaigns for Plays. 

### Purpose

Utilizing MS Excel program, perform and report data analysis on Kickstarter Campaigns using Pivot Tables, Pivot Charts, Conditional Formatting, among other technical techniques learned on Module 1.

## Analysis and Challenges

The analysis started with getting to know the dataset for my project [#Kickstarter_Challenge](https://github.com/chocoplace/kickstarter-analysis/blob/main/Kickstarter_Challenge.zip) and understanding the background of my analysis, the client wanted to know how different “Plays” campaigns fared in relation to their launch dates and their funding goals.

### Analysis of Outcomes Based on Launch Date

*Technical background: For the analysis of outcomes based on Launch Date, the first step was to create a new column (Year) on the main dataset to be able to filter the information by Launch Date (Date Created Conversation) on a Pivot Table. The second step was to create a Pivot Table under the name Theater Outcomes by Launch Date to better visualize the information of Launch Date, Outcomes by Successful, Failed, Canceled, and Parent Category. The table is filtered by the Parent Category “Theater” because it is the point of interest of our client. As the third step, I created a linear PivotChart to have a visual of the Theater campaigns per outcome and month. 

*Analysis: 
![Theater_Outcomes_vs_Launch](https://github.com/chocoplace/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.pn)

From the information presented on the Pivot Table: Theater Outcomes by Launch Date we can highlight the following: 
From the Parent Categories, “Theater” is the one with the highest number of events conducted over the period reported in the dataset. This can support future campaigns aimed to identify the interest by category.
“Theater” has 1369 campaigns. According to Launch date vs funding goals, 839 had successful results, 493 failed, and 37 were canceled. 
The best months to successfully promote a Theater campaign are: May (111), June (100) and July (87). 
The failed campaigns follows the trend year along, however the ratio between failedVSsuccesful is bigger on October. The recommendation could be to reschedule the events of October for another time. 

