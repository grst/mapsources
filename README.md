# Web Maps Mapsource Collection
This is a collection of tiled web maps for GEOS ([Google Earth Overlay Server](https://github.com/grst/geos/)). 
The mapsources are based on the [MOBAC XML MapSource Format](http://mobac.sourceforge.net/wiki/index.php/Custom_XML_Map_Sources) with some extensions. For a documentation of the format, please read [GEOS: creating mapsources](https://github.com/grst/geos#creating-mapsources)

## Status of the maps
* World
  * Google Road: **works**
  * Google Terrain: **works**
  * Komoot: **works**
  * OSM Mapnik: **works**

* Europe
  * Outdooractive Germany: **works** (more precise boundaries?)
  * Outdooractive Germany Topo: **works** (Note: contains only zoom levels 15/16, so you have to zoom in to view it)
  * Outdooractive Austria: **works** (more precise boundaries?)
  * Outdooractive Austria Topo: **works** (Note: contains only zoom levels 15/16, so you have to zoom in to view it)
  * Outdooractive South Tyrol: **works** (more precise boundaries?)
  * Geoportail France: **needs API key**
  * Kompass: **works**
  * OSM 4umaps: **works**

* Oceania 
  * NZ topo: **doesn't work** (Tileserver return 404 when outside their web app)


## Wishlist
* North America Topo Maps
* [Swisstopo](http://map.geo.admin.ch)
* [Geoportail France](https://www.geoportail.gouv.fr/carte)
* [Bayernatlas Topo](https://geoportal.bayern.de/bayernatlas/index.html?X=5253240.74&Y=4380640.88&zoom=10&lang=de&topic=ba&bgLayer=tk&layers_opacity=0.2,0.25&layers=lod,e528a2a8-44e7-46e9-9069-1a8295b113b5&catalogNodes=122)

## Creating Map Sources
Please read the tutorial [here](https://github.com/grst/geos#creating-mapsources)

## Contributing
Feel free to create pull requests with new maps or improvements! 
