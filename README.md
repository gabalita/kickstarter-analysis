# Identifying What Makes a Play Successful on Kickstarter

## Overview of the Project
- The purpose of this project was to identify factors that make campaigns --  specifically plays in the United States -- successful on Kickstarter.  

## Analysis and Challenges
- To perform how the timing of a campaign determined its success, we used a simple Pivot Table to tabulate over 1,000 outcomes captured for theater data over the years. To determine how campaign goal affected success and fail rate, we counted the number of campaigns for each goal size using countif functions. We then did simple division to find the corresponding success/fail percentages for each outcome category.  

- During our goal analysis, our calculations were intially off because we didn’t write the countif functions correctly. At the beginning we used simple greater than or less than inequalities. By adding the equals sign (changing it to greater/less than or _equal_ to), we were able to capture all the data. 

## Results 
**Theater Outcomes by Launch Date**
- On average April to August have the highest number and percentage of successful theater campaigns.
-  Fail and cancel rates stay relatively consistent, whereas the number of successful campaigns usually peaks in May and steadily decreased throughout the rest of the year. 

**Outcomes based on Goals**
- Across all fundraising goals, the campaigns with budgets less than $5000 were the most successful and reached their goal 76% and 73%, respectively. 

**Limitations of the Data Set and Future Views** 

**Limitations**
- The dataset did not contain sufficient information to identify all the factors that dictated whether or not a theater campaign was successful. For example, the median goal of *failed* plays was $5,000, which means that 50% of plays *still* failed despite being less than $5,000. This implies that other factors were at play. It would be useful to analyze trends among the successful campaigns such as commonalities within proposed story plot, subject, region/city, time length of play, etc. 

- Another limitation was that these numbers included several outliers, which skewed the data.  

**Future Views**
- Additionally, it would be useful to create more graphs related to how average donation and number of backers within the different outcomes. 
- It could also be worth mapping how these trends over each year (instead of by month) for further insights. 
