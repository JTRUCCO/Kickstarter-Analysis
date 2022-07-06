# Kickstarting with Excel

## Overview of Project

To help louise choose the best way to structure her Kickstarter for her play "Fever", so that it is successful. She wanted to know how Different campaigns did against hers with respect to Launch date and fundraising goals.

### Purpose

Make conclusions for Louise's project based on Analysis of Past Kickstarters and More Specifically Kickstarters that are in the subcategory "Plays". "Musicals" were also looked at. If we can find trends in our sample data we will be better prepared to make an informed decision.
 
## Analysis and Challenges

Visualized the different campaign outcomes on the basis of their launch date in relation to their fundraising goals. We also looked deeper into the outcome based on goal amounts. I used a pivot table with outcomes in columns, Date created in the rows, count of outcomes in the values columns and category and years in the filters. I created a line graph with markers to visualize the outcomes based on launch date. For outcomes based on goal amount, I created a table With ranges in the first column and headers labeled, Number Successful, Number Failed, Number Canceled, Total projects, Percentage Successful, Percentage Failed, Percentage canceled. I used the Countifs() function and the Sum() function when determining the contents of the table. I created a line chart with goal-amount ranges on the x axis, and the percentage of successful,failed, or canceled projects on the y axis.

### Analysis of Outcomes Based on Launch Date

Measured the different outcomes," Successful", "Failed", "Canceled" in relation to months. From there I made a pivot table in Excel to better visualize the relation between the different outcomes.
I Noticed that there are many successful Kickstarters in the Months of May(111 "Successful" Kickstarters) and June (111 "Successful" Kickstarters) This trend starts to taper off in June and continues to decline until December.

![Outcomes based on launch date](https://github.com/JTRUCCO/Kickstarter-Analysis/blob/main/Theater_Outcomes_vs_Launch.png?raw=true)

### Analysis of Outcomes Based on Goals

Created a line chart to show the relationship between the different goal ranges on the x axis and the percentage of kickstarters that were Successful or failed on the y axis.
The Blue line represents the percentage of projects that were successful in the given ranges.
The Orange line represents the percentage of projects that failed in the given goal ranges.
The "successful" and "failed" percentage lines I interpreted show that Projects up to with goals up to 15000 dollars are typically above 50% successful. For projects that are above 15000 the percentage of failed projects is over 50% overall. The success rate crosses over the 50% barrier once more at the range between 35000 to 45000. I would suggest that the goal stay below 15000 dollars.


![Outcomes on goals](https://github.com/JTRUCCO/Kickstarter-Analysis/blob/main/Outcomes_vs_Goals.png?raw=true)  


### Challenges and Difficulties Encountered

I had to make sure my data was calibrated and structured correctly and properly visualized. I wanted to make sure I was properly representing the data in a way that is meaningful to the viewer. There was no data cleaning or outliers in this data because we want to look at all of the data at once in order to display a truthful picture of the full data.

## Results
The result o

- What are two conclusions you can draw about the Outcomes based on Launch Date?

The month of May had the most successful Kickstarters with 111 instances. There were 52 failed Kickstarters in the month of May. There are around 2 to 1 successful to failed projects. This is a good ratio and I would recommend launching the Kickstarter in May.
 
Beginning in May there is a downward tapper of Successful Projects continuing all the way to January where it begins to pick up again. I would recommend launching a Kicksterter in May or June.

- What can you conclude about the Outcomes based on Goals?

Goals set between "Less than 1000" to "15000 to 19999" have historically been above 50% Successful.
 
I would conclude that the Kickstarter for the play should be under $15000 for their goal to be successful.
Anything above the $15000 goal Shows less favorable results based on the historical data.


- What are some limitations of this dataset?

This is a limited sample size and could only represent a small portion of the population as a whole. If the sample size was larger, we would have a bigger and clearer picture.
 
If this data was self reported it could be unreliable due to personal bias. If we had a reporting strategy that would unbiasedly collect data based on verifiable identifiers we could be more confident in our final analysis.
 
There could be information that could provide more feedback and help us make a more informed decision. An example of this could be the status of the person creating the kickstarter and if they have past successful Kickstarters. It would be interesting to see how many people who have successful kickstarters were first-time users or if they were kickstarter veterans.

- What are some other possible tables and/or graphs that we could create?

We could create a stacked bar chart to look at different subcategories. We can add filters such as Country, goal and pledged to drill down to see specific information about outcomes of past kickstarters.
 
Having a genuinely good play that people enjoy and recommend is very important and knowing people's thoughts on the play would be useful data to include and add to the tables. How well the public receives the play is important and marketing data for information such as engagement level on posts could be a good KPI to examine.
