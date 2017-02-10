---
published: true
custom_css: leaflet
custom_js: leaflet
---
## A New Post - Testing Leaflet

A new attemept at getting Leaflet to work.

<div id="mapid"></div>

<script>
    // create the map object and set the cooridnates of the initial view: 
    var map = L.map('map').setView([51.4833, -3.1833], 10);

    // create the tile layer with correct attribution: 
    L.tileLayer('http://{s}.tiles.mapbox.com/v3/jamesg87.goac2bf1/{z}/{x}/{y}.png', {
        attribution: 'Map data &copy; <a href="http://openstreetmap.org">OpenStreetMap</a> contributors, <a href="http://creativecommons.org/licenses/by-sa/2.0/">CC-BY-SA</a>, Imagery © <a href="http://mapbox.com">Mapbox</a>',
        maxZoom: 18
    }).addTo(map);
</script>
    


Enter text in [Markdown](http://daringfireball.net/projects/markdown/). Use the toolbar above, or click the **?** button for formatting help.
