# oregon_d3
D3 exploration using the state of Oregon as a focus

Source Data and Workflow:

County Boundaries Shapefile - Oregon	1990 County Boundaries. Source: Census Bureau TIGER files, 1:100,000 - http://navigator.state.or.us/sdl/data/shapefile/k100/county.zip
Coordinate reference system changed to EPSG:4326 (WGS 84) from EPSG:2992 (NAD83/Oregon Lambert (ft)) using QGIS 2.8.1
http://www.mapshaper.org/ used to simplify original .shp to 2.5% and 2 line intersections fixed
GeoJSON exported as oregon.geo.json and validated at http://geojsonlint.com/
TopoJSON exported as oregon.topo.json


