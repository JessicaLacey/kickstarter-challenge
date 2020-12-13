# kickstarter-challenge

## Analysis of Theater campaigns based on launch date and goal

### Compare Louise's campaign to others within the Theater category

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
First I created a pivot table using the Launch Date and Outcomes fields. I filtered the Parent Category to theater and then filtered to only show the months. With this table you can see that the best times to launch a campaign are May and June. The worst time to launch a campaign is in December.

I then created a line chart to visually represent the pivot table. The chart makes the Outcome, mentioned above, very clear.

![Theater_Outcomes_vs_Launch](path/to/https://github.com/JessicaLacey/kickstarter-challenge/blob/main/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
I created a table that breaks down the goal amount into several categories. This makes it easier to read and understand the data. From this I can see the majority of the campaign goals were under 10000.

From this table I created another line chart based on the goal percentage. The chart allows you to see that the higher the goal, the less successful campaigns there are. 

![Outcomes_vs_Goals](path/to/https://github.com/JessicaLacey/kickstarter-challenge/blob/main/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
The biggest challenge I faced was the COUNTIFS formula. There are so many parts to this and if one thing is off, it will mess up all of the data. It was just trial and error until I figured out the correct formula.

## Results

- Based on the Launch Date, the best time to start a campaign is May. The worst time is December.

- Based on the Goals, the most successful campaigns had a goal of less than 10000. The higher the goal amount is, the less likely you are to have a successful campaign.

- One limitation of this dataset is that the launch date data shows numbers for all of the theater category which includes musicals and spaces. It would be more accurate to filter by plays.

- One possible table and/or graph we could create is the length that the campaign stayed open. Louise's campaign was open for a little less than a month. If it had been open for a longer period of time, she may have reached her goal. Another possible chart we could create is the number of backers compared to the average donation amount.
