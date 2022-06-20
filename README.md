# Kickstarting with Excel

## Overview of Project
This project is a collection of data regarding a large variety of kickstarter projects.

### Purpose
The purpose of this analysis was to find a pattern in the success of certain types of kickstarters based on their launch and goal. 

## Analysis and Challenges
I first organized the data in the kickstart sheet into sections and orders that were more readable and easier to work with. 

### Analysis of Outcomes Based on Launch Date
The analysis of the outcomes based on luanch dates was primarily preformed by creating a pivot table to section of the necessary data to analize in issolation. 
Then I formed a line graph of the data in order to properly visualize patterns that the data indicated. 
The greatest challenge of this section was organizing the pivote table in a way to make the data clear, but I was able to achieve this by using only the months of the aquired dates to show a more accurate timeline of the outcomes. 

### Analysis of Outcomes Based on Goals
The outcomes based on goals analysis was much more challenging, due to the more compolicated processes of "countif()" statements. The main challenge in these was adding in all of the correct criteria to get the desired outcome. 
I was able to overcome this challenge through a very slow and methodical writing of every step of the "countif()" statement. Starting with "=COUNTIFS(Kickstarter!$F:$F,"=successful",Kickstarter!$R:$R,"=plays",Kickstarter!$D:$D,"<1000")", and building from there to get the rest of the data chart filled out. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. Kickstarts launched in May have a much higher success rate; possibly due to the start of summer. 
2. There doesn't seem to be any greater risk of cancelation between launch dates across the year. 

- What can you conclude about the Outcomes based on Goals?
1. For the most part, the lower goals have a higher chance of success.

- What are some limitations of this dataset?
1.This data is limited by it's lack of sufficiant data on advertising of these kickstarters. Such as advertising budget, trailers released to build popularity, endorsments, etc. 

- What are some other possible tables and/or graphs that we could create?
1. An interesting table to go through with this data could be the highest average donation by country, to better undestand some ways to have your kickstart succeed. 
