# Kickstarting with Excel

## Project Overview

* Given that the play "Fever" came close to its fundraising goal in a short amount of time, Louise wants to more closely examine the outcomes for other plays based on their launch dates and funding goals. Using data visualization, this project illustrates the outcomes of plays based on these two main criteria. Deliverable 1 shows the outcomes based on launch dates. Deliverable 2 shows the outcomes based on goals, and Deliverable 3 is a written analysis of the results.

* The purpose of this project is to analyze how the goal amount and launch date impact theater campaigns outcomes throughout an entire year.

---

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date & Challenges

* In order to analyze the outcomes based on launch date, I created a pivot table in a new sheet, added Parent Category and Years as filters and displayed the Axis categories as months instead of Quarters. I selected theater only as parent category and put the outcomes in descending order, so that the successful campaigns are visible first. 
[Kickstarter_Challenge](/Users/irinapreotescu/Desktop/Analysis Projects/Crowdfunding Analysis/Kickstarter_Challenge.xlsx)

The line chart can be seen here:
![Theater_Outcomes_vs_Launch](/Users/irinapreotescu/Desktop/Analysis Projects/Crowdfunding Analysis/resources/Theater_Outcomes_vs_Launch.png)

* A challenge I encountered was remembering how to display the months of the year. I overcame that by researching how to group the data in pivot tables.

### Analysis of Outcomes Based on Goals & Challenges

* In order to analyze the outcomes based on the campaign goals, I created the range categories, then used the COUNTIFS function to count all the successful, failed, and canceled campaigns for theater plays, respectively. I used the SUM function to caculcate the total number of successful, failed, and canceled campaigns, and the ROUND function to calculate the percentage of successful, failed, and cancelled projects. I used the line chart to illustrate this analysis, which can be seen below.

![Outcomes_vs_Goals](/Users/irinapreotescu/Desktop/Analysis Projects/Crowdfunding Analysis/resources/Outcomes_vs_Goals.png)

* One challenge I encountered was formatting the chart to include exactly what the assignment required. I overcame this by going back to the class material and selecting the correct range for the chart. I was not able to add the percentage symbol for the y-axis values. 

---

## Results

1. The best time to launch a theater play is in May and June. 
2. The worst time to launch a theater play is in December and October.

--- 

1. The best goal range to have for theater plays is either less than $1,000 or between $30,000 and $40,000. The highest percentage of successful plays had campaign goals in these ranges.

---

* What are some limitations of this dataset?
- One limitation is that it does not tell us whether these results are region or country-specific, which might show different results. Another limitation is that it does not tell us how long the campaigns lasted and what the average donation was. Longer campaigns might have yielded better results because there was more time for the goal to be reached. Certain campaigns might have had different target audiences and therefore different average donations, which might have affected the outcomes of the plays.

* What are some other possible tables and/or graphs that we could create?
- We could create a country-based table to illustrate whether or not location impacts campaign outcomes. Additionally, we could also create a table that categorizes campaign length and average donation.

