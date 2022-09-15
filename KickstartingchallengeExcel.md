# Kickstarting with Excel

## Overview of Project
Visualizing outcomes based on Kickstarter campaign launch dates and funding goals. 

### Purpose
Comparing Kickstarter campaign launch dates and funding goals for Louise who wants to achieve a successful campaign.  

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
To understand the outcomes by launch dates, a pivot table was created to compare the successful, failed, and canceled events to the months that they were scheduled to launch. A filter was created for the Parent Category (Category) and Years.  The outcomes were counted and the months were placed in the Row. A line graph was created from the pivot table. 

![Theater_Outocmes_vs_Launch](https://user-images.githubusercontent.com/111452227/190430891-a0b8a76c-7f6b-4dfc-9738-12497400afea.png)

### Analysis of Outcomes Based on Goals
Louise wanted to know more about the campaigns based on their funded goals.  To compare the number of successful, failed and  canceled campaigns, the CountIF() function was used.  The Sum() function was used in column E to obtain the total number of projects.  Finally, the perctange formula (percentage/total project) was used to list the percentage for all 12 funding ranges.  A line graph was created from this data.  From the Select Data section ( right click on graph) I placed the percentage on the Y-axis and the price ranges in the X-axis.  


![Outcomes_vs_Goals](https://user-images.githubusercontent.com/111452227/190431177-fb35990d-fd36-461f-aceb-1a9d8a215635.png)



### Challenges and Difficulties Encountered
X-axis as months: I spent a lot of time trying to filter out months from the years/quarters from the Rows field.  I think I removed the additional categories from the Rows Field and that is how I was left with the months although the steps in doing that were not successful until several tries later. 

Removing the Live outcome: It also took me a while to realize that in order to remove the Live outcomes, I simply had to click on the Column Labels and unselect Live from the dropdown. I then moved on to filtering out which outcomes.  After exploring the table, I found that clicking on the Column Labels allowed removal of the Live outcomes. 

Outcomes Based on Goal charts: I learned halfway through that you can simply change the goal values without reentering the column names/formula each time. I also made data entry errors so I had to go back and correct some of the values and "><" characters to match the line graph image to the lesson. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

    Conclusion 1: The best time to launch a successful theater campaign is end of May and June.
    
    Conclusion 2: October and December had high rates of failed campaigns so it is best not to launch a kickstarter campaign during those months. 

- What can you conclude about the Outcomes based on Goals?

    Conclusion 3:  Goals that were set with funds less than $4,999 or between $35,000 to $49,999 had the highest success percentages (blue line). 

    Conclusion 4: Goals that were set with a fund between $25,000 to $34,999 or more than $45,000 had the most failed campaign percentages (green line). 

- What are some limitations of this dataset?

    When looking at conclusion 3, the data doesn't explain why funded goals between $4,999 and $34,999 were not as successful but goal funds in the next range up ($35,000 - $45,000) were. 
    
    This analysis only compared outcomes for theater plays. 

- What are some other possible tables and/or graphs that we could create?

    We could create a table comparing the funded goals with the time of the year. 

    We could create tables and graphs for other types of categories or subcategories, i.e musicals.
    
    We could create tables comparing the campaigns in different countries. 
