# An Analysis of Kickstarter Campaigns
Performing analysis to uncover trends in kickstarter data

# Identifying What Makes a Play Successful on Kickstarter

## Overview of the Project
- The purpose of this project was to identify factors that make campaigns --  specifically plays in the US -- successful on Kickstarter.  

## Analysis and Challenges
- To perform how the timing of a campaign determined its success, we used a simple Pivot Table to tabulate over 1,000 outcomes captured for theater data over the years. To determine how campaign goal affected success and fail rate, we counted the number of campaigns for each goal size using countif functions. We then did simple division to find the corresponding success/fail percentages for each outcome category.  

- During our goal analysis, we originally calculated the wrong values because we didn’t properly write the countif function. Instead of using just greater than or less than, we had to add the equals sign to also catch the campaigns that were equal or less than/greater than those values.  

## Results 
**Theater Outcomes by Launch Date**
- On average April to August have the highest number and percentage of successful theater campaigns.
-  Fail and cancel rates stay relatively consistent, whereas the number of successful campaigns usually peaks in May and steadily decreased throughout the rest of the year. 

**Outcomes based on Goals**
- Across all fundraising goals, the campaigns with budgets less than $5000 were the most successful and reached their goal 76% and 73%, respectively. 

**Limitations of the Data Set and Future Views** 
- The dataset did not contain sufficient information to identify all the factors that dictated whether or not a theater campaign was successful. For example, the median goal of *failed* plays was $5,000, which means that 50% of plays *still* failed despite being less than $5,000. This implies that other factors were at play. It would be useful to analyze trends among the successful campaigns such as commonalities within proposed story plot, subject, region/city, time length of play, etc. 

- Additionally, it would be useful to create more graphs related to how average donation and number of backers within the different outcomes. It could also be worth mapping how these trends over each year (instead of by month) for further insights. 
