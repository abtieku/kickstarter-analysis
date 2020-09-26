# Kickstarting with Excel
## Overview
### Purpose
The purpose of this document is to assist Louise, an artistic fundraiser, in maximizing her fundraising goals. She raised funds for a play called _Fever_ which came close to its goal in a short amount of time. She wants to know how to maximize her future efforts and know what should she do, and what should she not do, in order to reach her goals. To do this, we will analyze trends that we see in a large dataset. 

I will perform an analysis on Kickstarter data to uncover how different campaigns fared in relation to their launch dates and fundraising goals. I will identify trends and provide guidance on what successful practices she should employ in the future. I will use visualizations to help with this. 

I will use the Kickstarter dataset. The dataset consists of:
- Plays (although it had other parent categories as well)
- Financial goals, amounts pledged, and whether the goals were met or not
- Countries
- Dates
- Number of backers
- Average donated

## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
For this, I did a pivot chart with theater in mind. It showed the months with number of successful, failed, and canceled campaigns.

Click the link to view a line chart depicting this:
![](./resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
For this, I used the COUNTIFS command which counts the number of cells in a range meeting certain criteria. It shows the percentage successful, failed and canceled campaigns. The criteria categories were the following (in dollars):
- Less than 1000
- 1000 to 4999
- 5000 to 9999
- 10000 to 14999
- 15000 to 19999
- 20000 to 24999
- 25000 to 29999
- 30000 to 34999
- 35000 to 39999
- 40000 to 44999
- 45000 to 49999
- Greater than 50000

Click the link to view a line chart depicting this:
![](./resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
I had challenges with pictures: getting them to show, cropping them, and getting the links to work. 

## Results
**What are two conclusions you can draw about the Outcomes based on Launch Date?**
The months in which she should do fundraising should be May and October. She should avoid the Christmas holiday season.

**What can you conclude about the Outcomes based on Goals?**
Louise will be more successful if she asks for small amounts of money from lots of people. She should avoid asking for larger amounts of money.

**What are some limitations of this dataset?**
It does not tell the entire story. For example, it did not break down the givers: Were they individuals or organizations? If individuals, what were the demographics? If organizations, what type were they? Also, what type of fundraising campaigns were used: Did they use social media, print, TV, or something else? How much money was spent on fundraising?

**What are some other possible tables and/or graphs that we could create?**
We could see how other countries are doing, or we could explore different parent categories, such as:
- Film and video
- Music
- Photography


