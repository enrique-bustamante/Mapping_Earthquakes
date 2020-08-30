# Mapping_Earthquakes


### Purpose

The purpose of this exercise is to build map that tracks not only the
earthquakes for the past 7 days, but the magnitude as well. The map also includes popup info for each incident.


### Technical Methods

To visualize the earthquake data, we needed a way to display a map along with
layers for markers, fault lines, and popups. We first used a map layer from
Mapbox to build upon, using Leafly. Leafly also allowed us to create a
markers, faultline, and popup layer. The GeoJSON function allowed us to import
data to parse for information.

D3 was also used to parse the data for the popups. We finally displayed all of
this information on a webpage that we put on local host using HTML and CSS.


### Future Considerations

For future considerations, it would be helpful to be able to pick the date
range for the data. Other additions could be to search by a specific country.
I did add a few more maps, just to have a few more options.
