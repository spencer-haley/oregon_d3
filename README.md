# oregon_d3
D3 exploration using the state of Oregon as a focus

Source Data and Workflow:

County Boundaries Shapefile - Oregon	1990 County Boundaries. Source: Census Bureau TIGER files, 1:100,000 - http://navigator.state.or.us/sdl/data/shapefile/k100/county.zip
<br>
Coordinate reference system changed to EPSG:4326 (WGS 84) from EPSG:2992 (NAD83/Oregon Lambert (ft)) using QGIS 2.8.1
<br>
http://www.mapshaper.org/ used to simplify original .shp to 2.5% and 2 line intersections fixed
<br>
GeoJSON exported as oregon.geo.json and validated at http://geojsonlint.com/
<br>TopoJSON exported as oregon.topo.json

US Drought Monitor Shapefile - 20150310
<br>
National Drought Mitigation Center (NDMC), the U.S. Department of Agriculture (USDA) and the National Oceanic and Atmospheric Association (NOAA) - http://droughtmonitor.unl.edu/Home.aspx
<br>
Coordinate reference system changed to EPSG:4326 (WGS 84)
<br>
http://www.mapshaper.org/ used to simplify original .shp to 2.5% and 2 line intersections fixed
<br>
GeoJSON exported as usdm_20150310.geo.json

