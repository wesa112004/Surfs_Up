# Surfs_Up

## Overview
The purpose of the analysis was to provide more information about the months of June and December in regards to temperature in order to see if opening a business on Oahu would be sustainable year round.

### Results

The results of the two summary statistics can be seen below with a side by side comparison of the dataframes based on summary statistics:


<img width="1046" alt="Summary_df" src="https://user-images.githubusercontent.com/100330488/164998316-e1b6f0d9-a1b0-4313-b4ea-9316c1133603.png">
The december month had lower average temperatures, as well as a greater standard deviation in the month of decvember indicating more fluctuations in temperatures deviating from the mean as opposed to the month of June where the average temperature was higher with less fluctuations and data points that follow a less volatile distribution: See June histogram

<img width="725" alt="Jun histogram" src="https://user-images.githubusercontent.com/100330488/165005506-3222ed9c-428d-494f-b557-1d6afbbb0239.png">

Compared to December histogram<img width="813" alt="Dec histogram" src="https://user-images.githubusercontent.com/100330488/165005514-31c0cf7c-57b7-4e8f-80fc-5e6867f27703.png">

We can also see more outliers for colder temperatures in December compared to June as noted byt the following diagram:

<img width="1188" alt="box and whisker plot" src="https://user-images.githubusercontent.com/100330488/165006060-247bddaa-09b4-472c-af4b-098a3d9b379b.png">

This is in-line with the variance differences we can see from the descriptive statistics comparing June and December, but not surprisingly we would expect lower temperatures in December

##### SUMMARY

The data suggest that June is likely a more appropriate month to operate a surf and ice cream shop because it is warmer, with even the minimum temperatures not deviating as far from the mean relative to December. Further, the data suggest that although June has less fluctuations in temperatures relative to December, there are still some relatively warm days in december where an ice cream shop and surf shop would likely do well. This is evident by the average temperature in december showing to be relatively close to that of June (71 vs 74). There are more data points for the month of June vs December, which could have made the data distrubition appear more favorable as far as having higher temperatures and less of a standard deviation. Because the sample size is larger for June, the standard deviation is less or lower than that of december, thereby making the distribution look more stable and favorable, despite the obvious of being a summer month. 
Additional queries that could be made regarding the weather data that might be useful for considering a shop would be to determine where on the island the weather is most favorable. This could be done by writing a query for the temperature based on station location and filtered by dates to see where the warmest spots are during the course of the year. Another query would be based on precipitation, station location and temperature by merging dataframes. This would provide us with more direct information that takes into account rain and temperature by location.

Although surf report data isnt in the dataset, it would be useful to know based on location. Most tourists and even locals are attracted to bigger surf and a shop in the location where the biggest attractions are would essentially have higher volumes of customers
