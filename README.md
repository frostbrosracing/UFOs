# UFOs

## Project Overview of the UFO Tracker
#### The goal of this project was to create a webpage using HTML and JavaScript that allows users to search for UFO sightings based on multiple search criteria.
This was in order to evaluate the viability of a business plan for a surfing and ice cream shop on the island.  Investors were interested in the weather findings to ensure that the business would be ideally located for optimal weather conditions.

#### Resources
- Data Source:  static/js/data.js
- Software:  Microsoft Visual Studio Code
- Languages:  JavaScript, HTML

## Results of the Webpage
By following the steps listed below a user can enter the search criteria for UFO sightings.  

1.  The search parameters must be typed according to the examples in the placeholder fields of the `Filter Search` box.

![Slide_1.PNG](https://github.com/frostbrosracing/UFOs/blob/main/README.md_images/Slide1.PNG)

2.  Begin by typing in the date according to the example.  The date of `1/1/2010` was used in the example.  Because all the sightings in the `data.js` file are located in the United States, "us" was also entered as the default search country.

![Slide_2.PNG](https://github.com/frostbrosracing/UFOs/blob/main/README.md_images/Slide2.PNG)

3.  Next, type in the state according to the example.  California was used in the example by typing in `ca`.

![Slide_3.PNG](https://github.com/frostbrosracing/UFOs/blob/main/README.md_images/Slide3.PNG)
## Summary of the Analysis
 
These mild temperatures are favorable for a business focused on the enjoyment of outside activity in ideal weather conditions.  In addition to the temperature data that was collected for this analysis, two additional queries could be written to go along with this analysis.

1. The June precipitation totals could be reported by substituting the temperature column in the query for the ***'prcp'*** column.  
2. The December precipitation totals could be reported by substituting the temperature column in the query for the ***'prcp'*** column.

A Pandas DataFrame could then be generated from which summary statistics could be reported.  This DataFrame would show the daily totals reported at each of the 9 weather stations.  

![Precipitation_chart.png](https://github.com/frostbrosracing/surfs_up/blob/main/Precipitation_chart.png)
