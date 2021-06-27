# Kickstarting with Excel

## **Overview of Project**
*Visualize campaign outcomes based on their launch dates and their funding goals.*

### **Purpose**
*To know how different campaigns fared in relation to their launch dates and their funding goals.*

## **Analysis and Challenges**

### *Analysis of Outcomes Based on Launch Date*

The best results obtained based on the launch date of the campaigns go from May to September, where from April onwards we started to see an upturn in the number of successful campaigns and it is in May where we reached the highest point of the whole year. 
From the fourth quarter onwards, the number of successful campaigns starts to plummet, being December the worst month to launch a new campaign, the percentage of success and failure is almost the same, that is, about 50% of the campaigns in that month fail and it seems that this negative behavior is transferred to the month of January, where we find the month with more cancellations of the year.

![Screenshot](Theater_Outcomes_vs_Launch.png)

### *Analysis of Outcomes Based on Goals*

Campaigns with a goal of less than 4999 have the best success rate, around 70% of the campaigns are successful, on the contrary, campaigns with a goal of more than 45000 have an average of 94% of the campaigns fail. 
In summary, following the trend of launching campaigns with a goal lower than 4999 gives us an average of 74% certainty that the campaign will be a success.

![Screenshot](Outcomes_vs_Goals.png)

### *Challenges and Difficulties Encountered*

It is necessary to work with the database prior to any analysis. In this case the category and subcategory were not found together and for our analysis it was necessary to identify only the parent category. 

It is necessary to be very careful when working with dates, to have the same format suitable for our analysis.

## **Results**

- What are two conclusions you can draw about the Outcomes based on Launch Date?

Q2 and Q3 are the best periods for launching theater campaigns, with May being the month with the best results.

Q4 is the period where we have more failed projects than successful ones, with December being the worst month to launch a new campaign.

- What can you conclude about the Outcomes based on Goals?

More positive outcomes are obtained in campaigns with goals<=4,999

- What are some limitations of this dataset?

Decision making is based on _only two_ variables, which could lead to leaving out information that could negatively affect the expected outcomes. 

- What are some other possible tables and/or graphs that we could create?

1. Table with the percentage of successes and failures campaigns with respect to the total:

   _The display of results in % helps to identify the points to be analyzed more quickly._

    ![Screenshot](Successful_Failed.png)

2. Table indicating the country where I should focus derived from the highest number of successful campaigns.