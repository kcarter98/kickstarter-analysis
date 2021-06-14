# Kickstarting with Excel

## Overview of Project

This dataset includes kickstarter projects and how they fared in their journey. The goal is to help compare the success of a campaign for a play called *Fever* with its peers. It provides project data, such as goal amount, start and end times of the campaign, category, and the overall outcome.

### Purpose

The purpose of this project is to provide insights on how kickstarter projects fared based ont their goal amount and launch date. It also specifically provides insight on campaigns in the theater category, and also in the plays sub-category.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

In this analysis, I created a pivot table for the kickstarter data with the additional year column based on the launch date. In this pivot table, I filtered the projects that only include a parent category based on theater, separated the data based on month of launch, and analyzed how many successful, failed, and canceled campaigns in each month. Lastly, I created a line chart with markers at each month to show trends over the year, and this chart can be pictured below.

![Image1](/resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals

Here I looked into the relation of goal amount set by a campaign to its outcome. A chart was created using the countifs function to count all outcomes in set goal ranges of campaigns within the plays subcategory. Then, percentages were analyzed to look at the total share of outcomes within each goal range. Lastly, a line chart was created to show the percentage of each outcome compared to the total cmapaigns in the set of goals.

![Image2](/resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

Here there were not much challenges encountered, as the data was pretty clean to start. The only difficulties I had were converting timestamps into readable dates.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

1. More successful campaigns are started in May than any other month. Additionally, you can also take into perspective the count of successful campaigns compared to total campaigns in which case May would still be the best at almost 67% of campaigns completing their goal. If you were to start a kickstarter campaign for a theater project, your will have better chances of it being a success with these parameters.
2. Consistently, theater campaigns on kickstarter were successful more than they failed if you don't consider the canceled ones as failures, which this dataset does not. This shows that if you need money for a theater project, then kickstarter might be a good option for you.

- What can you conclude about the Outcomes based on Goals?

The trend shows that campaigns are far more successful when the goal is set lower, although there is a slight increase in successful campaigns around 45000 this is probably due to too little samples as only plays were analyzed. This is probably pointing to the idea that if a campaign wants to be successful they need to focus on setting realistic and attainable goals.

- What are some limitations of this dataset?

This dataset only considers projects that had funds raised on kickstarter, there are multiple online sites that could be used for this same purpose that were not considered.

- What are some other possible tables and/or graphs that we could create?

For the analysis of outcomes based on launch date, I believe a stacked bar chart could have helped. This is because it wouls be helpful to look at a percentage of total. For instance, what month are campaigns most and least successful? Only have counts would not be sufficient in this case because differnet months have different total campaigns started.

