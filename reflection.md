1. At what array size did your baseline algorithm become noticeably sluggish to execute?

My baseline algorithm became noticeably sluggish to execute at an array size of 10,000.

2. Based on your empirical data and the shape of your graph, estimate how long (in seconds, minutes, or hours) your baseline algorithm would take to process an array of 1,000,000 elements. Show your reasoning.

After scaling the graph to no longer be logarithmic, I have concluded that the baseline algorithm grows quadratically as the number of elements in the input array increases. Thus, my estimate for the time it will take to process an array of 1,000,000 elements is 35,000 seconds.

3. Based on your empirical data and the shape of your graph, estimate how long (in seconds, minutes, or hours) your Kadane's algorithm would take to process an array of 1,000,000 elements. Show your reasoning.

My estimate for how long that the Kadane algorithm will take to process an array of 1,000,000 elements is 0.07787534908 seconds. I got this estimate from observing that the processing time of an array of n elements is linear when comparing time and number of elements. So, since it took 0.0007787534908857196 seconds for 10,000 elements in an array, it should take around 0.07787534908 seconds for an array of 1,000,000 elements.