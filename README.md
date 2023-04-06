# Data Visualization Project

## Data

The data I propose to visualize for my project is from the 2021-2022 Premier League Season. Each row in the dataset represents a instance of a certain matchweek for a team. The row contains the team, matchweek, points (accumulated up to that matchweek), expected points (accumulated up to that matchweek), and where in the PL table the team would be if it was based on the expected points. The data was scraped from understat.com. The focus of this project will be to compare a team's results to what their expected results to see if any teams were "lucky" or "unlucky".

## Design Process (Prototypes & Sketches)

I’ve created a series of proof of concept visualizations of this data. I started with a couple iterations of sketches:
(describe each sketch - how is the data visualized, what are the interactions, and how do these relate to the questions/tasks)
![image](https://github.com/Diz138/PL-2021-2022-xPvsPoints/blob/master/images/sketch_iteration1.png)
I started with the idea to focus on one team at a time as it would become too distracting with all 20 PL teams on one graph. From here I know I can compare both xP and Points using the same axis as they represent the same value. There is the option to change teams from a drop down and the final points and xP total will be displayed in a table on the graph. The biggest question a viewer of this visual would be to see if the team overperformed or underperformed and when. This will be determined when there is a big differnce in values of Points and xP. 
![image](https://github.com/Diz138/PL-2021-2022-xPvsPoints/blob/master/images/sketch_iteration2.png)
On my second iteration I noticed that I was using the two channels (color and line type) to represent the same value, so I instead thought of the idea of using color to highlight the portions of the season in which there was a a big difference in xP and Points. 
[![image](https://github.com/Diz138/PL-2021-2022-xPvsPoints/blob/master/images/LineChartwithLogos.png)](https://vizhub.com/Diz138/3ec5b64a2ef94d32a922ecd4445d9089)
This is my current implementation of my sketches. I just added the x and y axes and am hoping to change the scatterplot to a line/scatterplot in the coming days.

## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * Which Premier League teams overperformed or underperformed during the 2021-2022 season?
 * During which periods did teams overperform or underperform?
 * What patterns do different teams have in terms of performance?
 * Does the final PL table represent the best teams according to xP?


## Open Questions

I also want to include an animation of each team and their table position over each Matchweek. This would be an entirely different plot, but using the same data. I do not know if I have time for this. In my schedule I am putting time to it, but I do not really have an estimate as to how hard creating my first viz will be so I am trying to be optimistic.

## Milestones

Week 7 - Modify line type and scrape more data for future interactions

Week 8 - Add interactive dropdown button for each PL team

Week 9 - Add table in graph for each PL team

Week 10 - Modify background and margins to make visualiztion look pretty and finalize

Week 11 - Team interaction for each dot to see who was the team's opponent that matchweek

Week 12 - Axes, scatter/lineplot, color of 2nd viz

Week 13 - Animation of 2nd viz

Week 14 - Finalize visualizations
