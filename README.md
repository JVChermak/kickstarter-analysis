# kickstarter-analysis
Analysis on Kickstarter data to uncover trends
#Analysis of Kickstarter Campaigns
An analysis of various Kickstarter campaigns to see if there are trends based on category, subcategory, launch date, goal amount, and pledged amount for theater and plays. Brief analysis of data for musicals in Great Britain.

## Trends Based on Category
Looking at the data based on parent category, the theater category has the largest number of campaigns. In the US alone, the theater category had 912 campaigns out of 3038, and 525 of these campaigns were successful.
While the percentage of successful campaigns was not as high as the music category, theater has the third highest success rate at 57.5%.
![Parent Category Outcomes](https://github.com/JVChermak/kickstarter-analysis/blob/master/Parent%20Category%20Outcomes.png)

## Trends Based on Subcategory
In the theater category for the US, plays are by far the most popular group with 671 out of 912 total campaigns, 412 of which were successful meaning a 61.4% success rate. For all countries, plays consist of 1066 out of 1393 total campaigns, 694 of which were successful meaning a 65.1% success rate.
The data also shows that while campaigns for both musicals and spaces have been canceled, no campaigns for plays have been canceled in any country.
![Subcategory Outcomes](https://github.com/JVChermak/kickstarter-analysis/blob/master/Subcategory%20Outcomes.png)

## Trends Based on Launch Date
Looking at the launch dates for all years, May has the highest number of successful campaigns. The numbers steadily decline through September and then are lowest in December. The number of successful and failed campaigns are almost the same in December.
![Outcomes Based on Launch Date](https://github.com/JVChermak/kickstarter-analysis/blob/master/Outcomes%20Based%20on%20Launch%20Date.png)

## Descriptive Statistics for Successful and Failed Campaigns
Based on the data for successful and failed campaigns for plays in the US, the mean goal amount and pledged amount are higher than the median amounts, showing that the data is skewed. The standard deviations are also very large for each group of data.

## Musicals in Great Britain
The average goal amount for musicals in Great Britain is just over 4,000 GBP, shown by the x in the plot. This is much higher than pledged amounts without outliers. The median goal amount is 2,000 GBP, which is just over the upper quarter for pledged amounts. There is one outlier for each, shown by the dots, with a goal amount of 15,000 GBP and a pledged amount of 10,092 GBP.
![Statistics for Musicals](https://github.com/JVChermak/kickstarter-analysis/blob/master/Box%20and%20Whisker_Musicals.png)

## Recommendations for Louise
Based on the number of successful campaigns in theater, it would be reasonable for Louise to launch a Kickstarter for her play.
1. The best time to launch would be in May.
   - June or July are also good options.
2. The goal amount of $12,000 for the play is an outlier for both goal and pledged amounts.
   - Better to have a goal amount less than $6,000.
3. The goal amount of 4,000 GBP for the musical is an outlier for both goal and pledged amounts.
   - Better to have a goal amount less than 2,000 GBP.

### Challenge Analyses
#### Outcomes Based on Goal
Breaking down the data to find the number of successful campaigns for plays by specific goal range shows that there is a higher percentage of successful campaigns for goals that are less than $20,000. There is another spike for goals between $35,000 and $45,000. However, the highest percentage of successful campaigns have goal amounts less than $5,000. Also, goal amounts of $45,000 to $49,999 had a 100% failure rate. There were no canceled campaigns for plays, which is confirmed by the line at 0 on the graph.
- While Louise's planned goal amount of $12,000 falls into the category of outlier, she still has a 54% chance of success.
![Outcome Based on Goal](https://github.com/JVChermak/kickstarter-analysis/blob/master/Outcome%20Based%20on%20Goal.png)

### Outcomes Based on Launch Date
Looking again at the data for theater campaigns in all countries, May has the highest number of successful campaigns while December has the least. There is a very small number of canceled campaigns for most of the year, with a gap in October.
![Outcomes Based on Launch Date](https://github.com/JVChermak/kickstarter-analysis/blob/master/Outcomes%20Based%20on%20Launch_Challenge.png)

Digging further into plays in the US, May still has the highest number of successful campaigns. This data shows that the number of successes stays strong through August. Because there were no canceled campaigns for plays, the line was omitted.
- The best time to launch would be in May.
  - June, July or August are also options for plays in the US.
![Outcomes Based on Launch Date for Plays in the US](https://github.com/JVChermak/kickstarter-analysis/blob/master/Outcomes%20Based%20on%20Launch_Plays.png)

#### Limitations and Suggestions for Additional Tables
The categories and subcategories are very broad in the given dataset. There is no breakdown for genre, i.e. comedy or drama. There is also no sense of scope. For example, is this a one-woman show? How many acts are in the play?
Besides digging into the launch dates by plays in the US, it might be useful to know the length of successful campaigns. This would tell Louise if shorter or longer campaigns were more successful. It might also give her an idea of how long she should expect her campaign to run.
