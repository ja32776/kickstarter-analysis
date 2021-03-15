# Kickstarting with Excel

## Overview of Project

Louise’s play Fever came close to its fundraising goal in a short amount of time. Now, she wants to know how different campaigns fared in relation to their launch dates and their funding goals. Using the Kickstarter dataset that you’ve already combed through, you’ll visualize campaign outcomes based on their launch dates and their funding goals. You’ll then submit a written report based on your analysis and the visualizations you create.

### Purpose
The purpose of this Project is to Identify, Summarize, and Visualize trends in the Kickstarter File. 

## Analysis and Challenges
The 2 analysis were produced by following the instructions provided on Canvas. 


### Analysis of Outcomes Based on Launch Date
 
Constructed a Pivot Table to analyze the Success/Failure data and graphed a Stacked Line Chart. Pivot Table was organized by Month, can be filtered by Years and Categories.

### Analysis of Outcomes Based on Goals

Constructed a Table via COUNTIF() statements to analyze the Success/Failure Proportions of Subcategory 'Plays'. Table was organized to reflect several ranges of Kickstarter goals. 


### Challenges and Difficulties Encountered

It was a challenge getting the "COUNTIF" formulas correct. Simple things like  (<45000) vs. (<=45000) make a difference. Also, trying to work more efficiently (i.e,  dragging the Bottom-Right corner of  the cell to replicate the Formula to the rest of the cells in that column/row), can cause problems if you aren't careful with the Cells (Some cells need to be locked, other cells need to be left open to change. Sometimes the Column needs to be locked, while the Row is free, etc.  ) ; Example: =D7/$E7.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

1.There was a steady rise in Successful kickstarters between January and June (peaking around 11), 

2. There was a sharp drop after June ; no Month exceeding 5 successful Kickstarters for the rest of the year. 

- What can you conclude about the Outcomes based on Goals?

1. The kickstarters with Lower goals had a good success rate (80%), then there was a steady decline to a 20% success rate For the kickstarters that had $25000 to $29999 as a goal. 

2. The success rate then went back up to about 65% for fundraising raising $35000 to $44999 , followed by another sharp decline.

- What are some limitations of this dataset?

The dataset could contain more information. We could perhaps keep track of the donations of each Backer. We know that the pledged / Backer gives us the average donation for each Kickstarter, but it'd be interesting to derive other stats like the Minimum /Maximum donation of a Backer, etc. 

- What are some other possible tables and/or graphs that we could create?

1. A stacked Column chart (and a 100% Stacked Column Chart) could help visualize the proportions of Success/Failed/Canceled kickstarters
2. An Analysis on whether or not there is a correlation between length of description provided in 'blurb' column v. Pledged amount. Did more descriptive 'blurbs' effect pledged amount?
3. Did Length of time between Date Created vs. Date Ended effect Pledged amount?
