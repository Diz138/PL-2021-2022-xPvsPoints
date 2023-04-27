# Data Visualization Project

## Data

The data I propose to visualize for my project is from the 2021-2022 Premier League Season. Each row in the dataset represents a instance of a certain matchweek for a team. The row contains the team, matchweek, points (accumulated up to that matchweek), expected points (accumulated up to that matchweek), and where in the PL table the team would be if it was based on the expected points. The data was scraped from understat.com. The focus of this project will be to compare a team's results to what their expected results to see if any teams were "lucky" or "unlucky".

## Initial Sketches

I created a series of proof of concept visualizations of this data. I started with a couple iterations of sketches:
![image](https://github.com/Diz138/PL-2021-2022-xPvsPoints/blob/master/images/sketch_iteration1.png)<br />
It began with the idea to focus on one team at a time as it would become too distracting with all 20 PL teams on one graph. From here I know I can compare both xP and Points using the same axis as they represent the same value. There is the option to change teams from a drop-down and the final points and xP total will be displayed in a table on the graph. The biggest question for a viewer of this visual would be to see if the team overperformed or underperformed and when. This will be determined when there is a big difference in the values of Points and xP. 
![image](https://github.com/Diz138/PL-2021-2022-xPvsPoints/blob/master/images/sketch_iteration2.png)
On my second iteration, I noticed that I was using the two channels (color and line type) to represent the same value, so I instead thought of the idea of using color to highlight the portions of the season in which there was a big difference in xP and Points. 
## Prototypes
After a couple iterations of my design, it was now time for me to start. I first just plotted one teams (Arsenal) data over the course of the season.
[![image](https://github.com/Diz138/PL-2021-2022-xPvsPoints/blob/master/images/initialArsenalPlot.png)](https://vizhub.com/Diz138/bc89b191a0a845f6aaba0abc06cd5e00)
After this, I then plotted Arsenal's xP and Points data. This plot included axes.
[![image](https://github.com/Diz138/PL-2021-2022-xPvsPoints/blob/master/images/secondIteration.png)](https://vizhub.com/Diz138/a4e0f29cf06d49b2bcb1574e61dde22e)
The next step after I completed plotting both xP and Points data was to add a way for users to change between which teams they view. I just added the dropdown functionality and no interaction.
[![image](https://github.com/Diz138/PL-2021-2022-xPvsPoints/blob/master/images/thirdIteration.png)](https://vizhub.com/Diz138/511122bd5c154a24840e3d034febd282)
After this I was able to add interaction to this and place the button above the plot.
[![image](https://github.com/Diz138/PL-2021-2022-xPvsPoints/blob/master/images/fourthIteration.png)](https://vizhub.com/Diz138/3ed0f744eab74924b87b8b5615011309)
The issue with this dropdown is that it causes sizing errors when clicked (more than 1 team is shown as an option) so I thought including the logos as buttons would be a cooler viz instead.
[![image](https://github.com/Diz138/PL-2021-2022-xPvsPoints/blob/master/images/LineChartwithLogos.png)](https://vizhub.com/Diz138/db634275642f4c4d9498ac4f9780e5a8)
This is my current implementation of my sketches.
## Final Visualization

## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * Which Premier League teams overperformed or underperformed during the 2021-2022 season?
 * During which periods did teams overperform or underperform?
 * What patterns do different teams have in terms of performance?
 * Does the final PL table represent the best teams according to xP?


## Open Questions

I also want to include an animation of each team and their table position over each Matchweek. This would be an entirely different plot, but using the same data. I do not know if I have time for this. In my schedule I am putting time to it, but I do not really have an estimate as to how hard creating my first viz will be so I am trying to be optimistic.

## Future Work
