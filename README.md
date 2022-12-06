# Surf and Shake: Weather Statistical Analysis

## Project Overview
The purpose of this analysis is to show potential investors that opening a surf and ice cream shop (Surf and Shake) in Oahu, HI is a great investment opportunity. The resources for this analysis include Jupyter Notebook and Python's SQL toolkit and Object Relational Mapper to analyze a weather database and retrieve all the temperatures for the months of June and December. The results of the analysis demonstrates that the weather patterns in Oahu are favorable for Surf and Shake's business to be sustainable year-round. 

## Results
The charts and list below addresses four key differences in weather between June and December:

June  |  December
:----:|:---------:
![jun_temps](https://github.com/fabeza/surfs_up/blob/eb58118d927426e9e7e27156983dedb70cd98138/jun_temps.png) | ![dec_temps](https://github.com/fabeza/surfs_up/blob/eb58118d927426e9e7e27156983dedb70cd98138/dec_temps.png)

* The average temperature in Oahu during the month of June is 74 F while December has an average temperature of 71 F.
* The minimum temperature during the month of June is 64 F and 56 F in December.
* The maximum temperature during the month of June is 85 F and 83 F in December.
* The standard deviation for the June data is 3.25 and 3.74 for December. This low standard deviations means the recorded temperatures for those months are clustered around the mean.

## Summary
In conclusion, opening the Surf and Shake shop in Oahu is an excellent investment. The island's weather is warm and tropical, with average temperatures in the low 70s F in June and December, which makes the business sustainable year-round. It doesn't get too cold in the island, the minimum temperature during June is 64 F and 56 F in December, while the maximum temperatures for both months are in the low 80s F, perfect temperatures for surfing and eating ice cream! 

If potential investors wish to see additional weather data, the hawaii.sqlite database offers other data points that are useful: precipitation and weather stations. It would be beneficial to expand the analysis using other queries, for example, calculating the average, minimum, and maximum precipitation to see if Oahu has a wet season and how it would impact the business. Additionally, we can look into potentially expanding the business to other locations/islands in Hawaii by querying the database to see which weather stations are more active and which ones have records of similar weather data to Oahu. 
