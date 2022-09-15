# Kickstarting with Excel

## Overview of Project
Visualizing outcomes based on Kickstarter campaign launch dates and funding goals. 

### Purpose
Comparing Kickstarter campaign launch dates and funding goals. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
To understand the outcomes by launch dates, a pivot table was created to compare the successful, failed, and canceled events to the months that they were scheduled to launch. A filter was created for the Parent Category (Category) and Years.  The outcomes were counted and the months were placed in the Row. From there, a line graph was created from the pivot table. 

![Theater_Outocmes_vs_Launch](https://user-images.githubusercontent.com/111452227/190430891-a0b8a76c-7f6b-4dfc-9738-12497400afea.png)

### Analysis of Outcomes Based on Goals
Louise wanted to know more about the campaigns based on their funded goals.  To compare the number of successful, failed and  canceled campaigns, the CountIF function was used.  The Sum function was used in column E to obtain the total number of projects.  Finally, the perctange formula was used to list the percentage for all 12 funding ranges.  A line graph was created from this data.  I had to manipulate the data set to get the percentage on the Y-axis and the price ranges in the X-axis.  


![Outcomes_vs_Goals](https://user-images.githubusercontent.com/111452227/190431177-fb35990d-fd36-461f-aceb-1a9d8a215635.png)



### Challenges and Difficulties Encountered
I spent a lot of time trying to filter out months from the years/quarters.  Once I did that , I then moved on to filtering out which outcomes.  After exploring the table, I found that clicking on the Column Labels allowed removal of the Live outcomes. 

On the Outcomes Based on Goal charts, I learned that you can simply change the values and leave the rest of the formula alone.  I had to go back and correct some of the values and "><" characters to match the line graph image to the lesson. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

    Conclusion 1: The best time to launch a successful theater campaign is end of May and June.
    
    Conclusion 2: October and December had high rates of failed campaigns.  The best months to launch campaigns were in the summer from May - August. 

- What can you conclude about the Outcomes based on Goals?

    Conclusion 3:  Goals that were set with funds less than $4,999 or between $35,000 to $49,999 had the highest success percentages. 

    Conclusion 4: Goals that were set with a fund between $25,000 to $34,999 or more than $45,000 had the most failed perctages. 

- What are some limitations of this dataset?

    The data doesn't explain why funded goals between $4,999 and $35,000 were not as successful compared to those mentioned in conclusion 3. These were           on the two ends of the chart.  
    
    This analysis only compared outcomes for theater plays. 

- What are some other possible tables and/or graphs that we could create?

    We could create tables and graphs for other types of categories, i.e musicals.
    
    We could create tables comparing the campaigns in different countries. 
