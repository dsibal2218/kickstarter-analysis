# Kickstarting with Excel

## Overview of Project
This project requires the utilization of different excel features in analyzing and providing result visualization of the kickstarter dataset.

### Purpose
Using excel, we will help Louise, a play writer who organized the Fever play fundraising, find out how different campaigns fared in relations to their launch dates and funding goals. 

## Analysis and Data details
The dataset included 4114 kickstarter campaigns from 21 countries with launch dates timeframe spanning from 2009 to 2017. There were 41 different categories/subcategories. For the analysis, the dataset had to be combed through, reformat any field that needed to be reformatted (e.g. date reformatting), and additional information had to be manually added using formulas (e.g. dividing categories/subcategories field). In the dataset, we were able to identify 1369 theater related campaigns, of which about 1047 were plays (not including the live or ongoing campaigns). After identification of the category and subcategories, we were able to create a line graphs of theater outcome based on launch date and play outcomes based on goal amounts.   

### Analysis of Outcomes Based on Launch Date

 ![image](https://user-images.githubusercontent.com/98235755/155796348-fab2e91b-6f65-4965-a437-7692724d3d2d.png)

The result of the outcome based on launch date seems to be showing some seasonality. May-Jul being the months with the most theater kickstarters launched, with May having the most successful theater Kickstarter and had the least amount of failure rate (31% of total launched). Additionally, Nov and Dec had the least amount of kickstarter campaigns launched with December having almost the same amount of successful and failed launched kickstarter campaigns. 

### Analysis of Outcomes Based on Goals

![image](https://user-images.githubusercontent.com/98235755/155796406-4dd118be-58e1-47c7-a3e1-dab73218ec50.png)

The analysis on the outcome based on goals shows that kickstarters with goal of less than $1,000 had the most success, while those with goals of $45,000 to $50,000 had 100% failure rate. 


### Challenges, Data limitations and Difficulties Encountered
Even though we had a little over 1000 samples in the dataset for theater/play campaigns, we can't say for sure that we had enough sample details to formulate decisions that will 100% result to success. The dataset doesn't include information on other factors that could be contributing to some of campaign results such as specific location (e.g. city, rural, venue), genre, and marketing (e.g. how long did they market for it before launch, effectiveness of it) that should also be looked into. 

Other graphs that could be used to represent the results of the analyses could be a stacked column/bar graph especially to show the percentages of failed and successful plays. In that graph, I would also add a secondary axis showing the total amount of plays. When just looking at the graph, one would easily conclude that those campaigns with 45,000-50,000 goal are for sure to fail, but in reality, there was only 1 campaign in that range in our dataset. 
