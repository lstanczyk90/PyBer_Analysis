# **PyBer Analysis**

## **Overview of Analysis**

The purpose of this analysis was to create tables and visualizations to assist key stakeholders at PyBer with understanding data for drivers and fares by city type (Urban, Suburban, Rural). Specifically, we were asked to create a table that summarizes the total number of rides, total number of drivers, the total fares for each city type, the average fare per ride and average fare per driver for each city type. 

Thereafter, we were asked to create a visualization that shows the total fares for each week by city type during the period 1/1/2019 to 4/28/2019.

See below for our analysis.

## **Results**

### **Pyber Summary Table**

![alt text](https://github.com/lstanczyk90/PyBer_Analysis/blob/4e8239c847bb81c110a76135862498f0da4429a2/analysis/PyBer%20Summary%20DataFrame.PNG)

As noted in the table above, we identified the following notable items:

- While Urban cities are serviced by a greater quantity of drivers, yield the highest number of rides, and are by far the most profitable for PyBer, the average fare per ride is significantly higher in rural communities than in urban (over $10 per ride). 

- Additionally, given that there are significantly less drivers in rural communities, the average fare per driver is signficantly higher in rural communities than in suburban and urban communities. 

- Suburban communities generaly fall in the middle between Rural and Urban communities when it comes to total rides, total drivers, total fares, average fare per ride, and average fare per driver. 

### **Fare Summary Visualization**

![alt text](https://github.com/lstanczyk90/PyBer_Analysis/blob/4e8239c847bb81c110a76135862498f0da4429a2/analysis/PyBer_Fare_Summary.png)

Per our review of the above-referenced visualization, we noted the same findings that are reflected in the analysis of the table (see above). Specifically, urban communities bring in significantly more fare revenues than rural communities overall, with suburban communities falling somewhere in the middle. 

Additionally, we noted the following:

- Rural communities appear to be slightly less subject to material swings or changes in fares by month when compared to suburban and urban communities. Fares, however, appeared to peak for rural communities at the start of April. 

- It is notable that all communities experienced a sharp spike in fares towards the end of February.

- Suburban communities experienced a sharp decline in fares at the start of March. While all categories experienced a decline to some extent, the impact was much higher for suburban communities. It is also notable that there was a sharp decline towards the middle of April for suburban communities. 

- Other than some of the trends identified above, it does appear that at a macro level, urban communities are subject to more fare volatility while rural communities are subject to less volatility. 

## **Summary**

Based on our preliminary review of the above-referenced data, we have the following initial recommendations:

- It may be worthwhile to perform an analysis of the high fares per ride and per driver in rural communities. Specifically, while rural communities do obviously have a lesser demand for PyBer services than urban, a review should be performed to determine whether rural communities are being over-charged and whether this has a negative impact on PyBer ridership in rural communities. 

- PyBer should investigate the volatility of fares for urban communities. Are these spikes due to changes in consumer demand (i.e. due to holidays, weather, etc.), surge-pricing for drivers, or a combination of both? It does appear that urban riders may be more price sensitive based on this volatility. 

- PyBer should investigate what caused the sharp weekly fare spikes and declines noted above in all community types, specifically to identify any trends and causes. Is there anything in particular during these periods that causes total fares to rise or fall? If yes, PyBer should analyze how these conditions can impact future revenues and perhaps leverage modeling or machine learning to adjust prices, supply, etc. under similar conditions in order to maximize revenues. 