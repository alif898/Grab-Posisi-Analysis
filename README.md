# Grab-Posisi-Analysis

https://alif898.github.io/Grab-Posisi-Analysis/

Analysis of Grab-Posisi dataset, Southeast Asia’s First Comprehensive GPS Trajectory Dataset, as part of NUS Data Analytics Competition 2022

### Problem Statement
There has been feedback about delays in Grab transport services in both Jakarta and Singapore (late driver arrival → late arrival at destination). This has led to a decrease in customer satisfaction and trust, which might increase customer turnover. Upon further research, it was found that this could be due to inaccurate ETA prediction, bad route planning, or other factors. Using the above dataset of GPS pings, what insights can your team obtain to help Grab alleviate these issues?

### Conclusion
We have collated some of the outliers which took a longer time or took an odd route into our presentation.

Here are our findings:

 - In both Jakarta & Singapore, our analysis of selected start points and end points shows that drivers can take varying routes, which may lead to inconsistent trip times, which can cause perception of delays/late driver arrival

 - Often, odd or longer routes are taken during peak hours

 - It is possible that Grab’s route recommendation system will recommend suboptimal routes during peak hours

 - Alternative routes might have been suggested with the intention of avoiding congested roads, but eventually a route that takes a longer time overall was taken

However, we acknowledge the following limitations:

 - We are not sure if these drivers selected the routes based on information from the Grab app or if they deviated and took a different route by themselves

 - It is possible that these longer trips/odd routes were due to multiple drop-off points or Grab Hitch rides

Nevertheless, these are potential recommendations which can be used to alleviate perception of long travel times:

 - During peak hours, detouring from congested roads may not save time, Grab may recommend drivers to continue using the route suggested on non-peak hours

 - For Jakarta, travelling by car in the city area is slower relative to travelling in residential areas, whereas motorcycle average speeds are consistent regardless of areas, Grab may recommend customers to travel by motorcycle in city area for faster transport
