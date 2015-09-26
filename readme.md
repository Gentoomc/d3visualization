####Summary:

This is a bubble chart of Literacy rates and Homicides by Country in 2012.
In general, most countries are clustered around the lower part of the homicides but scattered throughout literacy rate. High income (both OECD and nonOECO) countries are in the uppermost left corner, indicating high literacy rate and low homicides. They have the least dispersion on both axes. 
On the other hand, lower middle income and upper middle income countries have the most dispersion throughout the x-axis, the homicides. Low income countries have most dispersion throughout the y-axis, the literacy rates but most are at the lower end of the homicides.

#####Changes made (final design):
Due to changing sample size as a result of missing data, it was confusing to readers and I decided to only use year 2012 to show the trend, instead of using multiple years. Values with (0,0) are gone (they were not real values), and it is much easier to understand the story behind the visualization.

####Initial Design decisions:

- Chart type: Bubble chart 
  Visual encodings: 
  - Position x: Intentional homicides (per 100,000 people)
  - Position y: Literacy rate, adult total (% of people ages 15 and above)
  - Color: Income Group (nomical data)
  - Animation: Time (Year) 

  I chose a bubble chart because I wanted to show the relationship between homicide and literacy rate for each country, and also used color to represent a third variable, an income group that each country belongs to. This wouldn't have been possible for a bar plot, which would have forced me to use a summary statistic such as a mean or a median. I chose to use bubble colors to represent income group, instead of region that each country belongs to, because there seemed to be more similarities of literacy and homicide combinations between countries in a given income group than in a region. I also chose year to animate to see a trend over time. 

#####Changes made (final design):

- Chart type: Bubble chart 
  Visual encodings: 
  - Position x: Intentional homicides (per 100,000 people)
  - Position y: Literacy rate, adult total (% of people ages 15 and above)
  - Color: Income Group (nomical data)

  Based on the feedbacks received, I dropped year-based animation since there was no clear trend over time due to missing data. 

####Feedback:

"What does OECD mean? Noticed Lower income correlated with lower literacy rate."

"I noticed how the sample size kept changing and that each year it would start at zero. The relationship for the years with larger data suggests that literacy rate around 100% correlates to low homicide rate across most income levels."

"What are values with (0,0)? Why are sample size different for each year?"

####Resources:

http://dimplejs.org/examples_viewer.html?id=bubbles_vertical_grouped
http://dimplejs.org/advanced_examples_viewer.html?id=advanced_storyboard_control
http://data.worldbank.org/indicator/VC.IHR.PSRC.P5
http://data.worldbank.org/indicator/SE.ADT.LITR.ZS

