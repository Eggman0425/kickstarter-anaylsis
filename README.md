# Kickstarter Analysis
Performing Analysis on Kickstarter data to uncover trends
## Overview
The purpose of this analysis was to see how various campaigns in Louise’s Kickstarters did in relation to their launch dates and their funding goals. This analysis took data from an established Kickstarter dataset and visualized the outcomes of theater campaigns and the months they launched, as well as charting the percentage of outcomes based on the goals set for play campaigns.
## Analysis
###### Outcomes Based on Launch Date
This analysis was performed by first looking at the outcomes of theater campaigns based on the dates they launched. I did this by creating a pivot table based on information from the successful, failed, and cancelled theater campaigns and the months they launched. By looking at months instead of specific dates, we get a cleaner visual of the outcomes. 
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/100382595/159180164-fc12288e-cc14-40aa-9783-44218c1a3759.png)
###### Outcomes Based on Goals
Secondly, this analysis visualized the percentage of successful, failed, and cancelled plays based on their funding goal. I did this by utilizing the COUNTIFS() function in Excel to help pull specific data from the original Kickstarter dataset into a new sheet. This new sheet held columns that grouped the Kickstarter projects based on their goal amount, which I then used the SUM() function to find the percentage of those projects. By getting the percentage of successful, failed, and cancelled plays in correlation with their funding goals, we can understand how well the play projects in achieving their funds as visualized by the following graph.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/100382595/159180547-2a1b2dce-c8e4-4774-80fd-c5979030e9ea.png)
###### Challenges
The biggest challenge I faced was consistency in the COUNTIFS() formula. I made sure to check my work at the end of each column in the Outcomes Based on Goals sheet, and by doing that I was able to catch errors in my formula and then correct them. 
## Results
In conclusion, in the outcomes for theater campaigns, the best time to launch a successful campaign are in the months of May and June, with the worst month being December. For outcomes based on goals, the smaller the goal, the more likely it was to be a successful campaign. The dataset is limited in its size and how definitive it is. The amount of projects in the Kickstarter are not as much as I would like to draw a better conclusion, and the projects are concluded so it is harder to track their success rate over a period of time. I think another line graph could be used to compare theater and play campaigns, with different graphs for successful, failed, and cancelled. This way we could visually see how these campaigns did side-by-side as they are so similar in content. 
