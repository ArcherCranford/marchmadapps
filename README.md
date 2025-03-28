# Project name 
marchmadapps
shortened version of March Madness Appearances
## Introduction:
The purpose of this map is to display the amount of March Madness Appearances by each state. However, this map excludes states that have 0 appearances including 6 states: Vermont, Alaska, South Dakota, New Hampshire, Nebraska, and Maine. The map also displays the amount of appearnaces by graduated circles. 
##Function
The way this map works is by using Java script, CSS, and HTML. On the basemap, I added my GeoJSON Data that contained the infromation about each state who had appearances. Then, using that data I used a power method to create different sized symbols or "graduated circles" to display the difference in appearance by different state. 
##Libraries 
https://code.jquery.com/jquery-2.1.4.min.js
https://unpkg.com/leaflet@1.7.1/dist/leaflet.js
https://cdnjs.cloudflare.com/ajax/libs/leaflet-ajax/2.1.0/leaflet.ajax.min.js
##Sources
Basemap: https://www.openstreetmap.org/copyright, https://carto.com/attributions
Data: https://en.wikipedia.org/wiki/NCAA_Division_I_men%27s_basketball_tournament_bids_by_school
Data Manipulation: https://geojson.io/#map=3.49/36.35/-108.38
