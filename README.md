# Data Visualization Project

## Data

The data I propose to visualize for my project is from the 2021-2022 Premier League Season. Each row in the dataset represents a instance of a certain matchweek for a team. The row contains the team, matchweek, points (accumulated up to that matchweek), expected points (accumulated up to that matchweek), and where in the PL table the team would be if it was based on the expected points. The data was scraped from understat.com. The focus of this project will be to compare a team's results to what their expected results to see if any teams were "lucky" or "unlucky".

## Initial Sketches

I created a series of proof of concept visualizations of this data. I started with a couple iterations of sketches:
![image](https://github.com/Diz138/PL-2021-2022-xPvsPoints/blob/master/images/sketch_iteration1.png)<br />
It began with the idea to focus on one team at a time as it would become too distracting with all 20 PL teams on one graph. From here I know I can compare both xP and Points using the same axis as they represent the same value. There is the option to change teams from a drop-down and the final points and xP total will be displayed in a table on the graph. The biggest question for a viewer of this visual would be to see if the team overperformed or underperformed and when. This will be determined when there is a big difference in the values of Points and xP. 
![image](https://github.com/Diz138/PL-2021-2022-xPvsPoints/blob/master/images/sketch_iteration2.png)<br />
On my second iteration, I noticed that I was using the two channels (color and line type) to represent the same value, so I instead thought of the idea of using color to highlight the portions of the season in which there was a big difference in xP and Points. 
## Prototypes
After a couple iterations of my design, it was now time for me to start. I first just plotted one teams (Arsenal) data over the course of the season.
[![image](https://github.com/Diz138/PL-2021-2022-xPvsPoints/blob/master/images/initialArsenalPlot.png)](https://vizhub.com/Diz138/bc89b191a0a845f6aaba0abc06cd5e00)<br />
After this, I then plotted Arsenal's xP and Points data. This plot included axes.
[![image](https://github.com/Diz138/PL-2021-2022-xPvsPoints/blob/master/images/secondIteration.png)](https://vizhub.com/Diz138/a4e0f29cf06d49b2bcb1574e61dde22e)<br />
The next step after I completed plotting both xP and Points data was to add a way for users to change between which teams they view. I just added the dropdown functionality and no interaction.
[![image](https://github.com/Diz138/PL-2021-2022-xPvsPoints/blob/master/images/thirdIteration.png)](https://vizhub.com/Diz138/511122bd5c154a24840e3d034febd282)<br />
After this I was able to add interaction to this and place the button above the plot.
[![image](https://github.com/Diz138/PL-2021-2022-xPvsPoints/blob/master/images/fourthIteration.png)](https://vizhub.com/Diz138/3ed0f744eab74924b87b8b5615011309)<br />
The issue with this dropdown is that it causes sizing errors when clicked (more than 1 team is shown as an option) so I thought including the logos as buttons would be a cooler viz instead.
[![image](https://github.com/Diz138/PL-2021-2022-xPvsPoints/blob/master/images/LineChartwithLogos.png)](https://vizhub.com/Diz138/db634275642f4c4d9498ac4f9780e5a8)<br />
This was one of my last iterations before my final visualization. I liked the look, but it was targeted only at viewers who understand the Premier League. I knew I needed to change this for my last visualization.
## Final Visualization
[![image](https://github.com/Diz138/PL-2021-2022-xPvsPoints/blob/master/images/finalviz.png)](https://vizhub.com/Diz138/8ba924f9f568416d95fdbdc82e80e1f8)<br />
My final visualization offers a lot of user-friendly information. First, a legend differentiates the two lines in the chart. An interactive legend is available to the right of the chart. The legend includes every team in this data set in order of where they finished in the 2021-2022 Premier League Table. When hovered over, the team name and logo will be emphasized. A black box is put around whatever team is being shown. Also, the colors used for the line chart title and line of points corresponds to the given team.
## Questions & Tasks

The following questions drove the visualization and interaction decisions for this project:

 * Which Premier League teams overperformed or underperformed during the 2021-2022 season?
 * During which periods did teams overperform or underperform?
 * What patterns do different teams have in terms of performance?

## Future Work
[![image](https://github.com/Diz138/PL-2021-2022-xPvsPoints/blob/master/images/finalEnglandMap.png)]([(https://vizhub.com/Diz138/1c8820a5828f4107a59b0ae14760f93a)])<br />
In the future, I am hoping to incorporate this map of England into my visualization somehow. I think it could be a cool introduction page to this visualization. However, I did not have time to implement it in this project.
