# An Analysis of Kickstarter Campaigns
Performing analysis on kickstarter data to uncover trends
# Kickstarting with Excel

## Overview of Project
The aim of this project is to analyze Kickstarter data from past campaings to uncover trends across various attributes leading to better understanding and an ability to potentially predict successful outcomes in future.  Specifically for this research we will look for co-relations between Launch Date for theatre campaigns and their outcomes.  We will further look at the subgroup Plays to understand the co-relation between Goal and success of the campaign

### Purpose
The purpose of this analysis is to look for trends and co-relations in the data for past campaigns that could provide a blueprint future Kickstarter campaigns could use to further their success.  

## Analysis and Challenges


### Challenges and Difficulties Encountered

- What are some limitations of this dataset?
    LIVE status campaigns were removed as incomplete data could impact results.  The analysis failed to look at campaign duration and this could have a significant impact on outcome.  This analysis also only takes into account month and outcome though theoretically the success of campaigns in May could be coincidence, attributable to some other factor as we have not looked at this from all angles  We filtered only on parent category “theater”, not sub-category “plays” so the data we are comparing is not like for like.  The theater data includes musicals etc.  Seasonality (launch date success) may also vary by country so we should look at that in future.

    Further analysis could include looking at average donation and backers count to see if there are any factors (such as seasonality that impact these).  If building a strategy to improve likelihood of successful outcome these are the two key levers that would impact outcome.  I’d want to analyze data to show how we might improve both and understand which of these plays more of a factor in failed campaigns (if not both combined).  If we truly wanted to understand seasonality we should likely look at each month in each year in isolation rather than in total for the month across all years in order to properly trend.  Incorporating stat/ significance testing could also help us to ensure our findings are meaningful.
  
- What are some other possible tables and/or graphs that we could create?
    Again we looked at inconsistent data sources:  Theaters v. Theaters/ Plays so I would not draw any conclusions between the 2 charts in the exercise as we are not comparing like for like.  In the notes it says we are looking at the relationship between the goal amount and the campaign’s chances of success or failure.  I don’t believe we have enough data points to use this as a basis for predicting outcomes based on goal.  We are looking at 2 variables but I’d want to look across the rest of the data set for deeper understanding of the relationship.  Further, it would be interesting to look at how goal impacts average donation and backers count.  We should definitely strive for ore indepth country/ subcategory analysis. As we did not apply stat/ significance testing we don’t know if the findings are meaningful - we should include this in future analysis.  Finally, campaign duration V Goal would have been key to understanding the relationship here (i.e. high goal, long duration could be successful and high goal, short duration could be unsuccessful).


## Results

### Analysis of Outcomes Based on Launch Date
- What are two conclusions you can draw about the Outcomes based on Launch Date?
 Theater campaigns launched in May resulted in more successful outcomes than any other month. Theater campaigns launched in December resulted in the fewest successful outcomes and there were nearly an equal number of failures as successess for campaigns launched in this month.

### Analysis of Outcomes Based on Goals

- What can you conclude about the Outcomes based on Goals?
  As would be expected, on the graph we see clearly that when success is at its highest % failure is at its lowest at each goal level.  Play campaigns with a goal of $45,000 to $49,999 had a 100% failure rate and a 0% success rate. No Play campaigns were canceled. Among campaigns with goals of $15,000-$19,999, 50% were successful and 50% failed.
