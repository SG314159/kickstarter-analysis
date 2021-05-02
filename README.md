# Kickstarting with Excel

## Overview of Project

### Purpose
The project analyzes data from a crowdfunding website. The analysis is done with Excel. The goal is to determine specific factors that make crowdfunding campaigns successful so that a new playright (Louise) can model her campaign after other successful campaigns.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
This tab contains a pivot table showing the number of successful, failed, and canceled theater fundraising campaigns. The count for each category is shown for each month of the year across the multiple years of the dataset. This analysis is designed to help Louise decide if certain months of the year are more successful for starting fundraising campaigns. 
The chart is filtered the same as the pivot table. The line graph shows the number of theater campaigns in each category over the months of the year. Again, note that multiple years are added up to make the total. That is, the number of successful campaigns in January is the sum of all successful campaigns across the years in the dataset.
Based on the pivot table and line graph, the month of May has the highest number of successful campaigns launched. The months of June and July are the next best months, in that order. December is the month with the fewest number of successful campaigns launched. Although there is a spike in the number of successful campaigns, the number of failed campaigns is relatively steady, hovering around 40 for most of the year. Very few theater campaigns were canceled.

### Analysis of Outcomes Based on Goals
This tab contains a table showing the number of successful, failed, and canceled fundraising campaigns from the subcategory of plays. The counts are separated by the dollar amount of the goal from the campaign. The counts are also displayed as percentages in the table and in the line graph. This analysis is designed to help Louise understand how likely her campaign will be successful based on its target goal to fundraise.
There were no "plays" campaigns canceled, so those values are all zero, thus making the successful and failed categories distinct partitions of the whole count. In the line graph, we see this because of the symmetric nature of the graph (horizontal symmetry across a middle line). 
From this data, it appears that as campaigns get more expensive goals, they are less likely to succeed. If Louise can keep her goal below $10,000, the data suggests that she will be more likely to be successful.


### Challenges and Difficulties Encountered
Though I did not have any major challenges, there are some difficult pieces of this analysis. First, a number of the data fields are textual or categorical in nature. These sometimes can be more difficult to analyze because of possible dirty data (misspellings and abbreviations) and because they are often not ordered and certainly not quantitative. If the data has lots of free-form data (e.g. Tweets or book reviews), the problem is even more complex to analyze due to the nature of language complexity.
I am grateful for the chance to learn about pivot tables and that you can filter related charts as well.


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
Assuming Louise wants her campaign to succeed, she should launch her campaign in May or June. If at all possible, Louise needs to avoid launching her campaign in November and December.

- What can you conclude about the Outcomes based on Goals?
Louise needs to keep her goal at or below her current budget of $10,000. The lower her goal is, the more likely she will be to succeed in the fundraiser.

- What are some limitations of this dataset?
We have information about the campaigns but not about the users that posted the campaigns nor about the people that donated to the campaign. This limits the ability that Louise has to form a target audience that would be likely to support her fundraiser. We also do not know when the donations came in relative to the start and end date. It may be helpful for Louise to know if there should be a rush at the beginning or a rush at the end or if the funding is somewhat steady. That could help her better plan financially.

- What are some other possible tables and/or graphs that we could create?
Instead of just having success and failure, it may be helpful to find the average percent that each campaign was funded. For example, that of the plays that had a campaign that failed, did those campaigns at least raise 50% of the goal?  This could be accomplished with a table and possibly a heirarchy or area chart of some sort and including the percentage funded column that we made as part of the module. 
It would probably also be useful for Louise to study the categorical factors of "spotlight" and "staff pick."  Presumably these are ways to highlight certain campaigns within the user display, and it would be helpful to know if those features (which probably have a cost) increased the chances of success or failure.



