# Kickstarting with Excel

## Overview of Project

This project focuses on generating insights and visualizing theatre kickstarter campaigns data based on Launch Date and Campaign Goals for all types..  To acheive this goal it was important utilize formulas, filters, pivot tables as well as charts within excel.  When done well the ultimate outcome is to enable better decision making and/or provide more insights for further analysis.

### Purpose

This analysis will provide insights on how launch dates for Theatre campaigns and funding goals for all types of campaigns impacted kickstarter outcomes of success, failure, or cancellations of those campaigns.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

#### Trends
Starting in March the number of theatre compaigns being launched begins to increase, peaking in May and then trending down for the rest of the year.  The measure of successful and failed campaigns moves in tandem as shown in the graph.  We can see that as there are more successful campaigns there is also and increase in failed campaigns.  The number of cancelled campaigns is consistently flat and does not appear to be impacted by launch date.

#### Best & Worst Months for Launching a Theatre Campaign
In the graph we see the narrowest gap between successful and failed campaigns is in the month of December suggesting this would be the worst month to launch a campaign.  The widest gap between the two is in the months of May and June suggesting this is the best time to launch a campaign.  The number of cancelled campaigns is rather insignificant overall.

![Theater Outcomes vs Launch Data](/Theater_Outcomes_vs_Launch.png)


### Analysis of Outcomes Based on Goals

#### Trends
There does not appear to be any consistent trend between success or failure as the goal amounts increaase.  The jagged lines implies there is more at play than just the goal amount driving results.

#### Best & Worst Goal Ranges
Based on this data it would appear that the best goal amount is $1000 or lower and $35000-39999.  The worst goal amounts are $45000 to $49999 and $25000 to $29999.

![Outcomes Based on Goals](/Outcomes_vs_Goals.png)


### Challenges and Difficulties Encountered

countif issues -  copy to adjoining cells error due to not setting the absolute reference

Basic writing syntax errors


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

  - Based on the data even though there would be a high number of campaigns running in the months of May and June resulting in lots of competition these are still the best months to launch a theatre campaign.  The worst months for launching a kickstarter are November, December and January.

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?
  - There is no data to measure the effectiveness of the pitch
  - There is no data about methods used to market the campaign to find backers.  Such has social media ads or other marketing efforts
  - There is no demographic data about backers for historical campaigns to leverage for the purposes of pitch and marketing plan development

- What are some other possible tables and/or graphs that we could create?
  - perform a goals analysis on just Theatre kickstarters not just all to detemrine if Theatre specific outcomes are similar or dissimilar to all campaigns
  - Perform a goals analysis on Theatre kickstarts & Goals by country and by year
  - identify any outlier data and make decisions about the inclusion of this data
  -  Calculate summary statistics such as measures of central tendency, standard deviation, and variance for the subset of data we are analyzing, namely theatre campaigns
  - for the outcomes by launch date it would be effective to show the outcomes as a percentage by month.  when you do this you find that aside from December for all other months the success rate is between 56-66% a range of 10 percent. when you look at the chart without percentages the success numbers  in the month of May, June & July appear to be really high however when viewed as a percentage it is not as large there was simply a higher volume of campaigns in these months 40-50% more than the other months so it has the effect of appearing oversized.  The following side by side view of this demonstrates how the view as a number of campaigns is potentially misleading or rather it understates the equally as good performance in the other months.

![Launch by number vs percentage](/Launch_outcomes_launch_date_vs_percentage.png)
