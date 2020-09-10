# Surf's Up with Advanced Data Storage and Retrieval

## Overview of the Analysis
### Purpose
The investor of a Surf n' Shake shop in Oahu selling surfboards and ice cream wants more information about temperature trends. Specifically, he wants temperature data for the months of June and December, in order to determine if the business is sustainable year-round.

## Results
### Key Differences between June and December Weather
- The lowest temperature recorded in June was 64° and the highest was 85°. The average temperature in June is 74.9° with a standard deviation of 3.3°.
- The lowest temperature recorded in December was 56° and the highest was 83°. The average temperature in December is 71.0° with a standard deviation of 3.7°.
- The interquartile range of temperatures in June is 73-77° and the IQR for December is 69-74°.

<img src='https://github.com/npantfoerder/surfs-up/blob/master/Images/june_df.png' width=500>
<img src='https://github.com/npantfoerder/surfs-up/blob/master/Images/dec_df.png' width=500>

## Summary
There were 1,700 temperature measurements taken in June and 1,517 measurements taken in December. 75% of the measurements from June were higher than 73° and 50% of the measurements from December were higher than 71°. The average temperatures in June and December are only 4° apart. December has a larger range of temperatures (56-83°), but only 25% of the measurements are below 69°. Temperature measurements from June range from 64-85°.
### Two Additional Queries
- Percipitation measurements in June range from 0-4.4 with an average of 0.1 and a standard deviation of 0.3. 
- Percipitation measurements in December range from 0-6.4 with an average of 0.2 and a standard deviation of 0.5.

<img src='https://github.com/npantfoerder/surfs-up/blob/master/Images/june_rain.png' width=500>
<img src='https://github.com/npantfoerder/surfs-up/blob/master/Images/dec_rain.png' width=500>

#### Resources
- Data Sources: hawaii.sqlite
- Software: Python 3.7.3, Anaconda 4.8.3, SQLAlchemy 1.3.18, Virtual Studio Code 1.48.2 
