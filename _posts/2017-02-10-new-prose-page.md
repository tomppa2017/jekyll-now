---
published: true
---
## A New Post

<div id="mapid"></div>

	<script type="text/javascript">

	var mymap = L.map('mapid').setView([47.2, 3.2], 6);

	L.tileLayer('https://api.mapbox.com/styles/v1/mapbox/streets-v10/tiles/256/{z}/{x}/{y}?access_token=pk.eyJ1IjoidG9tY3JhdyIsImEiOiJjaXl6eGIxd3cwMDB3MzNxbTE3dXA2ZGVxIn0.aV8eyoMAAVfcdtxZwANalw', {
	    attribution: 'Map data &copy; <a href="http://openstreetmap.org">OpenStreetMap</a> contributors, <a href="http://creativecommons.org/licenses/by-sa/2.0/">CC-BY-SA</a>, Imagery © <a href="http://mapbox.com">Mapbox</a>',
	    maxZoom: 18,
	    id: 'your.mapbox.project.id',
	    accessToken: 'pk.eyJ1IjoidG9tY3JhdyIsImEiOiJjaXl5NmZ6MmowMDA3MndtcTEzMW9jZGQxIn0.JN30JZ6xA_gI2Atu6k02WQ'
	}).addTo(mymap);

	var polylinePoints = [
		[48.844328, 2.374377],
		[47.618719, 4.336338],
		[46.799296, 4.439421],
		[46.282470, 4.778602],
		[46.200151, 5.214965],
		[46.184570, 5.528312],
		[46.110894, 5.825930],
	    [46.210457, 6.142902],
	];

	var polylineOptions = {
               color: 'blue',
               weight: 10,
               opacity: 0.5
             };



	var day1 = new L.Polyline(polylinePoints, polylineOptions);

	day1.bindPopup(
		"Day 1: Paris to Geneva. For more info, <a href=leaflet_test.html>click here</a>");

         mymap.addLayer(day1);                        

	</script>


Writing new **posts** _with_ Prose.io.

Enter text in [Markdown](http://daringfireball.net/projects/markdown/). Use the toolbar above, or click the **?** button for formatting help.
