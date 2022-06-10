# PyBer_Analysis

## Overview of Analysis

This new analysis had two parts: 
The first was to find measures such as the total drivers by city, total rides by city, total fares by city, average fares 
per ride and average fare per driver via 2 different CSVs, which were merged into a single DataFrame. After these 
measures were found we could place them into a formatted, summary DataFrame that could cleanly present the information.

![Alt text](https://github.com/jeremylam21/PyBer_Analysis/blob/df0b3b2f688a69787e2aafb20d9168a24cae3aa3/analysis/pyber%20summary.png)


The second was to change the original dataframe so that it was indexed by date and time. By doing this we were able to 
show the total fares for each city type over a period of time as shown below:


![Alt text](https://github.com/jeremylam21/PyBer_Analysis/blob/99f6250fb4110a3da86c96ee2ea397de9effc530/analysis/Fig7.png)


## Results
From the images above we can see that Urban cities have the highest amounts of rides, drivers, fares, average fares per driver and average fares per ride. Suburban cities are second, and Rural cites have the lowest. This may be expected since there are lower populations in rural areas, but this is still notable. The chart also reflects the what is shown in the summary dataframe, however it's iteresting to note that there is a spike in total fares right before March, 2019. 


## Summary
In sum, to address the disparities between cities I believe that there are 3 options:
1. Lower fares so that more riders are willing to use the PyBer service in rural cities. 
2. Increase the portion of fares that are paid directly to the driver in rural cities, in order to increase the supply of drivers in those areas. 
3. Encourage Urban drivers (monetarily) to take riders in suburban and rural areas to distribute the supply of drivers across different city types. 
