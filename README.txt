# Kickstarter-analysis

## Overview of Project

### Purpose

Help Louise understand how the different campaigns did against hers.  Since hers failed, understanding when, how and why campaigns are successful will help her understand why hers failed.
I will be using excel to create new data and graphs that help explain the outcomes.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
I used a pivot table to show the breakdown of theater campaign outcomes (minus live) by month.  
I also created a line chart that shows, by each given month, what outcome was most frequent. 

### Analysis of Outcomes Based on Goals
Using the =countifs function, I filled out a chart that calculates the outcomes of campaigns based upon the dollar goal amount.
This chart also showed the percentage of successful, failed and canceled based upon a range of goal amounts.  I then created a line charts that shows which dollar ranges were most successful.


### Challenges and Difficulties Encountered
Upon some data validation checks with the =countifs function, I noticed the total number of campaigns (successful and failed) was higher in my chart than in the data.  
I used filters to add up the correct numbers in the Kickstarter sheet but still never figured out why the numbers did not add up.


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
In total, there were very few canceled campaigns in the cateogry of theater.  The most successful campaigns started in May and June with the totals being noticeably higher.

- What can you conclude about the Outcomes based on Goals?
The most successful campaigns were ones whose goal was under 20k. There were a couple that did well in the higher dollar amount but the bulk of all campaigns stayed under 20k.
There were zero canceled campaigns in the plays subcategory.  


- What are some limitations of this dataset?
This just measured the data involved with the category Theater and subcategory plays. The outcomes would maybe be different if we looked into different categories.  
- What are some other possible tables and/or graphs that we could create?
I could have used a pie chart to show the percentage of outcomes.  