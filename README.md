# Kickstarting with Excel

## Overview of Project

### Purpose

Lousie, a rising playwriter, is looking to raise $10,000 in order to create her play Fever. Ahead of her crowdfunding endevour, she would like to get previous crowdfunding projects analyzed in order to better understand what makes crowdfunding projects successful. 

The data for 4113 crowdfunding projects were collected and given for analysis. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

### Analysis of Outcomes Based on Goals

### Challenges and Difficulties Encountered

While creating the Analysis of Outcomes Based on Goals sheet, there was an error in my formulas that was resulting in erroneous results. After unsuccessfully trying to find the error, I decided to start from the begining and verify I was getting the right information in every step. Originally I had started the COUNTIFS formula by specifying the Goal ranges, which made the formula visually difficult to debug. When I started from scratch, I began by filtering the subcategory column first by "plays". Since that filter was needed in all the cells, copied the formula to all the cells. Then I applied the column filtering of successful, failed and canceled to the respectives cells in the columns. Only at the end I applied the row filtering of ranges in the COUNTIFS formula.

By adding one filter at a time and going from the most encompasing category to the more specific category, I was able to ensure that there were no typos in the earlier part of the formula. This allowed me to validate my data step by step. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
