# PyBer Analysis 

### Overview 
As a data analyst at PyBer, a ride-sharing app company valued at $2.3 billion has just asked for the analysis of its rideshare data from January to early June of 2019 and accompanying visualization for the CEO, V. Isualize. One of the tasks is creation of the summary DataFrame of the ride-sharing data by city type. 

The task has some objectives that may benefit from the analysis to:
  A-	help improve access to ride-sharing services and 
  B-	determine affordability for underserved neighborhoods.
  C-	A multiple-line graph that shows the total weekly fares for each city type. 
  D-	A report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.


### Methods
Using two different datasets in Excel (.csv) files, we application of the Pandas groupby() function with the count() and sum() methods on PyBer DataFrame columns we calculated:
  1- the total number of rides, total number of drivers, and the total fares for each city type. 
  2- the average fare per ride and average fare per driver for each city type. 
  3- added the resulting data to a new DataFrame.

### Results
The analysis of the Ride-sharing data shows that the services active in three different community settings: Urban, suburban and rural areas. The results from these three different settings indicate that the total rides in the urban areas top the other two by 1,625 rides, and the lowest being in rural areas with only 78 instances. The total number of drivers is also the highest in urban vs suburban or rural areas, as are the total number of fares across the three settings in the same order. The average fares, on the other hand are different from the previous results in that they rank from the highest in the rural ($34 per ride) vs suburban or urban areas (Figure 1).  

**Figure 1: PyBer Summary DataFrame**

---------------
![Fig-0-1-PyBer-summary-DataFrame.png](https://github.com/BHashemi2021/PyBer_Analysis/blob/main/analysis/Fig-0-1-PyBer-summary-DataFrame.png)

----------------

The total fares for each city type differed from each other greatly with the highest being in the urban and lowest in the rural areas. It is noticeable to that the average fare was the highest in the rural and lowest in the urban ares that shows an inverse correlation. Whether this phenomenon has been the causative problem for fewer rides in rural areas or the fewer number of people living in such areas has been the reason or both, an analysis investigating their correlation might be warranted (Figure 1).

While there is an upward trend in the number of rides in early January 2019 in urban and suburban areas, the rides are downward in rural areas, indicating a lower interest to take such services early in that month. All the three community types show a synchronous increase in the number of rides in mid February but after the peak and keeping it for nearly 10 days, the downward trend begins and plateaus until late March. The trend takes another leap in both urban and rural areas up to April and the ridership in the two areas begins to go down while the trend is taking pace to increase in suburban areas (Figure 2).


**Figure 2: The total fares for each city type during January to Mid-April 2019.**

--------------------------
![Fig8.png](https://github.com/BHashemi2021/PyBer_Analysis/blob/main/analysis/Fig8.png)

--------------------------


### Summary
First, there seems to be a disproportionately large number of rides in urban areas versus suburban or rural areas. On the other hand the fare per ride in rural areas is nearly more than 1.4 times in the cities. Therefore, a normalization of the fares in rural areas may be helpful in more rides in such areas. 

Secondly, While the number of drivers in the urban areas is nearly 5 times is greater in urban cities, the total revenues from such areas is only twice is much as suburban areas. Therefore allocation of a number of drivers to suburban and to a lesser degree to rural areas deems to be advisable. 

Third, despite some relative changes in the seasonality of the number of rides in different months of the study during January to April 2019, a more solid recommendation on such trends can be made by undetaking a longer study during all months and seasons of the year. 

 

 






