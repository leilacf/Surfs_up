# Surfs_up
## Overview
We worked closely with W. Avy in establishing a business plan for the opening of a *Surf 'n Shake shop*, serving surfboards and ice cream to the local community. The idea was deemed a success, however, there was one primary concern in the way: the volatility of the weather. When establishing a shop which at its core, is based heavily on sunny days, the weather could drastically impact profits. W. Avy had previous experience with another surf shop that had been rained out of existence--therefore, with this knowledge, he asked us to run analytics on a weather data set he had, set on the island in which we wanted to open the shop. The purpose of this project was to understand and dissect temperature and weather trends, specifically for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business would be a sustainable year-round venture.

## Results
We used Jupyter Notebook with Python coding, and SQLAlchemy to query the Hawaii SQLite dataset.
From our analysis, below are the tables of the summary statistics for the months of June and December:
#### June Temperatures
![This is an image](https://github.com/leilacf/Surfs_up/blob/main/June%20temps.png)

#### December Temperatures
![This is an image](https://github.com/leilacf/Surfs_up/blob/main/December%20temps.png)

Summary statistics serve as a compelling synthesis of datasets which can be used to extract valuable information from exploratory data analysis, including statistical distribution of variables, potential outliers, and whether the data are skewed. 

Based on this, below are a few primary observations:
- In terms of temperature ranges, December has a wider range with the mean temperature at 71 degrees and lowest temperatures of 56. Meanwhile, June has a mean temperature of 74.9 and a minimum of 64, indicating that there could be quite a few days of temperatures in the 50's during December, while in June, they do not drop below the 60's range. 
- The standard deviation for both months does not vary significantly, both between 3.25-3.74. These are low standard deviations indicating that the data are clustered around the mean and are there therefore, relatively consistent and more reliable as extreme values are not occuring frequently in the data set.
- In both June and December, the difference between their respective mean and median (50% column) is small, allowing for one to infer that the data are symetrically distributed 

## Summary
In concluding our analysis, we can infer that the weather is relatively stable in Oahu for the establishment of the *Surf 'n Shake shop.* Going forward, if additional analysis were to be needed, below are a few reccomendations:
- Comparing key tourism months with consequent weather data
- including percipitation rates, UV index, and wind speed in the weather data in tandem with temperatures to provide an overall holistic weather approach
- including current data on the amount of surf shops on the island and their proximity in miles to the particular land where we want to establish the new shop, to take into account to what extent competing products could affect profits

Lastly, in using a similar analytical approach, we could utilize additional databases and our refactored code, to further investigate the profitability and success of other new establishments on the island.
