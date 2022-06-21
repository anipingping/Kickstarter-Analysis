# An Analysis of Kickstarter Campaigns
## This is an analysis of Kickstarter data to uncover trends and relationships between fundraising goals, funds pledged and outcomes.
### Purpose
The purpose of this analysis was to uncover trends and relationships between the type of activity (in this instance, plays), the fundraising goal of each activity, the amount of funds pledged and the outcomes for the various activities. 
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
There is a clear relationship between the success of a theater activity and a launch date in May, June, and to a lesser extent July and August. In short, the late spring and summer months are the time to launch a theater production! There was not much of an association or relationship between failed productions and time of year. The number of failed theater activities was mostly consistent throughout the year.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/106618404/174894164-60a2f940-825e-429e-b659-b9fa8760a790.PNG)
### Analysis of Outcomes Based on Goals
Successful play/theater activities tend to be those that have a modest fundraising goal, roughly $20,000 or less. There are some successful plays with larger fundraising goals, but overall the trend I observed indicated that a modest fundraising goal was associated with success. As a specific example, almost 80 percent of theater/play activities that had a fundraising goal of less than $1,000 were successful. On the other hand, plays/theater activities with a very large fundraising goal of $40,000 or more seemed like they were more likely to fail. This pattern is very clear in the table below, where the percentage of failed activities spikes dramatically above to a rate above 80 percent. 
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/106618404/174894343-7aca1554-fa44-4f87-9f2c-2bb40969abc8.PNG)
### Challenges and Difficulties Encountered
Not all of the formulas in the module instructions worked for me. I encountered a serious challenge when trying to execute the =countifs('Kickstarter'!,...) formulas in the Outcomes Based on Goals worksheet. In order to get around my failure to successfully execute the formula commands I created a new column in the main dataset with the categories that aligned with the specific dollar value goal of each entry. I then utilized the filters to find the exact count of outcomes by each goal category (Less Than 1000, 1000 to 4999, etc.). This workaround enabled me to gather the required data for deliverable 2. You can see this extra column in the main kickstarter worksheet.
## Results
*What are two conclusions you can draw about the Outcomes based on Launch Date?*
1. It is important to launch your proposed theater/play activity in the late spring or early summer. This is probably because people are out of school, people are taking more time for vacation, the days are longer so any outdoor plays can operate further into the night. Furthermore, a launch date in May gives you the whole summer and into the fall for a run that lasts a long time and thereby makes more money.
2. More data is needed to understand how launch date affects canceled or failed shows. The numbers are too flat to really highlight an interesting pattern.

*What can you conclude about the Outcomes based on Goals?*

Based on the dataset we have here, it seems pretty clear that there is a strong association between the success of a play/theater activity and a modest fundraising goal.

*What are some limitations of this dataset?*

I think this dataset could be strengthened if we knew more about the company or organization running the operation. I don't think I saw that data in this file. I think this data needs more information about the facility where the activity occurred, cost of tickets, the number of people who attended the event. If available, this type of data, which is quantitative data and would lend itself to analysis in Excel, would really strengthen this dataset.

*What are some other possible tables and/or graphs that we could create?*

I kind of addressed this in the previous section, but more information about the parent company, the number of staff involved, the number of months that a marketing campaign ran, the social media platforms that were used for the marketing campaign, maybe the specific cities where the activity occurred. I know there is a column called "blurb" but that data is formatted as long blocks of text that will require more manipulation to effectively categorize and tabulate for a pivot table. Perhaps a separate column called "company" would be better? 

Additionally, there is information on countries, but I think that some information about CITIES could provide even more detail. Is New York a better place to launch a theater production than Houston? Is Paris a better place to launch a theater production than New York? That would be interesting data to assess.
