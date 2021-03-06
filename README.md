# Weather Analysis of Oahu
## Overview of the Weather Analysis
### Purpose
I love Oahu, Hawaii so much so that I decide to move there full time and open up a shop called Surf n’ Shake. We will be providing surfboard rentals and ice cream to locals, tourists, and myself. I have reached out to an investor, W. Avy. One of his concerns is the weather. I have already performed an analysis on the precipitation and to provide W. Avy with more information I have now performed an analysis on temperatures for the months of June and December. This new analysis will help determine if the Surf n’ Shake shop will be sustainable year-round.
## Results
<img width="146" alt="june_stats" src="https://user-images.githubusercontent.com/103657822/175394675-65a6abe9-7e1f-401c-801b-9db182817c58.png">
<img width="170" alt="dec_stats" src="https://user-images.githubusercontent.com/103657822/175394682-002092d8-ed8f-4fe1-b1cf-b765f3b29dda.png">

* To retrieve the June and December temperatures, we first had to query our hawaii.sqlite database and then create a DataFrame from that list. The df.describe() function allowed us to determine the number of recorded temperatures, mean, standard deviation, minimum recorded temperature, the 25th, 50th, 75th percentiles, and the maxiumum recorded temperature. As you can see when comparing these data points, there is not a large difference between the temperatures in June and December. The largest temperature difference is of 8 degrees for the minimum recorded temperature.
* The smallest difference is of 2 degrees for the maximum recorded temperature. The maximum temperature recorded in June was 85 degrees and 83 degrees in December. The average temperature in June was 74.94 degrees and 71.04 degrees in December. The difference between these two numbers is 3.9 degrees.
* The standard deviation for the month of June is 3.26 and 3.75 for December. The standard deviation is telling us that 50% of our temperatures will fall in between 71.68 and 78.2 for the month of June. As for the month of December, 50% of our temperatures will fall in between 67.29 and 74.79.
## Summary
Based off of the results, I think Ohau, Hawaii would be able to support Surf 'n Shake year round. With the average temperatures in both June and December being low to mid 70s, I think the demand for surfing and ice cream would remain constant. I performed an additional query to discover the average temperature per reporting station for the months of June and December (the code and results are shown below). This information can help us determine which area of Ohau would be best suited for our business. The Station ID USC00519523 and Station ID USC00514830 could be two appropriate places to open our business. Station USC00519523's average reporting temperature in June is 76.67 degrees and 72.43 degrees in December. Station USC00514830's average reporting temperature in June is 76.01 degrees and 73.22 degrees in December. Both of these stations report high average temperatures in June and relatively high average temperatures in December. 


<img width="690" alt="june_query" src="https://user-images.githubusercontent.com/103657822/175431705-006c5785-426b-43c3-b7d1-09623a26dde9.png">
<img width="705" alt="dec_query" src="https://user-images.githubusercontent.com/103657822/175431716-e2ccd5bd-4b3f-49cd-95b0-bbfa4fd17a2d.png">
<img width="522" alt="avg_station_temps" src="https://user-images.githubusercontent.com/103657822/175431718-949599f7-0222-4223-9ac2-c84d8f9f3dc6.png">
