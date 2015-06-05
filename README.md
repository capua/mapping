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

Is a language for map design and it is similiar in syntax to CSS, but builds upon it with specific abilities to filter map data and by providing things like variables.

Carto, aka CartoCSS, targets the Mapnik renderer and is able to generate Mapnik XML.

Carto is an evolution of the *Cascadenik* idea and language, with an emphasis on speed and flexibility.

### Data

### Publishing

## Web utils

- [GeoJSON.io](http://www.mapshaper.org/) *Edit/display geojson map data*
- [Mapshaper](http://www.mapshaper.org/) *Edit/simplify geospatial vector data*
- [Overpass Turbo](http://overpass-turbo.eu/) *Data mining of OpenStreetMap*
- [Mapschool](http://mapschool.io/index.es.html) *A free introduction to geo (9 languages)*

## Glossary

##### Baselayer

Layer used as *background* that contains the info of the world (terrain, streets, roads).

##### Overlay

Layer that overlays the baselayer with custom info.

##### Tile layer

Square bitmap graphics displayed in a grid arrangement to show a map.

##### Feature

Features is a term used to describe markers, lines and polygons.

##### GeoJSON

Format for encoding collections of geographic data structures (features) using *JSON*.

##### Shapefile

Geospatial vector data format for geographic information system *(GIS)*.

##### KML

XML notation for expressing geographic annotation and visualization.

##### Projection

Projections are methods of transforming the coordinates of locations on earth to a two-dimensional plane. *Web Mercator* is adopted by the vast majority of web maps.

##### TIF

A TIF is a file format for saving raster images. TIF is often a *GeoTIFF*, meaning the file is embedded with georeferencing information.

##### Raster data

Rasters are a pixel-based data format that represent surfaces. Digital photographs are stored in this format, which is also referred to as a bitmap.

##### Vector data

Vector data is made of points, lines and polygons. *KML*, *GeoJSON*, *shapefiles*, *GPX* are all examples of vector data formats.

##### GIS

A geographic information system, you know.


## License
MIT © [capua](https://github.com/capua)
