# PyBer Analysis

## Overview
With the increasing popularity of using ride-sharing services, it is important to understand how to more effectively serve varying geographical locations. The purpose of this project was to analyze ride-sharing data for a company called PyBer. I produced a summary dataframe of the ride-sharing data by city type. Then, using pandas and matplotlib, I created a multiple-line graph showing the total weekly fares for each city type.

## Method and Results

Jupyter Notebooks was used for this analysis, with the dependencies panda and matplotlib. The data analyzed was sourced from the files [city_data.csv](https://github.com/alexdallman1029/PyBer_Analysis/blob/main/Resources/city_data.csv) and [ride_data.csv](https://github.com/alexdallman1029/PyBer_Analysis/blob/main/Resources/ride_data.csv).

The code used to analyze the data can be found [here](https://github.com/alexdallman1029/PyBer_Analysis/blob/main/PyBer_Challenge.ipynb).

Types of cities analyzed were urban, suburban, and rural. Total ride count, driver count, and fare were calculated for each city type. Then, average fare per ride and average fare per driver were calculated. 

See Figure 1 for results of the calculated data. There are the most urban drivers and rides, while urban fare is the lowest. The rural ride-sharing is less popular and is more expensive for customers to receive rides, at approximately $10 more per ride. The larger the ratio is between drivers and rides, the higher the fare.
<br><br><b>Figure 1</b>
<br><img src="https://github.com/alexdallman1029/PyBer_Analysis/blob/main/Analysis/Pyber_data.png" width=500><br>
<br><b>Figure 2</b>
<br><img src="https://github.com/alexdallman1029/PyBer_Analysis/blob/main/Analysis/Pyber_fare_summary.png" width = 1000><br>


## Summary
Because the ride-share market seems to be dominated by the urban city type, I would suggest to Pyber to focus on hiring more rural drivers to ensure demand for drivers is being met in that city type. Most likely, higher costs are associated with longer rides in rural areas. Pyber could incentivize drivers to drive in rural areas to lower cost per ride.
