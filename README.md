# PyBer_Analysis

## Project Overview
As we build a variety of charts, we will leverage our knowledge of Python arrays and turples, and learn how to apply Pandas methods, functions, and conditional expresion, as well as perform mathematical calculations on Series and DataFrames.

By the end of this module, we will be able to:
- Create line, bar, scatter, bubble, pie, and box-and-whiskers plots using Matplotlib.
- Add and modify features of Matplotlib charts.
- Add error bars to line and bar charts.
- Determine mean, median, and mode using Pandas, NumPy, and SciPy statistics.

## Resources
- Data Source: city_data.csv, ride_data.csv 
- Software: Anaconda 4.7.12, PythonData, Jupyter Notebook, Pandas, SciPy, and NumPy

## Summary
![Fig1](https://github.com/Shannon-Goddard/PyBer_Analysis/blob/master/analysis/Fig1.png)<br/>
Bubble charts are useful when presenting financial, population, and weather data because you can add a third and fourth factor to convey more information.
The first two factors are the x- and y-axes data, which we have been using quite frequently. By changing the “dot” into a “bubble,” we are adding a third factor: size. If there is more than one dataset that uses the same axes, we can change the color of each marker for each dataset, which will add a fourth factor: color.



![Fig2](https://github.com/Shannon-Goddard/PyBer_Analysis/blob/master/analysis/Fig2.png)<br/>
we can visualize the summary statistics and determine if there are any outliers by using box-and-whisker plots.

There is one outlier in the urban ride count data. Also, the average number of rides in the rural cities is about 4- and 3.5-times lower per city than the urban and suburban cities, respectively.

![Fig3](https://github.com/Shannon-Goddard/PyBer_Analysis/blob/master/analysis/Fig3.png)<br/>
From the combined box-and-whisker plots, we see that there are no outliers. However, the average fare for rides in the rural cities is about $11 and $5 more per ride than the urban and suburban cities, respectively.

![Fig4](https://github.com/Shannon-Goddard/PyBer_Analysis/blob/master/analysis/Fig4.png)<br/>
The average number of drivers in rural cities is nine to four times less per city than in urban and suburban cities, respectively.

![Fig5](https://github.com/Shannon-Goddard/PyBer_Analysis/blob/master/analysis/Fig5.png)<br/>
Pie charts allow us to depict percentages of categories as wedges of a pie. One limitation of pie charts is that they can only represent one dataset or category. However, pie charts do have a high visual appeal. We can make them even more visually appealing by choosing vibrant colors and giving each pie wedge a label.

If we look at the final product, we can see that the bubble chart contains three different scatter plots, one for each type of city.

![Fig6](https://github.com/Shannon-Goddard/PyBer_Analysis/blob/master/analysis/Fig6.png)<br/>

![Fig7](https://github.com/Shannon-Goddard/PyBer_Analysis/blob/master/analysis/Fig7.png)<br/>

## Challenge Overview
We've been asked by our CEO to create an overall snapshot of the ride-sharing data. In addition to our scatter and pie charts, she would like to see a summary table of key metrics of the ride-sharing data by city type, and a multiple-line graph that shows the average fare for each week by each city type.

### Objectives:
- Use Pandas functions like groupby, pivot, resample, and reset_index on a DataFrame.
- Use Pandas methods and attributes on a DataFrame or Series.
- Create a newDataFrame from multiple groupby() Series.
- Format columns of a DataFrame.
- Create a multiple-line graph.
- Annotate and apply styling to the chart.

## Challenge Summary
Create a summary DataFrame that showcases the following:

  - Total Rides
  - Total Drivers
  - Total Fares
  - Average Fare per Ride
  - Average Fare per Driver



### Summary DataFrame <br/>
|                | Total Rides    | Total Drivers  | Total Fares    | Average Fare per Ride| Average Fare per Driver |  
| -------------- |:--------------:|:--------------:|:--------------:|:--------------:|---------------:|
| Rural          | 125            | 78             | $4,327.93      | $34.62         | $55.49         | 
| Suburban       | 625            | 490            | $19,356.33     | $30.97         | $39.50         | 
| Urban          | 1,625          | 2,405          | $39,854.38     | $24.53         | $16.57         | 

The summary DataFrame shows that the Rural Average Fare per Ride and Average Fare per Driver is significantly higher than that of the Suburban and Urban city types. This can be correlated to the Total Rides and Total Drivers being significantly less than that of the Suburban and Urban city types.



Create a Multiple-Line Plot for the Sum of the Fares for Each City Type
![Fig8](https://github.com/Shannon-Goddard/PyBer_Analysis/blob/master/analysis/Fig8.png)
