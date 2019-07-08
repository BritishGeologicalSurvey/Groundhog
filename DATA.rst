Providing Data
==============

Data can be supplied to the GIP in 3 ways

- Providing GIS data (GeoPackage)
- Providing OGC Web Services
- Providing secure Database access

Providing GIS Data 
------------------

The preferred format to provide data is GeoPackage. 

The best support to provide GeoPackage is using QGIS 3.8 Zanzibar. 

Create Geopackage
^^^^^^^^^^^^^^^^^

1. Download QGIS 3.8
2. Import current data
3. Make any styling changes required
4. Open the processing toolbox (Ctrl+Alt+T)
5. Open "Database" menu
6. Select "Package Layers"
7. Select input layers to package (3 dot button on right)
8. Make sure "Save Layer Styles into GeoPackage" is selected
9. Choose filename and destination of final geopackage
10. Click Run

Should now find your geopackage where ever you selected to save it. Drag and drop it into a new QGIS window to check it's output is as expected. 

