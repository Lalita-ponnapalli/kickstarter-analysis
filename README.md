# kickstarter-analysis

## Project serves the following purposes
Louise’s play Fever came close to its fundraising goal in a short amount of time. Now, she wants to know how different campaigns fared in relation to their launch dates and their funding goals. Using the Kickstarter dataset that you’ve already combed through, you’ll visualize campaign outcomes based on their launch dates and their funding goals. You’ll then submit a written report based on your analysis and the visualizations you create.
Theater outcome by Launch Date
This deliverable outlines the successful, failed and cancelled events since the Launch date of the theater. The events are summarized by month and can be filtered by year or all the years. The events can also be summarized by other parent categories.

# Outcome based on goals
This deliverable outliner the percentage of successful, failed and cancelled goals against multiple goal ranges.

# Analysis
Purpose and Background
Louise wants to know how play fever fared in different fundraising campaigns in relation to their launch dates and their funding goals. 

##Analysis and challenges for Theater Outcome by launch date
#Analysis
To get the count of successful and failed and cancelled projects separately by month for theater for a year, At first, I put date in a proper format so that I can get the values by month. Then I separated parent category and subcategory to get parent category “theater”.
Then put filters to get outcomes separately for successful, failed and projects.
Created a pivot table based on outcomes for counts of successful, failed, cancelled projects in relation to months, so that we know on which month we got highest or lowest successful launches, on which month we get lowest or highest failed launches, and we can know on which month of year we have the highest and lowest cancelled project for the year.

#Challenges
1.	The Launch date formats are not readable.

2.	Data conversions were necessary to get the desired results for months and years
      

##Analysis and challenges for outcome based on goals

Analysis
To get percentage for failures and successful projects based on goals on parameters, we need to get the total numbers for successful and failure projects for each parameter separately for subcategory plays.
For that we pulled the goals from the original sheet, set ranges on goals as per the instructions within subcategory plays and parameters of successful, cancelled and failure.
The counts are then evaluated and summed to calculate the total projects. The percentage for successful projects, failure projects, and cancelled projects is calculated by dividing the projects in each category by the total projects. The percentages are rounded.
A line chart is inserted with the Goal ranges and the percentages evaluated from above.

#Challenges
None.
#Results
Conclusions for Theater Outcomes by launch date.

1.	Total successful launches are more than the total failure but in the month of December count for launches of successful and failures are relatively low.

2.	Highest successful launches are in the month of May and lowest in Dec and the highest failures are in the month of June and lowest in December.



#Conclusions for Outcome based on goals.
1.	Goals for 1000 to 4999 have highest successful projects. Realistic approach for successful projects to put our goals around 4999 for subcategory plays. Percentage of cancelled projects are none.


#Limitation

The Outcomes related to annual Goals does not show the results. 
#Suggestions
Another graph with yearly goals performance needed.

