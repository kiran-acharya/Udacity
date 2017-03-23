# Make Effective Data Visualization - (Udacity)

## Summary

This project visualizes a trimmed down subset of data from the 
[Lahman’s Baseball Database](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud507/baseball_data.csv&sa=D&ust=1490125746632000&usg=AFQjCNFCnmjfmAdD01JPvXiOtpgyT9Z94w). 
The visualization shows the high proportion of baseball players who are left-handed 
and compares their performance (batting average and number of home run) to the remaining players.

## Design
I have not attached my initial version of the project but my research started by studying 
the data of players and finding out what could be used to plot and visualize the data. 
It was very clear in the beginning that I will be using handedness as the tool to show some relations
visually for the performance of players. I used R scripts to aggregate data and to generate necessary 
CSV files that I used for my visualizations, I simply started playing with functions, each of these functions 
drew single visualization for datasets. While exploring many variables finally an initial decision made was to remove 
players with zero batting average. Since both performance indicators in the dataset have to do with batting, 
it does not make sense to include players that are not batters.



### Bar Plot

To compare how many players are right or left handed or how many are ambidextrous, 
we chose bar plot for this because: Bar graphs have three key attributes.

	* It's easy to compare sets of data between different groups at a glance.
	* The relationship of the data between the x and y axes is easy to see.
	* They are effective in presenting trends or changes over time.

### Box-Plots

To compare the batting average and home runs, box-plots are used. The
reason for this choice is the ability to convey a lot of information
in one single plot:

	* we can compare medians.
	* we can compare distributions.
	* we can visualize outliers.

## Feedback

	* What do you notice in the visualization?
	* What questions do you have about the data?
	* What relationships do you notice?
	* What do you think is the main takeaway from this visualization?
	* Is there something you don’t understand in the graphic?

Feedback A:
> The visualisation makes sense to me if data is right, I notice handedness plotted against performance of a player.
Looking at the data I think height could be used to make good assumptions. My suggestion would be reorder the players
which are more likely to user's view i;e left handed players to left and right handed to right others in center.


Feedback B:
> Visualizations are good. I had a feeling
that the % of left handed players was higher than that of the general
population, but had no idea that they had a higher avg batting average & HRs.

Feedback C:
>I did not need any of the narration to support the visuals/plots, it was clear at first glance
My take away would be although narration was quite to point. It would be great if you could add some color 
and find some way user's can interact with charts to drill down themselves.


Addressing Feedback A:
>According to the feedback A The order of categories was changed a bit anf left handed players are now kept on 
left side and right handed on right, this makes sense and also makes the visualization mode intuitive

Addressing Feedback C:
>Also based on feedback, tooltips that show the median values appear when hovering the boxes with the mouse pointer. 
Additionally, the performance and names of the outliers appear when hovering the outlier circles.



## Resources
### Baseball resources:

http://psycnet.apa.org/journals/bul/84/3/385/

https://en.wikipedia.org/wiki/Batting_average#Major_League_Baseball

https://en.wikipedia.org/wiki/Home_run#Inside-the-park_home_run

http://www.livescience.com/2665-baseball-rigged-lefties.html

### D3 Bar plots

http://bl.ocks.org/mbostock/3019563

https://bost.ocks.org/mike/bar/3/

### D3 tooltips

http://bl.ocks.org/mbostock/1087001

https://github.com/caged/d3-tip
