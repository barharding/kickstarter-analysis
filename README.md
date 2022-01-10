# Kickstarting with Excel

## Overview of Project

This project focuses on generating insights and visualizing theatre kickstarter campaign data based on Launch Date and Campaign Goals.  To acheive this goal it was important to utilize formulas, filters, pivot tables as well as charts within excel.  The ultimate outcome is to enable better decision making and/or provide more insights for further analysis.

### Purpose

This analysis will provide insights on how launch dates for Theatre campaigns and funding goals for play campaigns impacted kickstarter outcomes of success, failure, or cancellations of those campaigns.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

#### Trends
Starting in March the number of theatre compaigns being launched begins to increase, peaking in May and then trending down for the rest of the year.  The lines for successful and failed campaigns move in tandem as shown in the graph.  We can see that as the number of successful campaigns increases that the number of failed campaigns also increases.  The number of cancelled campaigns is consistently flat and does not appear to be impacted by launch date.

#### Best & Worst Months for Launching a Theatre Campaign
In the graph we see the narrowest gap between successful and failed campaigns is in the month of December suggesting this would be the worst month to launch a campaign.  The widest gap between the two is in the months of May and June suggesting this is the best time to launch a campaign.  The number of cancelled campaigns is rather insignificant overall.

![Theater Outcomes vs Launch Data](/Theater_Outcomes_vs_Launch.png)


### Analysis of Outcomes Based on Goals

#### Trends
There does not appear to be any consistent trend between success or failure as the goal amounts increaase.  The jagged lines implies there is more at play than just the goal amount driving results.

#### Best & Worst Goal Ranges
Based on this data it would appear that the best goal amount is $1000 or lower and $35000-39999.  The worst goal amounts are $45000 to $49999 and $25000 to $29999.  There is no additional data to provide insights as to why these bands are the best or worst.

![Outcomes Based on Goals](/Outcomes_vs_Goals.png)


### Challenges and Difficulties Encountered

#### Formula Error
When I originally tabulated my outcomes based on goals table using the countif formula I copied my formula over from the first column and then manually adjusted the cell references.  Without realizing it I made two typos and when I generated my chart it did not look as expected.  When I inspected my cells I found the error.  I improved my formula by setting an absolute reference in my formula so I would not need to make manual adjustments when I copied my cell to the right.  

#### Syntax Error
In my initial draft for this readme report I could not get the graphs to appear because I was making a syntax error and was entering a space where there should not have been one.


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

  - Based on the data it would appear that even though there would be a high number of campaigns running in the months of May and June resulting in lots of competition, these are still the best months to launch a theatre campaign.  The worst months for launching a kickstarter are November, December and January.

- What can you conclude about the Outcomes based on Goals?
  - The outocmes based on goals does indicate a high success rate for goals under $1000 however overall there does not seem to be enough information to conclude that goals impact success or failure because the results across the various goal ranges has no consistency.

- What are some limitations of this dataset?
  - There is no data to measure the effectiveness of the pitch (i.e. the details about what the play is about)
  - There is no data about the methods used to market the campaign to potential kickstarter backers.  Did the founder leverage social media ads?  Or engage in other marketing efforts?
  - There is no demographic data about backers from historical campaigns.  Demographic data could influence how the pitch is crafted and other marketing activities.

- What are some other possible tables and/or graphs that we could create?
   - Perform a goals analysis on Theatre kickstarts & Goals by country and by year
  - identify any outlier data and make decisions about the inclusion of this data
  -  Calculate summary statistics such as measures of central tendency, standard deviation, and variance for the subset of data we are analyzing, namely theatre campaigns
  - For the outcomes by launch date it would be effective to show the outcomes as a percentage by month, see chart on the right below.  When you do this you find that aside from December for all other months the success rate is between 56-66% a range of 10 percent. When you look at the chart without percentages, chart on the left, it has the effect of appearing oversized for those specific months when it is not that much different percentage-wise.  
  
![Launch by number vs percentage](/Launch_outcomes_launch_date_vs_percentage.png)
