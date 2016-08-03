Data visualization Project
==============

## Summary

This project investigates the distribution of minimum hourly wage around the world as well as its relation to GPD per capita of the G20 Countries. In general, most countries' minimum hourly wage is under 2 USD. Examing the G20 Countries, we found the minimum wage is generally positively correlated to GDP per Capita. However, countries in the same GDP tier show some difference by region. This project explores the general relationship and also this nuance by region.

## Design

### Histogram

To understand the distribution, I chose the histogram plot to plot the minimum wage data. In addition, to help reader understand the specific countries in each category, I also designed a hover animation that display list of related country names when you hover over the bar. 

### Barchart and Slopegraph
I subset only G20 countries in the later analysis to gather a more detail understanding on the difference in terms of labor policy in major countries. I chose
barchart + slopegrape since it will show 

- the relative position of country in each catogory and the relationship between two variables; 
- a comparison between countries by their ranking change. 

To highlight the story by region, I color countries by region. 

To hightlight the relationship, I also design a hover animation that gives a dark color to the bar and bold font to the text.

I adapt codes form d3 histogram block, barchart block and also slopegraph block and put them together. The process also include some data manipulation in javascript. It took quite some time to consolidate the data and code of d3 3.0 version and d3 4.0 version.

## Feedback 

- Feedback1
"I noticied following things and hope others will explore more.

There is no label in the first plot. There is title and text but if only shown the plot what information is gained. Like I don't know the unit of the wage.
Same as point 1, in the second plot the per captia GDP range and minimum wage rank text is small and seems like merged with the axis labels. Making them more prominent will help in more understanding.
The plots are left aligned and some labels are cut. If you can align them in centre then that will be better. (See the image)"

- Feedback2

"
Very nice work. I really like the interactive design. A few points,

The first figure does not have axes labels
It might be helpful to make some light color instead of pale bars.
The font size may be enlarged appropriately to improve readability"

- Feedback3
"Your visualization is for the most part well designed and easy to understand.
In my opinion two things could be improved:
The list of countries in the first graph that appear with "the hover" could be display in  ascending order of the minimum wage and not by alphabetical order.
And for the second part of your work, you conclusion isn't obvious when I look at the graph. You should better highlight your findings."

To summary, the feedback I received include:

1. Storyline -how to highlight stroy via graph. before I did not color the countries by region, but after I discuss with the coach, I think it is a good idea to highlight it by color to show a pattern;
2. Missing title and small unit label. I added the missing title and bolden the label like "minimum wage rank" and "GDP per Capita rank";
3. Padding and margin ajustment to ensure the text will not cut out in some area;
4. Oragnize the pop-out text of country list in Figure 1 in the acsending order of minimum wage;
5. make some fonts larger to improve the readablity (I did enlarge the text font size of country names by 1);
6. I also receive comment about considering doing a scatter plot. I tried that in R, and feel that this slopegraph offer a better story than scatter plot.

## Resources 

d3 histogram
<http://bl.ocks.org/mbostock/3048450>

d3 bar chart 
<https://bost.ocks.org/mike/bar/3/>

d3 slopegraph
<http://bl.ocks.org/zbjornson/2573074>
# Data_Visualization_Project
