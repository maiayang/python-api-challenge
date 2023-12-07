# python-api-challenge

In this challenge we used API's to retrieve and analyze weather and map data. The challenge consisted of two parts. In the first part of the challenge we used the OpenWeatherMap API to find relationships between latitude and weather conditions. In the second part of the challenge we filtered the cities in the first part to find potential vacation spots based on our ideal weather conditions. Then we used the Geoapify API to find the nearest hotel to those cities.

For the first part of the challenge we used the citipy Python library to generate random cities. Then we made requests to the OpenWeatherMap API to retrive coordinate and weather informaiton for each city. We saved these results to a Pandas dataframe and from there we plotted each weather condition against latitude to observe patterns. Linear regressions were performed for each plot.

For the second part of the challenge, we first plotted the cities from the first part using Geoviews. Then we filtered the cities using our chosen weather conditions. Finally we used the Geoapify API to find the nearest hotel to those cities and created another Geoviews map showing our vacation cities.

Help for this code was obtained from Stack Overflow.

