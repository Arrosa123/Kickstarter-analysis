# Kickstarter-analysis
Performing analysis on Kickstarter data to uncover trends
# Kickstarting with Excel

## Overview of Project
In this project, use Kickstarter data to uncover trends relating to campaigns launch dates and goals within the "plays" subcategory. 
### Purpose
The purpose of this project is to analysis of Kickstarter campaigns for various theater plays conducted to determine whether the lenght of a kickstarter campaign contributes to its ultimate success or failure.
## Analysis and Challenges
This project analysis has two main deliverables.  
### Analysis of Outcomes Based on Launch Date
This analysis looked at the outcomes of the parent category"theater" campaigns which the subcategory "plays" is apart of it and based on the each month. I craeted a pivot table by using all of the data from the Kickstarter, and launch date of of each campaign and the outcome of those campaigns. I used "parent category" and "years" as filtes, the "outcomes" as values and columns, and the "launch date" as rows.After setup my pivot table, I created a line chart to visualize the relationship between outcomes and launch month. See chart below.
![image](https://user-images.githubusercontent.com/96403349/147900694-44032aa3-c01a-4b8c-9a26-0d63adcaf55f.png)

### Analysis of Outcomes Based on Goals
This analysis looked at the outcomes of the subcategory "plays" campaigns based on the amount goals. I used the COUNTIFS() function to find the number of succesful, failed, and canceled campaigns with different dollar-amount ranges. I found the total amount of campaigns by using the SUM() formula. Then I calculated the percentages of all success, failed, and canceled campaigns per dollar-amount range. After that, I created line chart to visualize the relationship between the goal-amount ranges on the x-axis and the percentage of successful, failed, or canceled projects on the y-axis. See chart below.
![image](https://user-images.githubusercontent.com/96403349/147901151-14cc2eae-4af5-4bc7-8ed9-f61739c4c668.png)

### Challenges and Difficulties Encountered
For the challenges making sure that the charts had the right lables on the axis and making sure that COUNTIF() included "plays" campaigns, and the pivot table rows were months and not individual dates. 
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
The first conclusion from the data analysis of the outcomes based on Launch Date, is observed that the most of the successful campaigns were launched in the months of May and June. The second conclusion is november and December were the worst months of the year.
- What can you conclude about the Outcomes based on Goals?
- The conclusion from the data analysis of the outcomes based on goals, is observed that the lower amount of the compaign goal higher the chance of success. Most of the successful campaigns have the goal amount less than $5000.
- What are some limitations of this dataset?
- One of the important limition is the data set size. For the outcomes based on Launch date, I only looked at the campaigns in the "Theater" subcategory and successful, failed, and canceled campaigns. It also would be helpful to compare that information to all campaigns on kickstarter. And we can show if kickstarter is a good place to raise money for theater.  
- What are some other possible tables and/or graphs that we could create?
Other possible tables/charts would include some other categories and we can include the columns like backer's to share profit making successful campaigns. 
