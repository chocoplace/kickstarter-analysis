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
![Theater_Outcomes_vs_Launch](https://github.com/chocoplace/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

From the information presented on the Pivot Table: Theater Outcomes by Launch Date we can highlight the following: 
1. From the Parent Categories, “Theater” is the one with the highest number of events conducted over the period reported in the dataset. This can support future campaigns aimed to identify the interest by category.
2. “Theater” has 1369 campaigns. According to Launch date vs funding goals, 839 had successful results, 493 failed, and 37 were canceled. 
3. The best months to successfully promote a Theater campaign are: May (111), June (100) and July (87). 
4. The failed campaigns follows the trend year along, however the ratio between failedVSsuccesful is bigger on October. The recommendation could be to reschedule the events of October for another time. 

### Analysis of Outcomes Based on Goals

*Technical background: For the analysis of outcomes based on Goals, the first step was to create a new sheet under the name Outcomes Based wirth 8 columns and 12 rows, aimed to populate the number of Successful, Failed and Canceled campaigns and grouped under a series of goal amount. The second step was to work on the formulas to populate each column and row as follow:
 ![Outomes_based_on_Goals_Sheet](https://github.com/chocoplace/kickstarter-analysis/blob/main/Resources/Outomes_based_on_Goals_Sheet.png)

As the third step, I created a linear chart to have a visual of the Outcomes Based on Goal. 

*Analysis: 
![Outcomes_vs_Goals](https://github.com/chocoplace/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)

From the information presented on the chart, we can highlight:
1. From the 12 groups the client requested to group the campaigns, the highest number of campaigns are under $1,000-$4,999. 
2. The highest number of Successful and Failed campaigns are placed under the range $1,000-$4,999 goal amount. 
3. The three popular groups are under $10,000 this might reflect the capacity of the backers of the campings.  
4. There are 14 failed campaigns with a goal Greater than $50,000 and only 2 successful campaigns. If interested, we can further the analysis on what did work and what is not working on these campaigns. 

### Challenges and Difficulties Encountered

Among the challenges and difficulties I encountered while performing the analysis, one was during the Analysis of Outcomes Based on Launch Date, the results I got on and the ones reflected on Canvas are slightly different. 

![Example_of_Challenge](https://github.com/chocoplace/kickstarter-analysis/blob/main/Resources/Example_of_Challenge.png)

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

1. From the Parent Categories, “Theater” is the one with the highest number of events conducted over the period reported in the dataset. This can support future campaigns aimed to identify the interest by category.
2. “Theater” has 1369 campaigns. According to Launch date vs funding goals, 839 had successful results, 493 failed, and 37 were canceled. 
3. The best months to successfully promote a Theater campaign are: May (111), June (100) and July (87). 
4. The failed campaigns follows the trend year along, however the ratio between failedVSsuccesful is bigger on October. The recommendation could be to reschedule the events of October for another time.

- What can you conclude about the Outcomes based on Goals?

1. From the 12 groups the client requested to group the campaigns, the highest number of campaigns are under $1,000-$4,999. 
2. The highest number of Successful and Failed campaigns are placed under the range $1,000-$4,999 goal amount. 
3. The three popular groups are under $10,000 this might reflect the capacity of the backers of the campings.  
4. There are 14 failed campaigns with a goal Greater than $50,000 and only 2 successful campaigns. If interested, we can further the analysis on what did work and what is not working on these campaigns

- What are some limitations of this dataset?

Among the limitations of this dataset we can highlight:
1. There is no background on how our client sets the time frame to start and close a campaign limiting the understanding and the analysis of Launch date vs Outcomes.  
2. There is no background on what determines the Outcomes results, we part from successful, failed and canceled but we don't know for sure on what is based. 
3. Overall we are missing vital information to perform a detailed analysis requested by the client. Client wanted to know how different “Plays” campaigns fared in relation to their launch dates and their funding goals.

- What are some other possible tables and/or graphs that we could create?

My suggestion to have a better analys on the performance of a campaign is to add the Days where the campaign was active to add a table with Outcomes, Percentage funded, Average of Days.  

End
