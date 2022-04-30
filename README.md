# Analysis of Kickstarter Campaigns
## Crowdfunding Analysis plays and general success of campaigns for Louise; charts and descriptive statistics of specific campaigns and those related to her goals
---
## Overview of Project
#### The purpose of this analysis is to aid Louise in creating a successful campaign to fund her attempt as a new playwright. She is nervous about making sure she can secure funds for a $10,000+ production and wants to use data and charts to make sure she has the best chance to be successful. This analysis contains 4,114 campaigns on Kickstarter from 2009 - 2017, including goal, success, location, and category/theme of each campaign.  There are many constraints to maintain what she wants such as the country, the category and subcategory of the campaign, and minimum goal she needs to ask for her play.  To be most helpful to Louise, charts are included to help determine the best time of year to start the campaign, exactly how much money to ask for, and how much to expect from each donation to advertise her effort to a willing audience. 
---
## Analysis and Challenges
 First, the Kickstarter data needed to be amended to include readable dates and separate the categories and subcategories of the campaigns so that  plays could be studied specifically. We color coded whether each campaign succeeded, failed or was canceled and added a color scale to easily visualize how successful each campaign was by the percent of expected funding received. 
<img width="1000" alt="kickstarter_new_columns" src="https://user-images.githubusercontent.com/103595718/165821518-b681f8ac-89d3-4dd6-9087-53d264de5f1a.png">

 From these additions, charts were created to show an overall comparison of plays to other categories - there were many more plays and theater related campaigns than any other type. Music was another successful category; additional analysis could be done on this category to understand why, or to compare successful categories to others that usually failed. 

![Categories](https://user-images.githubusercontent.com/103595718/165827620-b36a39ea-a801-4ce4-a2ac-d29fb527a685.png)
![Subcat](https://user-images.githubusercontent.com/103595718/165828133-0bbb8af0-73bf-43ef-9c8c-addfe3fabe23.png)

 After the overall analysis of categories, the focus of the study was shifted to only examine plays. Descriptive statistics were determined to compare successful and failed plays. I tried to determine the outliers of the data, both pledged and goal amounts, but had difficulty figuring out the best mothod to do so. The standard deviation seemed very high for the data. It was said the IQR rule is usually better to use, but the minimums were all negative numbers, which is not applicable for money. I presume that means campaigns that had very low goals or even raised $0 would still be reasonable data to keep. Using the IQR rule, I color coded the (upper) outliers on the successful and failed outcome sheets. Without much more analysis and time, I do not know how this data would be useful for Louise. The statistics state that the goals of $10,000 or higher should be outliers, however, Louise needs to raise more than $10,000 to make her play possible. I also could not determine how to exclude those outliers from the descriptive statistics to see the difference. 
<img width="396" alt="Descriptive_Stats" src="https://user-images.githubusercontent.com/103595718/166118555-2c856661-ca42-4306-821c-594b7fd88b18.png">
<img width="569" alt="Successful_Outliers" src="https://user-images.githubusercontent.com/103595718/166118559-3a9c0d0a-9138-4ac2-9ee8-3aa9cdba6e48.png">

---

## Results
 The pivot table and chart of the Launch Dates show a pattern that launching campaigns from May to July are usually more successful. Limitations of this visualization, though, are that there were very few plays from 2009-2013 and 2017, so it would make more sense to limit the campaign years in the entire analysis.  
 ![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/103595718/166119513-ebed0325-ae44-4508-aca7-f0fd47d00f4a.png)

The most successful campaigns asked for less than $5,000 total. Asking over $20,000 resulted in more failed campaigns than successful; so Louise should be mindful when determining exactly how much she needs to ask for. Perhaps two smaller campaigns would be better for her overall outcomes if that is possible. I presume that asking enough friends, family, or social media followers to reach a goal is difficult. I furthered my analysis to determine the minimum amount of donations she should ask for. I had difficulty viewing the data as a whole to determine the categories I should use and rather used groupings that I thought would be more common in campaigns (i.e. political campaigns stating that every $5 donation matters, etc.). This may have produced more helpful data if I limited the campaigns from $5,000-$10,000. However, with the spread of goals for plays ranging from $1 to $200,000, she has a greater chance of asking for donations above $30. Donations from $75 to $300 were most successful. With donations this high, it would not require many supporters to reach lower goals. Out of >900 plays total, 374 plays asked for less than $2,000 while only 113 asked for over $10,000. This shows that her original goal may not be as feasible as she hoped for. 
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/103595718/166119947-5f0aac3b-ccf0-43a8-a944-b4a2dfa4d412.png)

![Outcomes_donation](https://user-images.githubusercontent.com/103595718/166119949-5d06046e-f92a-4a83-9fe5-06658416dd24.png)
Other limitations for this data include the inability to see who is starting these campaigns. Are the promoted by individuals or (theater) companies? Are there incentives for donating over a certain amount, as common in many Kickstarter campaigns. Also, the average donation column is likely unreliable as many campaigns have a few very large donations and most smaller amounts. I did not complete much analysis on other categories. It is easy to determine through filtering that music and plays are more successful than other categories; what is the determining factor for making those successful? 

More analysis should be conducted on other categories and through limiting the launch dates, i.e. combining the sheets and charts completed in this analysis. It may also be useful to limit the type of play and if spotlighting the campaign had any impact on overall success. We could also analyze the descriptions of each play campaign to determine if there are key verbs, length, impactful phrases, etc. that render more attention for support. 

---




