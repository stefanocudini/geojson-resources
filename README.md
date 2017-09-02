# geojson-resources

Statis GeoJSON resources

## Install

```
npm i geojson-resources
```

## Usage

Loading by JQuery and show in Leaflet map directly in your page:
```
$.when(
  $.getJSON('https://unpkg.com/geojson-resources@1.1.0/world.json'),
)
.then(function(arg) {
  
  L.geoJSON(arg[0]).addTo(map);
  
});
```
