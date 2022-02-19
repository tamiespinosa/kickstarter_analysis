# Kickstarting with Excel

## Overview of Project

### Purpose

Lousie, a rising playwriter, is looking to raise $10,000 in order to create her play Fever. Ahead of her crowdfunding endevour, she would like to get previous crowdfunding projects analyzed in order to better understand what makes crowdfunding projects successful. 

This repository contains the analysis of 4113 crowdfunding projects. Excel was used to interpret the gathered data. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

<img src="Theater_Outcomes_vs_Launch.png" width="70%" object-position= center alt="Theater_Outcomes_vs_Launch">

### Analysis of Outcomes Based on Goals

The criteria used to determine whether a project succeded or failed was solely if the pledged  money matched or exceeded the goal. Therefore, projects with more modest goals tend to be be more successful. Of the 1047 kickstarter projects for plays, 720 (69%) of them had a goal to raise under $5000. Projects with goals of less than $1000 had 76% of success and projects between $1000 and $4999 had 72% of success.  

Between $5000 and $15000 the rate of success dropped to around 55%. Yet, of the 117 kickstarter failed play projects in this range, 26% of them raised $1000 or more and would've been succesful if the goal was less. Between $15000 and $25000 the rate of failure increases, 

It is worth mentioning that once the goal amounts exceed $25,000 the sample size becomes small and therefore the percentage of succesful and failed kikstarter projects are more affected by a single project. The trend becomes more erratic. 

<img src="Outcomes_vs_Goals.png" width="70%" object-position= center alt="Outcomes_vs_Goals">

### Challenges and Difficulties Encountered

The COUNTIFS formula used in the Outcomes Based on Goals sheet gave me erroneous numbers due to a typo. I used the "Show Formulas" button under the Formula Tab to be able to see the formulas in the table, and try to spot the typo there. 

After unsuccessfully trying to find the error, I decided to start from g and verify I was getting the right information in every step. Originally I had started the COUNTIFS formula by specifying the Goal ranges, which made the formula visually difficult to debug. When I started from scratch, I began by filtering the subcategory column first by "plays". Since that filter was needed in all the cells, copied the formula to all the cells. Then I applied the column filtering of successful, failed and canceled to the respectives cells in the columns. Only at the end I applied the row filtering of ranges in the COUNTIFS formula.

By adding one filter at a time and going from the most encompasing category to the more specific category, I was able to ensure that there were no typos in the earlier part of the formula. This allowed me to validate my data step by step. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?



- What can you conclude about the Outcomes based on Goals?



 If Louis' budget was less than $5000, the chance of her kickstarter to meet her goal would be greater. 



Because not all the play kickstarter projects are being carried in the US, some of the goal and pledged numbers are not measured in USD. Of the 1047 projects, 662 (63%) are measured in USD. The remaining projects are measured in 11 different currencies. If the data is not being measured in the same units, then some of the data points might actually fall under different ranges which might be impact the percentages being shown in the graph. For example Mexican pesos, as of Feb 2022, are worth 20 times less than a USD. Not to mention, culturally plays might be more or less important in certain countries therefore impacting the rate of success. To improve the accuracy of the graph, only US project should be taken into consideration or all of the data should be converted to one currency. 

- What are some limitations of this dataset?



- What are some other possible tables and/or graphs that we could create?
