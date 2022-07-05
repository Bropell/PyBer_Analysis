# PyBer_Analysis
## Project Overview
The purpose of this analysis is to use the power of Python, Pandas and Matplotlib to create a summary DataFrame of the ride-sharing data by city type. A multiline graph was generated to show the weekly fares for each city type do that better decisions can be made at PyBer.
## Results
https://github.com/Bropell/PyBer_Analysis/blob/main/PyBer_Challenge.ipynb

![alt text](https://github.com/Bropell/PyBer_Analysis/blob/main/Analysis/pyber_summary_df.png)

As seen in the image above regarding ride-sharing data by city type, there are several take away points. The indices are ordered from smallest to largest in terms of city size. The data in the first three columns show an increase in total rides, total drivers and total fares respectively as the size of the city increases. This makes sense because larger cities have more people, which means more people in need of a ride, more drivers are needed to transport those people, and more funds are generated as a result. Conversely, the average fare per ride and driver shows a decrease as the city size increases. This is due to a larger ratio between the fare and rides or drivers for the smaller city types.

![alt text](https://github.com/Bropell/PyBer_Analysis/blob/main/Analysis/PyBer_fare_summary.png)

As seen in the multiline plot above, it is obvious that the total fare per city type is consistently higher for the larger city types. This correlates to what is shown in the DataFrame image above as well. Another take away point here is that there does not seem to be a significant difference in total fares anywhere during this time frame for any city type. Suburban cities have a small spike in late February, Urban cities have a couple small spikes around the same time and rural cities have two small spikes around late February and beginning of April. The low point for all the city types seems to be in early January. 
## Summary
Three business recommendations can be made to the CEO based off the disparities among city types. Looking at either the smallest city type or the largest city type is a good idea because the most change can be made. One recommendation is to potentially increase total fares in a rural city, more drivers can be added. However, there is a delicate balance here because adding more drivers without generating significantly more revenue will cause the average fare per driver to go down. Another recommendation is to slightly increase the cost of rides for urban cities in order to increase total fares. There is always the risk of losing customers by raising the cost but the total rides is so high compared to other cities that more revenue could still be generated. The last recommendation is to reduce the number of drivers in urban cities. Compared to other city types, urban cities are the only city type where the total drivers exceeds the total rides. The idea here is that there are already plenty of drivers for the rides and even though total fares might decrease, the money spent paying extra drivers can be saved instead.     