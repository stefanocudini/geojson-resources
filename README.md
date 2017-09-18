# geojson-resources

Statis GeoJSON resources

## Install

```
npm i geojson-resources
```

## Usage

Loading by JQuery and show in Leaflet map directly in your page:
```javascript
$.when(
  $.getJSON('https://unpkg.com/geojson-resources@1.1.0/world.json'),
)
.then(function(arg) {
  
  L.geoJSON(arg[0]).addTo(map);
  
});
```

## License
This work is licensed under a **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License**. 

![Creative Commons License Logo](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png "License")

