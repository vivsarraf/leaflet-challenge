# leaflet-challenge Module 15


# Leaflet Challenge
![5-Advanced](https://github.com/vivsarraf/leaflet-challenge/assets/135401654/4cce097f-5d7a-4a35-ae09-4aeb8e48512c)


## Project Overview
The United States Geological Survey, or USGS for short, is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.
The USGS is interested in building a new set of tools that will allow them to visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. In this challenge, you have been tasked with developing a way to visualize USGS data that will allow them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.## Deployment
Explore the fascinating world of microbial ecosystems with our interactive dashboard: [Leaflet Dashboard](https://vivsarraf.github.io/leaflet-challenge/)).


## Instructions

The instructions for this activity are broken into two parts:

Part 1: Create the Earthquake Visualization
Part 2: Gather and Plot More Data (Optional with no extra points earning)
Your first task is to visualize an earthquake dataset. Complete the following steps:
Get your dataset. To do so, follow these steps:

The USGS provides earthquake data in several formats, updated every 5 minutes. Visit the USGS GeoJSON FeedLinks to an external site. page and choose a dataset to visualize. The following image is a screenshot of what appears when you visit this link.

Import and visualize the data by doing the following:
Using Leaflet, create a map that plots all the earthquakes from your dataset based on their longitude and latitude.

Your data markers should reflect the magnitude of the earthquake by their size and the depth of the earthquake by color. Earthquakes with higher magnitudes should appear larger, and earthquakes with greater depth should appear darker in color.
Hint: The depth of the earth can be found as the third coordinate for each earthquake.
Include popups that provide additional information about the earthquake when its associated marker is clicked.
Create a legend that will provide context for your map data.

Your visualization should look something like the preceding map.

## References

http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php
