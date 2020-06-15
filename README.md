# PyBer_Analysis
  Ride sharing apps have revolutionized the transportation space, so it is imperative to analyze data because there are many factors that affect the profitability of drivers. In this assignment, I wanted to synthesize the key metrics for the ride-sharing data by creating a summary DataFrame. Furthermore, I created a line graph that would visiually demonstrate the disparities between city types and provide data to support my recommendations that I would give the CEO. I cleaned and analyzed the data by using key concepts I used in this module such as creating DataFrames and utilizing the groupby() function. According to the line chart and summary DataFrame, 
  ![](images/total%20fare%20by%20city%20type.png) ![](images/summary_df.png) rural cities have the least amount of drivers and total rides. This makes the average cost per ride and average fare per driver much higher than the average costs in suburban or urban cities. However, urban cities have more drivers and total rides which make the average cost per ride much cheaper. The summary DataFrame shows us that the data is reasonable and makes sense: the lower the population density in the city, the less rides given and higher price per ride. 
  
  The main challenge I ran into was formatting the dataFrame with the correct structure and language. For example, when I was creating the summary dataframe with the groupby series, the summary would print/display more information than what was needed. While I only needed the numerical value to form a summary dataframe, the column names would also display. I overcame this issue by searching the error message online and read forums to figure out the solution. I learned that to display the exact value, you have to code to specifically pull the data in the groupby series with the square bracket and quotations.

  Based on the data, I would recommend adding more drivers in the rural area to decrease the average price per ride. If prices rise, customers will definitely look for a cheaper alternative. However, if you add more drivers in the rural area, customers are more likely to use the ride-sharing app. Targeting the rural cities are a great opportunity because they are more likley to have brand loyalty if we provide the best prices for ride sharing. To gain more insight on the individual cities' data, I would use the pivot table and chart in Excel. A pivot chart can also be filtered to show when people are using the app the most. I have to inspect the data and make sure that there are no blank rows and all columns have headers. I would have to build a certain criteria and use the COUNTIFS function to count how many times all the criteria are met. 
