# PyBer Analysis 

### Overview 
As a data analyst at PyBer, a ride-sharing app company valued at $2.3 billion has just asked for  the analysis of its rideshare data from January to early June of 2019 and accompanying visualization for the CEO, V. Isualize. One of the tasks is creation of the summary DataFrame of the ride-sharing data by city type. 

The task has some objctives as follows that will benifit from the analysis to:
  A-	help improve access to ride-sharing services and 
  B-	determine affordability for underserved neighborhoods.
  C-	A multiple-line graph that shows the total weekly fares for each city type. 
  D-	A report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.


### Methods
Using the Pandas groupby() function with the count() and sum() methods on PyBer DataFrame columns compiled in two different Excel (.csv) files we calculated:
  1- the total number of rides, total number of drivers, and the total fares for each city type. 
  2- the average fare per ride and average fare per driver for each city type. 
  3- added the resulting data to a new DataFrame.

### Results
The analysis of the Ride-sharing data shows that the services active in three different community settings: Urban, suburban and rural areas. The results from these three different settings indicate that the total rides in the urban areas top the othe two by 1,625 rides, and the lowest being in rural areas with only 78 instances. The total number of drivers is also the highest in urban vs suburban or rual areas, as are the totl fares across the three settings in the same order. The average fares, on the other hand are different from the prevous results in that they rank from the highest in the rural ($34 per ride) vs suburban or urban areas (Figure 1).  

**Figure 1: PyBer Summary DataFrame**

---------------
![Fig-0-1-PyBer-summary-DataFrame.png](https://github.com/BHashemi2021/PyBer_Analysis/blob/main/analysis/Fig-0-1-PyBer-summary-DataFrame.png)

----------------

The total fares for each city type diffred from each other greatly with the highest being in the urban and lowest i the rural areas. It is noticeable to add that th average fare was the highest in the rural and owest in the urban ares that shows an inverse correlation. Whether this phenomenon has been the causative problem for fewer rides in rural areas, aside from the fewer number of people in such areas to call for a ride, needs to be investigated to see i there is a significant correlation (Figure 1).

While there is an upward trend in the number of rides in early jjanuary in urban and suburban areas, the rides are downward in rural areas, indicating a lower interest to take such services early in that month, All three areas show a synchronous increase in the number of rides in mid February but after the peak and keeping it for nearly 10 days, the downward trend begins and plateues until late March. The trend againtakes a leap in both urban and rural areas up to April and the two areas begin to go down while the trend is taking pace to increase in suburban areas (Figure 2).


**Figure 2: The total fares for each city type during January to Mid-April 2019.**

--------------------------
![Fig8.png](https://github.com/BHashemi2021/PyBer_Analysis/blob/main/analysis/Fig8.png)

--------------------------


### Summary

???????????????There is a statement summarizing three business recommendations to the CEO for addressing any disparities among the city types. 

 






