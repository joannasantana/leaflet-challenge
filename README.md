# Leaflet Challenge

Background:

The United States Geological Survey, or USGS for short, is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.

The USGS is interested in building a new set of tools that will allow them to visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. In this challenge, I was tasked with developing a way to visualize USGS data that will allow them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.

Using JavaScript, HTML, and CSS I've created a visualization of all earthquakes across the globe in the past 7 days. The color of the markers correspond to the depth of the earthquake and the size conveys the earthquake's magnitude. When a marker is clicked, a popup will give the location, time, and magnitude of the quake.

Skills demonstrated:
- Connecting to and reading USGS GeoJSON data usig the D3.js JavaScript library.
- Using OpenStreetMap to create a tile layer.
- Creating maps and plotting data with the Leaflet.js library.
- Setting up and adding a legend to a map.

Data Source: https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php
