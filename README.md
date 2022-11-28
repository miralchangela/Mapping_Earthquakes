# Mapping Earthquakes

## Purpose of the project :
* The purpose of this project is to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days. 
* To complete this project, we use a URL for GeoJSON earthquake data from the USGS website and retrieve geographical coordinates and the magnitudes of earthquakes for the last seven days. Then add the data to a map.
* To retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data , we are using the JavaScript and the D3.js library. We are also using the Leaflet library to plot the data on a Mapbox map through an API request and create interactivity for the earthquake data.

## Resources
- Data Source: [Earthquakes GeoJSON](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson), [Earthquakes above 4.5mag GeoJSON](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson), [Tectonic Plate GeoJSON](https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json)
- Software: HTML/CSS, JavaScript, Visual Studio Code, Leaflet, D3.js

## Results:

### Create a Mapbox account, setup config.js and open index.html

To interact with the maps API the user have to visit [mapbox.com](https://www.mapbox.com/), create a Mapbox account and retrieve the access token.

As shown below, the [index.html]() calls for the Mapbox API key in the *config.js* file. 

To open the *index.html* file, open the command line, navigate to the main folder and on the command line, enter `python -m http.server`.

### Link to Interactive Maps webpage
The deployed webpage is accessible at [Earthquake Mapping webpage](https://miralchangela.github.io/Mapping_Earthquakes/).

### Creating the overlays and controls:

![Layers](https://github.com/miralchangela/Mapping_Earthquakes/blob/main/static/images/layers.png)

### Interactive Maps Views:

![Street Earthquake](https://github.com/miralchangela/Mapping_Earthquakes/blob/main/static/images/street_eq_map.png)

![Satellite Earthquake](https://github.com/miralchangela/Mapping_Earthquakes/blob/main/static/images/satellite_eq_map.png)

![Light Earthquake](https://github.com/miralchangela/Mapping_Earthquakes/blob/main/static/images/light_ed_tectonicplate.png)

![Dark Majoreq](https://github.com/miralchangela/Mapping_Earthquakes/blob/main/static/images/dark_majoreq.png)

![Street with all overlay](https://github.com/miralchangela/Mapping_Earthquakes/blob/main/static/images/streets_all.png)

![streets with popup](https://github.com/miralchangela/Mapping_Earthquakes/blob/main/static/images/streets_all_tectonicplates_popup.png)
