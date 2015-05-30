# Mapping

Table of contents:
- [Software installation](#software-installation)
- [Getting started](#getting-started)
- [Web utils](#web-utils)
- [Glossary](#glossary)
 
## Software installation

### Mac OS X

- [GDAL Complete](http://www.kyngchaos.com/software/frameworks#gdal_complete)
- [Matplotlib python module](http://www.kyngchaos.com/software/python#matplotlib)
- [QGIS](http://www.kyngchaos.com/software/qgis)
- Add the following line to your `~/.bash_profile` for set up GDAL, more info [here](https://www.mapbox.com/tilemill/docs/guides/gdal/).

```sh
export PATH=/Library/Frameworks/GDAL.framework/Programs:$PATH
```

> To test your installation, run the terminal command `gdalinfo --version`

#### QGIS Plugins

- SimpleSvg
- TileLayer Plugin
- Table Manager

## Getting started

### Style

#### CartoCSS

### Data

### Publishing

## Web utils

- [GeoJSON.io](http://www.mapshaper.org/) *Edit/display geojson map data*
- [Mapshaper](http://www.mapshaper.org/) *Edit/simplify geospatial vector data*
- [Overpass Turbo](http://overpass-turbo.eu/) *Data mining of OpenStreetMap*

## Glossary

##### Baselayer

Layer used as *background* that contains the info of the world (terrain, streets, roads).

##### Overlay
*Insert definition here*

##### Tile layer
*Insert definition here*

##### Feature
*Insert definition here*

##### GeoJSON

Format for encoding collections of geographic data structures (points, lines, poligons) using *JSON*.

##### Shapefile

 Geospatial vector data format for geographic information system *(GIS)*.

##### KML

 XML notation for expressing geographic annotation and visualization.

##### Raster data
*Insert definition here*

##### Projection
*Insert definition here*

##### TIF
*Insert definition here*

##### GIS

A geographic information system, you know.

##### Vector data
*Insert definition here*


## License
MIT © [capua](https://github.com/capua)
