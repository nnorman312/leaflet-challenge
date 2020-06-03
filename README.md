Visualizing Data with Leaflet

Using earthquake data from USGS (United States Geological Survey), I create a visualization with JavaScript and HTML. The USGS provides earthquake data in a number of different formats, updated every 5 minutes. 

For this demonstration, I visualize the magnitude of all earthquakes from the past 7 days (https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson). Using Leaflet, I create a map that plots all of the earthquakes from this dataset based on their longitude and latitude ("Earthquakes"). 

The second dataset on my map illustrates the relationship between tectonic plates (https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json) and seismic activity ("Fault Lines").

Using mapbox.com, I also include the following tile layers to provide different views: Satellite, Grayscale, and Outdoors. See previews of my visualization attached.
