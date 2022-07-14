# Mapping_Earthquakes
Mapping Earthquakes with JavaScript &amp; APIs

The purpose of this project was to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days.
In order to accomplish this project, a URL for GeoJSON earthquake data from the USGS website was used to retrieve geographical coordinates and the magnitudes of earthquakes for the last seven days. I also used the Leaflet library to plot the data on a Mapbox map through an API request and created interactivity for the earthquake data.

Deliverable 1: Add Tectonic Plate Data
Using my knowledge of JavaScript, Leaflet.js, and geoJSON data, I added tectonic plate data using d3.json(), added the data using the geoJSON() layer, set the tectonic plate LineString data to stand out on the map, and added the tectonic plate data to the overlay object with the earthquake data.

![image](https://user-images.githubusercontent.com/102322707/179074576-d6cc1f80-7a4c-4af9-85d2-fe814a1e931a.png)

Deliverable 2: Add Major Earthquake Data
Using my knowledge of JavaScript, Leaflet.js, and geoJSON data, I added major earthquake data to the map using d3.json(). I added different colors and set the radius of the circle markers based on the magnitude of earthquake, and added a popup marker for each earthquake that displays the magnitude and location of the earthquake using the GeoJSON layer, geoJSON().

![image](https://user-images.githubusercontent.com/102322707/179089463-64252c41-45d8-4417-82ed-93ecdf00dbc6.png)

Deliverable 3: Add an Additional Map
Using my knowledge of JavaScript and Leaflet.js, I add a third map style ("Outdoors) to my earthquake map.

![image](https://user-images.githubusercontent.com/102322707/179089119-c3dad8cc-f33a-418b-a5f4-b769517591ed.png)

