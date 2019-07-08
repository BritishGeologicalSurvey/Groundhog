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

Providing Web Services
----------------------

We will try to assist with the setup of web services to serve data to EGDI,
by providing a basic explanation of how to do so easily.

WMS
^^^^

- Be awesome
- Make things faster

WFS
^^^

Install $project by running:

    install project

WCS
^^^^

- Issue Tracker: github.com/$project/$project/issues
- Source Code: github.com/$project/$project

Support
-------

If you are having issues, please let us know.
email: support@geoera.eu
Issue Tracker: https://github.com/GeoEra-GIP/Project-Support-WP8
