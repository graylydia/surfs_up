# Weather Analysis of Oahu
## Overview of the Weather Analysis
### Purpose
I love Oahu, Hawaii so much so that I decide to move there full time and open up a shop called Surf n’ Shake. We will be providing surfboard rentals and ice cream to locals, tourists, and myself. I have reached out to an investor, W. Avy. One of his concerns is the weather. I have already performed an analysis on the precipitation and to provide W. Avy with more information I have now performed an analysis on temperatures for the months of June and December. This new analysis will help determine if the Surf n’ Shake shop will be sustainable year-round.
## Results
<img width="146" alt="june_stats" src="https://user-images.githubusercontent.com/103657822/175394675-65a6abe9-7e1f-401c-801b-9db182817c58.png">
<img width="170" alt="dec_stats" src="https://user-images.githubusercontent.com/103657822/175394682-002092d8-ed8f-4fe1-b1cf-b765f3b29dda.png">

* To retrieve the June and December temperatures, we first had to query our hawaii.sqlite database and then create a DataFrame from that list. The df.describe() function allowed us to determine the number of recorded temperatures, mean, standard deviation, minimum recorded temperature, the 25th, 50th, 75th percentiles, and the maxiumum recorded temperature. As you can see when comparing these data points, there is not a large difference between the temperatures in June and December. The largest temperature difference is of 8 degrees for the minimum recorded temperature.
* The smallest difference is of 2 degrees for the maximum recorded temperature. The maximum temperature recorded in June was 85 degrees and 83 degrees in December.
* The average temperature in June was 74.94 degrees and 71.04 degrees in December. The difference between these two numbers is 3.9 degrees.

## Summary
