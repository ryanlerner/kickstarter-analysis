# An Analysis of Kickstarter Campaigns
---
## Overview of Project
This project was created to help Louise launch a successful kickstarter campaign in order to fund her play, *Fever*. To ensure that Louise had well-informed expectations, this analysis worked with a set of data from over 4,000 unique kickstarter campaigns. These campaigns were focused on a variety of different categories, but a signficant number were also focused on theater and plays. The most crucial data for the purpose of this analysis was whether the outcome of each campaign was successful, failed, or canceled. 
---
### Purpose
Since Louise's campaign came close to its fundraising goal, this analysis sought to demonstrate how successful other campaigns were based on when they were launched, and how high each campaign's goal was. In order to determine the relationship between these sets of criteria, I used data from the "outcomes" column and the "goals" column. I also used data from the "launched_at" column to determine if there was a relationship between when a campaign was launched and whether that campaign was successful. By dividing the campaigns based on their outcomes, I was able to compare successful campaigns to failed and canceled campaigns to observe whether the goal and launch date had any impact on their outcomes. 
---
## Analysis and Challenges
---
### Analysis of Outcomes Based on Launch Date
To determine the relationship between outcomes and their launch dates, I only needed to pull data from when each campaign was launched and the outcome of each campaign. To view this in a more visually accessible way, I put this data in a pivot chart so that the columns displayed different outcomes and the rows separated these outcomes based on the month each campaign was launched. Since Louise was specifically focused on funding her play, I also used the filter option to limit the data to only theater campaigns. This pivot table also included a "Grand Total" column which calculated the sum of successful, failed and canceled theater campaigns per month. A line chart with the number of successful, failed, and canceled theater campaigns per month can be seen here: ![Theater_Outcomes_vs_Launch](resources/to/Theater_Outcomes_vs_Launch)

### Analysis of Outcomes Based on Goals

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?
--Outcomes based on launch date appears to show summer months as most successful, but that's also because there were more projects created in these months. 

- What are some other possible tables and/or graphs that we could create?
--To account for limitation A, we can create a line chart that calculates the percentage of successful campaigns rather than the number. 
