# tools_for_gis_scientists

<details>
  <summary>Spoiler warning</summary>
  
  Spoiler text. Note that it's important to have a space after the summary tag. You should be able to write any markdown you want inside the `<details>` tag... just make sure you close `<details>` afterward.
  
  ```javascript
  console.log("I'm a code block!");
  ```

  <summary>Spoiler warning 2</summary>
  Spoiler text2
  
</details>

--- Python librairies ---

-- GENERIC --

Numpy (Numerical Python) : uses structured array for scientific computing

pandas : 

SciPy (Scientific Python) : 

scikit : machine learning

matplotlib : draw plots, visual display

Regex (Regular expression) : detect or filter in strings

reportlab : the open source part allows to create reporting pdf

json : manipule les json

neo4j : managing graphs

psycopg : postgresql driver for python

networkx :

-- SIG --

PySAL : open-source meta-package that brings together a family of packages for spatial data science
https://pysal.org/

	MomePy : Momepy is a library for quantitative analysis of urban form - urban morphometrics. It is part of PySAL (Python Spatial Analysis Library) and is built on top of GeoPandas, other PySAL modules and networkX.
--> used for converting gdf to networkx graph

geopandas : pandas with a geographic component, manipule les geoDataFrames
https://geopandas.org/en/stable/docs.html
- transférer des données vers postgis : https://geopandas.org/en/stable/docs/reference/api/geopandas.GeoDataFrame.to_postgis.html

Gdal/OGR :translator library for raster and vector geospatial data formats, transform extensions from almost all gis softwares

Shapely : manipuler et analyser les géométries
https://shapely.readthedocs.io/en/latest/manual.html

pyproj (= binding de PROJ.4) : gestion des SRC et reprojections de points

osgeo : module osr permet de faire des reprojections

fiona : lecture et écriture des shapefiles
https://fiona.readthedocs.io/en/latest/manual.html

OSMNX : spécialisée dans les routes de OSM, utilise l'api Overpass, lui transmet des requêtes
https://osmnx.readthedocs.io/en/stable/
remarque : besoin d'avoir son propre environnement pour l'installation

osmosis : tool for manipulating and processing raw .osm data

Mapnik : open source toolkit for developing mapping applications 

arcpy : Spatial analysis, data conversion, management, and map production with Esri ArcGIS.

RSGISLib : raster processing and analysis, it classifies, filters, and performs statistics on imagery

leaflet : an open-source JavaScript library for mobile-friendly interactive maps

ipyleaflet : fusion between jupyter notebook and leaflet

lidar : process and visualize lidar data

Geemap

Folium : build interactive webmap

GrassGIS : GRASS GIS contains over 500 modules to process and render geographic data. The software allows to manipulate a variety of raster, vector and 3D formats, and run simple to advanced spatial analysis and modeling.
https://grass.osgeo.org/learn/overview/
include cluster identification, generalization

overpass

wms_grid_gen : produces raster tiles from a wms flux
https://github.com/ilokhat/wms_grid_gen



--- APIs ---

Overpass : Recup données depuis OSM à partir de requêtes

OTB (OrfeoToolBox) : process high resolution optical, multispectral and radar images at the terabyte scale

Nominatim : tool to search OSM data by name and address and to generate synthetic addresses of OSM points (reverse geocoding)
https://nominatim.org/release-docs/latest/


Notable sources :
https://gisgeography.com/python-libraries-gis-mapping/


--- logiciels ---

star UML : modéliser des diagrames de classes et générer du code automatiquement

pgmodeler : modéliser des BDD postgresql

Modelio : open source pour faire des graphs


--- Cartographie

https://colorbrewer2.org

https://gribrouillon.fr/


--- Autre
https://www.connectedpapers.com/

https://miro.com/app/dashboard/

https://excalidraw.com/
