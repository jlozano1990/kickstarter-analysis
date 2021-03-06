# Kickstarter Analysis
## Overview of Project
### Purpose
---
The purpose of this project is to visualize Kickstarter outcomes based on their launch dates and their funding goals to best advise Louise on what she should do to launch her own successful play.
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
---
This analysis was performed by looking at the outcomes of Kickstarter campaigns that fell under the theater category. A PivotChart was created to filter the Kickstarter data by looking at the theater campaigns and whether they were successful, failed, or were canceled over a number of years. This is displayed in the form of a line chart with markers. This was done to visualize trends in terms of what months tend to have the most successful theater campaigns.
![Outcomes Based on Launch Date](https://github.com/jlozano1990/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)
### Challenges and Difficulties encountered
---
There was not very much challenge when it came to analyzing this dataset or displaying it. A challenge that may arise for someone is not filtering the data in a way that properly displays the results we'd like to show.
### Analysis of Outcomes Based on Goals
---
This analysis was performed by looking at what goals Kickstarter campaigns had set for themselves and seeing what percentage of campaigns achieved that goal and what percentage of campaigns did not. A PivotChart was created to display the percentage of successful campaigns and compare them to the percentage of failed campaigns in the theater subcategory of campaigns. This was displayed in the form of a line graph.
![Outcomes Based on Goals](https://github.com/jlozano1990/kickstarter-analysis/blob/main/Outcomes_vs_Goals_Fix.png)
### Challenges and Difficulties encountered
A challenge I faced when trying to display the information was that the line graph was displaying incorrectly for me. The problem was I hadn't properly organized how I wanted Excel to show the information, so the <1000 category was somewhere in the middle, and the rest of the categories were not displaying properly because of that. Once I realized the issue, I organized it the way it should've been organized.
## Results
Based on the **Outcomes Based on Launch Date** line graph, we can conclude that the best month to launch a new Kickstarter trying to fund a play in the US would be May. In the month of May, we had the most ***successful*** Kickstarters for new plays. We can also conclude that one should try to avoid launching a new play in the time around October. That was when we saw the most ***failed*** Kickstarters for new plays.

When it comes to the **Outcomes Based on Goals** line graph, we can conclude that it is best to set a goal that's less than $5,000 or a goal between $35,000 and $45,000 in order to reach said goal. The Kickstarter campaigns that had goals in those parameters were more likely to achieve their goals.

These two graphs give us a good view at seeing when it would be best to launch a new Kickstarter for a play to get fully funded and what goals we should set in order to achieve them, however, those are not the only two things that contribute to the success of a new campaign. One limitation of this dataset is that we don't know how people are finding the crowdfunding pages. If we knew that, we could see what areas of marketing were most successful for other Kickstarter campaigns and suggest to Louise to use those avenues to give herself a better chance of achieving the goal that she set for her own Kickstarter campaign.

Another possible table that we could create would be one comparing how many backers successful campaigns had versus how many backers failed campaigns had. We could use that information to predict how many backers Louise's new Kickstarter would have to get in order to be more likely to achieve the goal she sets for her campaign.
