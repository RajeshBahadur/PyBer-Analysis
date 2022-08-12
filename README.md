# PyBer-Analysis
Module 5-PyBer ride share-Analysis
A written Report for the PyBer Analysis

#Overview of the analysis

In this anaysis, we have receceived data from "PyBer", a company which has platform where those who drive can connect with riders to go from one place to another.
We have received data in two csv files, one containing city data and other having ride data. The purpose of the analysis is to summarize and present the information
in graphical mode to explain what is the total fare per week based on the type of city's. The period covered in this analysis is from January to April 2019.
The anaysis started by merging data in the two csv files, followed by pivoting merged data and getting average fare per city per week for 16 weeks.The end result is to 
dispay the average fare per city/per week in the graphical mode using fiverthirtyeight style of graph in Matplotlib.

I have used Jupyter Note book to manipulate data by importing matplotlib and pandas.

#Results
Looking at the summary data frame, urban city has the highest total revenue and rural cities has the lowest, the total revenue in urban is almost 10 times of rual cities.
However, when we look into average fare per ride and average fare per driver, rural cities got the highest average fare per ride and per drivers.The total fare is higher in 
the urban cities due to higher number of rides due to density of the population.
Looking at the line chart, the weekly total fares are fluctuating, all cities experienced a growth in fare during first week of march. In case of rural cities, the total fare
numbers are flactuating so much during the period from mid March to Mid April which is not the case with sub urban and urban cities. It seems, the demand for rides in urban and suburban
cities are consistent.
