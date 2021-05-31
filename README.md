# PyBer Analysis  Pyber, a Ridesharing App

### Overview of the analysis:
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


### Summary
There is a statement summarizing three business recommendations to the CEO for addressing any disparities among the city types. (4 pt)

Once you’re ready to submit, make sure to check your work against the rubric to ensure you are meeting the requirements for this Challenge one final time.  



Deliverable 1: A ride-sharing summary DataFrame by city type
•	The total number of rides for each city type is retrieved. (5 pt)
•	The total number of drivers for each city type is retrieved. (5 pt)
•	The sum of the fares for each city type is retrieved. (5 pt)
•	The average fare per ride for each city type is calculated. (5 pt)
•	The average fare per driver for each city type is calculated. (5 pt)
•	A PyBer summary DataFrame is created. (5 pt)
•	The PyBer summary DataFrame is formatted as shown in the example. (5 pt)

Deliverable 2: A multiple-line chart of total fares for each city type (45 points)
Using your Pandas skills and two new functions, pivot() andresample(), create a multiple-line graph that shows the total fares for each week by city type.

Deliverable 3: A written report for the PyBer analysis (20 points)
Use your repository README file to write your analysis of how to address any disparities in the ride-sharing data among the city types.

The analysis should contain the following:

Overview of the analysis: Explain the purpose of the new analysis.
Results: Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.
Summary: Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.



xxxxxxxxxxxxxxxxxxxxxxxxxxxx
As a reminder, the deliverables for this Challenge are as follows:
xxxxxxxxxxxxxxxxxxxxxxxxxxxx
Deliverable 1: A ride-sharing summary DataFrame by city type.
Deliverable 2: A multiple-line chart of total fares for each city type.
Deliverable 3: A written report for the PyBer analysis (README.md).
Upload the following to your PyBer_Analysis GitHub repository:
The PyBer_Challenge.ipynb file.
The results need to be kept populated in the PyBer_Challenge.ipynb file. Do not clear the output from the PyBer_Challenge.ipynb file before uploading to GitHub.
The “Resources” folder with the city_data.csv and ride_data.csv files.
The “analysis” folder with the PyBer_fare_summary.png.
An updated README.md that has your written analysis.
