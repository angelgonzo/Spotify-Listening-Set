# Spotify-Listening-Set

In this project, I used a data set from data.gov in which compiled Spotify usage data from various artists and platforms, within a 12 year span.

I used Google Sheet as the tool to help clean and really focus on two aspects of the data: most used platform, and most listened artist on a specific platform by year.

I found the total playing time in milliseconds, and then found each individual platform's playing time within the 12 years. 
Converted that data into seconds, minutes, finishing off with hours which is what is used for the bar graph seen next to the toal values

I chose to not find the average playing time in hours as it wasn't the main goal of the data set, but I still provided the average playing time in ms for those who wanted to know. 

Following that came the creation of the Pivot Table to see the artist's most played on platform. I used a splicer that allows the table to be filtered by year using a string condition, rather than a data format. 
  - the data format was not chosen because the this data set contained over 140k rows, and going through each would be terrible to determine when the cutoffs were due to the data set not having complete years sometimes
  - the string format was better suited as the dates all began with the year, so for 2014, the filter would display dates that included '2014'
