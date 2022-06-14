# Kickstarter-Analysis
Performing analysis on Kickstarter data to uncover trends

## Overview of Project
Shows visually how succesful or unsuccesful the theater categpry was based on what goals they had and when they were launched.

### Purpose
To show trends that are useful for Louise and her future project campaignes.
## Analysis and Challenges
 Analyzing the data for both launch date and funding goals was necessary to see two different points of view. That way Louise can use it to further her planning when it comes to her projects. The challenges I faced were getting the formula for the count ifs to count what I wanted specifically. I got held up by counting the whole column of outcomes instead of specifically successful, failed, or canceled like I needed it to. I overcame that by adding in more criteria and criteria ranges.
### Analysis of Outcomes Based on Launch Date
To start the analysis to and draw the Outcomes Based on Launch date I started with a pivot table using the Kickstarter worksheet. I then included the year, parent category, successful, canceled, and failed to the rows and columns. I arranged the data to have the months be the rows and the successful, failed, and canceled to be the columns. And leaving the parent category and years to be able to be filtered. After that, I inserted a line graph to show how many were successful, failed, or canceled over the span of the months in a year.
### Analysis of Outcomes Based on Goals
The process of figuring out the Outcome Based on Goals started with creating a new sheet within the Kickstarter worksheet. Starting with the ranges of goals in the rows and having the following be the columns: Number Successful, Number Failed, Number canceled, Total projects, Percentage successful, Percentage Failed and Percentage canceled. This is the countifs function that extracted that number for each column that I needed: =COUNTIFS(Kickstarter!$F:$F,"successful",Kickstarter!$Q:$Q,"plays",Kickstarter!$D:$D,"<1000"). I would modify that based on what certain column I was in and what range of the goal I was looking for. I then selected all the data and made a line graph to show what percentage of goals succeeded or failed within each range of goals.

### Challenges and Difficulties Encountered
 Another challenge that occurred was when I inserted the line graph for the Outcomes Based on Goals, is that my graph was showing too much data. I had to filter it to only show the percentage successful, percentage failed, and percentage canceled columns.
## Results
•	What are two conclusions you can draw about the Outcomes based on Launch Date? The best time to launch a project is in May. December is possibly the most ill-timed month to launch a play considering it had the least amount of successful plays.

•	What can you conclude about the Outcomes based on Goals? 100% of the campaigns failed between the goal amounts of 45,000 to 49,999.
To give Louise a better chance at success she needs to keep it below 45,000. Her second highest success rate was 66.7% percent between the 40,000 and 44,999 range. She doesn’t have to sacrifice the amount of money to guarantee success she just has to keep it below 45,000.
•	What are some limitations of this dataset?
You can see what percentage or how many were successful, failed, or canceled, but you cannot see what other factors played a role in the reason why they also may have been successful or unsuccessful.
•	What are some other possible tables and/or graphs that we could create?
A clustered column graph would be helpful to compare the successful and failed percentages of the Outcomes Based on Goals.

