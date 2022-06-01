# Leaflet map.on('click') Example

This is a simple [Leaflet](https://github.com/Leaflet/Leaflet) HTML/JavaScript example using the map.on click event handler to populate a text field with the latitude and longitude of the mouse click event.

## Breakdown

[Leaftlet Reference](https://leafletjs.com/reference-1.6.0.html)

- Import the stylesheet `leaflet.css`
- Import the script `leaflet.js`
- Create a div element with the id of "map"
- Initialize the map inside the "map" div `L.map('map')`
- Set view and zoom with `setView`
- Build a tile source (assume [Slippy Map Tilenames](https://en.wikipedia.org/wiki/Tiled_web_map#Defining_a_tiled_web_map) standard) with `tileLayer` and add to map
- Create the event handler `function onMapClick`
- Register the event handler `map.on('click', onMapClick)`
- Added HTML text fields with id lat and lon to receive the latitude and longitude data values
