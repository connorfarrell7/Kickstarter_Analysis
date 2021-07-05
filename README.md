# An Analysis of Kickstarter Campaigns

##Overview
Louise is looking to produce a play. She plans on using a Kickstarter campaign to fund the play. There is available data for past Kickstarter campaign. I have analyzed the relevant data to optimize her success. I did this by looking at the two most important factors, which are the time of year to start the campaign and goal amount. 

###Analysis
This analysis was done in two parts. The first was done by looking into the time of year each campaign was started. The second was done by looking at the success rate of each campaign based on the amount of money they asked for. For the first analysis, I first converted the Unix timestamps into date format to better see the time of year. Next, I filtered the data to show only theatre related Kickstarter campaigns. Then I made a pivot table (table 1) to look at the time of year these were started. Using this pivot table, I made a chart for a visual representation of this data to easily determine the best time of year for Louise’s campaign. For the second analysis, I created several ranges to categorize the relevant campaigns based on their goal amount (table 2). I then filtered the data to show only campaigns for plays. Next, I put the new data set into the corresponding ranges. I sorted each range by successful, failed, and cancelled campaigns. Then I created a line chart to make a clear representation of the findings.
![Pivot Table](https://user-images.githubusercontent.com/86024575/124413109-00f8e100-dd1e-11eb-8a62-8afd8610ecc2.png)

Table 1

![Goals Table](https://user-images.githubusercontent.com/86024575/124413200-2980db00-dd1e-11eb-8c8b-949a70e70c89.png)
Table 2

####Challenges
The main challenge was assessing how to sort through the immense amount of data provided. I was able to overcome this challenge by becoming familiar with pivot tables and using their versatile features to isolate the relevant information.

#####Results
Based on the chart that I created (figure 1) for Theatre Outcomes by Launch Date, we can see that the best time for the campaign to start would be in May, with the next best options being June or July. As you can see in the chart, May has the highest amount of successful Kickstarter campaigns, followed by June and July with the second and third highest amounts. All three months also have the widest margin between successful and failed campaigns. We can also determine that the worst time of the year to start a Kickstarter campaign would be in December. This is because there are the least number of successful campaigns in December, and there are almost as many failed campaigns as successful ones. Looking at the graph (figure 2) that I created for the Outcomes Based on Goals, it appears that the optimal goal would be the Less Than $1000 range. This is because the chart shows the percentage of successful campaigns, not the absolute value. Furthermore, based on the data, the $1000 - $4999 range had far more successful campaigns. I would recommend this range for a goal amount. Also, this goal range would work well for Louise because it is within her initial estimations of cost. 
![Theatre_Outcomes_vs_Launch](https://user-images.githubusercontent.com/86024575/124412395-6a77f000-dd1c-11eb-96f8-aae4892be01a.png)
Figure 1

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/86024575/124412145-de65c880-dd1b-11eb-831b-3da2bca955a0.png)
Figure 2

######Limitations
A possible limitation is the amount of data for May being abundant whereas the other months don’t provide as much information. Noticeably, the sample size for May is the largest and it is the best optimal time to start a campaign, whereas the sample size for December is the smallest and it is the worst month to start a campaign. An even sample size for each month could provide a better understanding. I found there was another limitation in the visual representation for the Outcomes Based on Goals chart. I used a percentage and not the absolute amounts of successful campaigns compared to failed campaigns. This has created a visual that could be misleading, depending on what you are trying to interpret from the graph. 
