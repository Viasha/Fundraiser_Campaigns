# Fundraiser_Campaigns
## Overview of Project
Analysis on several thousand crowdfunding projects from around to world to uncover hidden trends and insights. I analyzed the success of fundraising campaigns based on catergory, launch dates and funding goals. 

### Purpose
A new playwright wants to launch a crowdfunding campaign for her play Fever but is hesistant about  her first attempt. This analysis explores key factors that contribute to successful campaigns. The insights gained will help her model her approach after proven successes, maximizing her chances of reaching her funding goal.
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
Using a pivot table and chart, I analyzed the campaign outcomes based on the month of the year it was launched. The month that launched the most success campaigns was May. May was also the most succcessful month for theater campaigns. For theater campaigns, January, March, September and November all roughly had the same number of failed campaigns launched. December has the least amount of successful campaigns. 
![Outcomes Based On Launch Date]"C:\Users\isler\Documents\Data_Analytics_2\Fundraiser_Campaigns\Resources\Outcomes based on launch date.png"
![Theater Outcomes Based on Launch Date]"C:\Users\isler\Documents\Data_Analytics_2\Fundraiser_Campaigns\Resources\Theater_Outcomes_vs_Launch.png"


### Analysis of Outcomes Based on Goals
To futher explore the success of theater campaigns, I narrowed down to explore plays specifically. I created a line chart that shows the success rate based on funding goals.
Funding goals showed an impact on the success of the campaign. Fundraisers with goals less than 1000 have the highest success rate and the lowest fail rate. When goals exceed 15000, the percentage of failed campaigns exceed success rate. Funding goals of 35000 to 44999 have the third highest success rate.  
![Outcomes Based on Funding Goal]"C:\Users\isler\Documents\Data_Analytics_2\Fundraiser_Campaigns\Resources\Outcomes_vs_Goal.png"

### Challenges and Diffuculties Encountered
While exploring this data set I encountered a challenge regarding the formatting of the columns providing date information. This caused an extra step to convert the data into readable information. Once I passed this challenge I was able to explore the factors related to timing and uncovered some impactful insights.

## Results
* The ideal time to launch a crowdfunding campaign is the month of May. December is not a successful time for theater crowndfuning due to it having the lowest success of the year.
* Funding goals of 15000 or less have good success rates. When fund goals exceed 45000 the failure rate is at it's higest.
* Some limitations of this dataset it that the currency values across the differrent countries could have different values. A goal of 15000 in US may equate to 30000 goal in another country.
* A currency conversion table would be useful to more accuarately compare funding goals and success rates across the different countries. 
