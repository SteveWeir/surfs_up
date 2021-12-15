# Surf's Up: Challenge Project

## Overview
  In order to accomplish the client's goal of opening a surf shop & ice caream parlor in Oahu, outside funding must be secured from notable investor and avid surfing fan, W. Avy. W. Avy requires assurance that an Oahu location would be suitable and attract customers year-round. Thus, Oahu's weather and temperature patterns will be examined in order to show the investor that Oahu's consistent, tropical climate would adequately drive demand for both surfing gear and ice cream!

* Resources used in this analysis:
  * SQLite database including daily temperature and precipitation data for Oahu
  * SQLAlchemy to pull queries from the database into Python for analysis
  * Jupyter notebook
  * Python and all relevant libraries thereof (pandas, numpy, datetime, etc)

## Results
June Temperature Statistics:
![june_temps_df_stats](https://user-images.githubusercontent.com/85244439/146256505-0e624405-b929-499f-882e-1a4e2c6f5f04.PNG)
December Temperature Statistics:
![dec_temps_df_stats](https://user-images.githubusercontent.com/85244439/146256544-73830c6e-3a85-4287-b35c-e9ab2f8747ce.PNG)

Based on the data shown in the two tables above, the following observations can be made:

  1. As previously stated in the overivew, Oahu provides a warm climate year-round. Average temperatures in December are only three degerees (farenheit) cooler than in June.
  2. Even at its hottest, Oahu's beaches provide a comfortable environement for surfing and ice cream consumption. The highest temperature recorded in June (85 degrees) is only two degrees warmer than in December (83 degrees). 
  3. In looking at the standard deviations of both data sets, we can infer that day-to-day temperatures will be relatively consistent. Temperatures in both June and December typically deviate by less than 4 degrees farenheit from the mean in either direction. 

## Summary

Based on the results of this analysis, Oahu appears to be an ideal location for the client's surf shop & ice cream parlor venture. With average temperatures in the low-to-mid 70s year-round, and with relatively low deviations from either average, unpredictable weather would seem to be less of a threat to the client's business model. However, to help ensure this, I would also recommend querying preecipitation data for June and December. Additionally, I would analyze both average and significant wave height in June and December, in order to better understand surf conditions. This would allow the client to forecast sales and profits from the surf shop more accurately.
