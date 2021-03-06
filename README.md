# An Analysis of Kickstarter Campaigns

## Overview of Project
Performing analysis on Kickstarter data to uncover trends in the film industry for Louise to use while considering the ideal project launch month and funding goal based on previous success rates.

### Purpose
The purpose of the project is to help Louise better understand how different campaigns fared in relation to their launch dates and their funding goals.

## Analysis and Challenges

### Analysis of outcomes based on Theatre Outcomes by Launch Date
![Theatre_Outcomes_vs_Launch.png](https://github.com/GiovanniBottone/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)
The main takeaway from Theatre Outcomes by launch Date should be focused on idntifying the most and least successful launch dates. Once these have been identified, Louise will have a much better understanding of her projects timeline. The most successful month for launch dates is May by chart standards and percentage standards, May has the highest success rate 67%, which can be found by dividing the Column Labels successful by GrandTotal. According to the chart May also has the highest fail rate; however, when you divide failed by total projects you'll see that May actually has the lowest failure percentage, 31%. December has the highest fail rate, 47%, and the lowest success rate, 49%. The second lowest success month according to the chart is November; however, when you dive into the percentages (Column labels successful / Total Projects) you'll see that October actually has the second lowest success rate, 57% compared to Novembers 61%)

### Analysis of Outcomes Based on Goals
![Outcomes_vs_Goals.png](https://github.com/GiovanniBottone/kickstarter-analysis/blob/main/Resources/Outcome_vs_Goals.png)
The main takeaway from Outcomes based on goals should focus on identifying the most successful and least successful goal ranges. Once these have been identified, Louise can decide what her project goal is based on the most successful goals. The lowest goals are the most successful, Goals of less than $1,000 have the highest success rate, 76% successful, as well as the lowest fail rate, 24% failed. The second most successful goal is $1,000 - $4,999, with a success rate of 73% and the second lowest fail rate, 27%. The most expensive goals are the least successful, Goals of $45,000 - $49,999 have the lowest success rate, 0% successful, as well as the highest failure rate, 100% failed. The second least successful goal is $50,000+, with a success rate of 17%, and the second highest fail rate, 83%. 

### Challenges and Difficulties Encountered
The main challenge I experienced when going through the data happened with Deliverable 1 part 10, grouping the data. My grouping dialog box did not have the necessary options to group the data from years to months, which put a tremendous halt in my progress. Eventually, I was able to overcome this challenge by adding the 'Data Created Conversion' into the rows section of the pivot table, which created a 'years 2' and a 'quarters' in the rows section. Once I dragged 'years 2' and 'quarters' out of the pivot table, I was able to group my years rows into months. An Additional challenge I faced happened with Deliverable 2 part 4, COUNTIFs. At first, I was unable to understand what information I was searching for in the formula, and struggled to gather the necessary information. Eventually, I decided to breakup the formula into sections and define exactly what I was looking for, which gave me a much clearer understanding of the process and allowed me to use the formula successfully. 

## Results
What are two conclusions you can draw about the outcomes based on launch date?

Two conclusions I can draw about the outcomes based on Theatre launch date are that May launch dates should be prioritized and December launch dates should be avoided. May has the highest success rate percentage, 67%, as well as the lowest fail rate percentage, 31%. December has the lowest success rate, 49%, as well as the highest fail rate percentage, 47%. Success rate percentages can be found by dividing the Column Labels successful number by the Grand Total Number, and Fail rate percentages can be found by dividing the failed number by the Grand Total Number. Ex: May Success Rate 111/166 = 66.8 or 67%, and December fail rate 35/75 = 46.6 or 47%. 

What can you conclude about the outcomes based on goals?

I can conclude that goals less than $4,999 are the most successful, and should be considered the best goal. Goals of less than $1,000 have the second highest number successful, 141, and the highest percentage successful, 76%; as well as the lowest percentage failed, 24%. Goals of $1,000 to $4,999 have the highest number successful, 388, and the second highest percentage successful, 73%; as well as the second lowest percentage failed, 27%.

What are some Limitations of this dataset?

One key limitation is there is no genre column in the kickstarter data. The lack of genre information can be considered a limitation to the dataset because it essentially removes a potential trend from the data. For instance, if we had a genre column and classified each ID into a specific genre, we would be able to identify the most and least popular genres of the year, the most and least successful genres in terms of reaching their goals, all of which would help Louise understand the market she's considering going into. If Louise's project is classified as a drama, and the drama category as a whole has struggled to reach their goals, Louise would have a better understanding of the struggles she may face with her current project. This may not be enough of a discouragement to Louise; however, it's important that we highlight every necessary bit of information for her to base her project off of, and without genre information, we can't do that.

What are some possible tables and/or graphs we could create?

A table and graph that would paint a more accurate picture would be a pivot table and line graph for Theatre Outcomes by Launch Date, with the main distinction being percentages shown and graphed, similar to the Outcomes Based on Goals sheet. Basing your charts off of totals can be disingenuous because one month may be substantially more popular launch dates which would skew the graph to make that month the 'most successful', when in reality another month could have a higher success percentage even though it has a smaller amount of launches. For example, on the Theatre Outcomes Based On Launch Date chart it shows that July is a more successful month than April because July has 87 Column labels successful and Aptil only has 71; however, July and April both have a 63% success rate (July 87/138 = 63% & April 71/113 = 62.8 or 63%.) By adding percentage columns to the pivot table and graphing based on percentages of success, failed, and cancelled, Louise would have a more accurate display of the information.
