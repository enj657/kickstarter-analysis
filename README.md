# Kickstarting with Excel

## Overview of Project

Our client, Louise, noticed that the play *Fever* raised money for its fundraising goal very quickly. She is interested to know how other theater campaigns handled reaching their goals based on launch dates and funding goals.

### Purpose

The purpose of these analyses is to figure out if different campaigns were successful or not in reaching their goals based on both their launch dates and their funding goals. 

## Analysis and Challenges

### Analysis Based on Launch Date
Our first analysis was to figure out theater campaign outcomes based on launch date. In order to figure out outcomes based on launch date I made a pivot table that lists the months of the year and shows the number of sucessful, failed, and canceled campaigns in columns. Each month represents the month that a campaign was started, or the launch date. On this pivot table I was able to filter the Parent Category for theater, and use the year filter to see any specific year. We then used this table to make a line chart, which makes it easy to see what launch dates had the highest success rates for theater campaigns.

![image info](./resources/Theater_Outcomes_vs_Launch.png)

### Analysis Based on Funding Goal
In the second analysis we were looking to figure out the relationship between outcomes and funding goal. I made a pivot table with goal ranges in the rows, and the outcomes in columns. I calculated the percentage of successful, failed, and canceled campaigned based on the funding goal. I made a line chart from the table with three lines showing the percentage of outcomes vs the funding goals. From the line chart we can easily see the outcome rates.


![image info](./resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties
The most diffucult part of the analysis was figuring out the countifs column in the funding goals vs outcomes table. I watched a video given to us in the courses material, and also looked up information on stackoverflow.com, and was able to figure out the correct formula.

## Results

Based on our analysis, we can determine from our data that the most successful month to launch a theater campaign is May because our line chart shows a spike in successes for the month of May. 

We can also conclude that December is the least successful month to launch a theater campaign because the success and failed rates are almost the same, and the success rates are lowest in December.

From the outcomes based on goals analysis, we can see that with funding goals up to the range of 15000 to 19999 theater campaigns have a higher success rate that failure rate. However, after the range of 15000 to 19999 the failure rate is higher than the success rate. There is a small range between 35000 to 39999 and 40000 to 44999 where theater campaigns have a higher success rate, but after 44999 the trend switches again.

Some of the limitations of this dataset include having a fairly small sample size and not having more outside research to compare our data to. In this analysis we are making conclusions about theater campaigns with only a small amount of data, and I think with more research our conclusions will change.

Another graph we could make is length of campaign vs outcomes. This graph would show us if the amount of time each campaign lasted changes the success rate of the campaign. It would benefit our client to see whether a short or long campaign is better.

