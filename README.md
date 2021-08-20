![github-small](https://github.com/MonaElahi/Kickstarter-Analysis/blob/8ecde83463804a847b9fd14715cd70c4513d6ea7/Ms%20Excel%20Solution%20by%20Yittbox.jpg)



# Kickstarter-Analysis
First module Kickstarter

# Kickstarting with Excel
Kickstarter with Excel module 1. Excel is a useful tool to sort and arrange large data in order to pull relevant information. Built-in Arithmetic operations help to calculate data. Variety of built in FUNCTIONS are predefined_ FORMULAS _which save time as our own calculation takes many steps to produce results. There are many features to organise data for example Filter can pull required data in no time,  it can be arranged to make tables, which are easily readable and can be transformed into a variety of graphical images.         


## Overview of Project
Crowdfunding data contain information of fundraiser campaigns for various countries in different categories and how they have performed. It will be reorganized by using excel to extract useful information which will be helpful in decision making.Louise is a play writer and wishes to start production for her new play called fever. Her budget is 10k dollars, she wishes to analyze fundraising campaigns through crowdfunding data in order to understand whether there are some factors which can aid her launch a successful campaign. 

### Purpose

The purpose of this project is to analyze the outcomes of the fundraising event according to the launch date and funding goals. To observe the behavior of the outcomes according to the required conditions. To figure out the challenges and difficulties encountered throughout the analysis of the dataset.

## Analysis and Challenges
Outcomes Based on Launch Date:
In parent category theater, its performance is reviewed according to its launch date. Number of projects in the theater category and their outcomes as per launch date will be analyzed.
**Challenges: **
1. Learn how to apply filters to pull relevant data. 
2. Separate parent category from a master category.
3. Change unix date into human readable format. 
4. use of pivot tables to pull relevant data for analysis.
5. Transfer table into line chart to see performance. 

![github-small](https://github.com/MonaElahi/Kickstarter-Analysis/blob/b5aaeaa361de91a69f708b26ff9b8e495b1396ea/Theater_Outcomes_vs_Launch.png)




Outcomes Based on Goals:
In Subcategory "Plays" performance will be reviewed according to goal range.
Goals will be sorted into ranges, also total number of plays and their outcomes; successful, failed and cancelled. Later outcomes will be converted into percentages.

**Challenges:**
1. Manually range the goals
2. Separate sub category from main category.
3. apply filters to pull plays in subcategory and number of outcomes.
4. Use Countifs to pull outcomes data from the kickstarter sheet. 
5. Make a column of the total project.  
6. Calculate percentages of outcomes.
7. From table Outcomes by goal, insert line chart. 


![github-small](https://github.com/MonaElahi/Kickstarter-Analysis/blob/b5aaeaa361de91a69f708b26ff9b8e495b1396ea/Outcomes_vs_Goals.png)


### Analysis of Outcomes Based on Launch Date

The campaigns launched during the middle of the year from April to September performed better than the campaigns launched beginning and end of the year.
The campaigns launched during the mid of the year are most likely to be successful due to good environment, moderate weather conditions & a large number of human interactions.  



### Analysis of Outcomes Based on Goals
The outcomes based on goals shows an abnormal behavior. In the beginning, we had a high rate of successful outcomes when the goals were low. With the increase in goals, the rate of successful outcomes also decreases gradually. In the middle, the success rate starts increasing and then just decreases to a high extent in the higher goals. The behavior of percentage failure is vice versa.
The rate of cancellation is minimal as compared to the rate of success and failures.


### Challenges and Difficulties Encountered
While preparing analysis there were a couple of challenges.
1. Using the COUNTIFS function was a little exhausting as in every field you have to change formulas.
first change columns and then change goals. The first and last field formula is different as the goals column holds just one value.
2. Since it was asked to prepare a canceled column and use it for analysis. It took ample time to figure out that there is "none canceled" in plays. As when filters were applied, while by selecting subcategory canceled wouldn't show and vice versa.    

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

1. Louise should consider launching her campaign in the month of May. As per the analysis, the highest number of successful outcomes are in the month of May. 

2. December shouldn't be considered to launch a campaign as it is the slowest month of all.


- What can you conclude about the Outcomes based on Goals?

1. Most successful goal range is <1000 and the Successful percentage is 76%.
2. Goal range between 1000-4999 also falls behind the most successful range with a percentage of 73%
3. Interestingly we have an inverse graph where two variables (Successful% and Failed%) outcomes are exactly opposite.

- What are some limitations of this dataset?
One of the limitations in this dataset is that we don't have any information regarding the reason for cancellation of any campaign. Other than that, We also don't have the reasons behind the failure of any campaign. These data columns can improve the number of successful outcomes due to an effective change in the analysis of the dataset.

- What are some other possible tables and/or graphs that we could create?
Highly recommended to also consider how campaigns performed in different countries. To review we need the following.
Pivot table data columns:
Country, outcomes and subcategory_ _"plays"__ should be selected from kickstarter for consideration.
**Chart:**
Use of filters in charts can help to see most active countries where campaigns are successful.
**Findings:**
1. USA and Great Britain are the most active and favourable countries to launch campaigns 
2. For subcategory _"PLays"_ outcomes are better in Great Britain as compared to the USA.

![github-small](https://github.com/MonaElahi/Kickstarter-Analysis/blob/b5aaeaa361de91a69f708b26ff9b8e495b1396ea/Country%20Outcome.png)





![github-small](https://github.com/MonaElahi/Kickstarter-Analysis/blob/b5aaeaa361de91a69f708b26ff9b8e495b1396ea/Outcomes%20based%20on%20launch%20date.png)




