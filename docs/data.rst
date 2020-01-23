Providing your Data
====================

Data can be supplied to the GIP in 3 ways

- Providing GIS data (GeoPackage) to EGDI
- Hosting your own OGC Web Services
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

Create Geopackage (alternative route)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1. Download GDAL
2. Check it has GeoPackage support using `ogrinfo --formats`

You should have something like `GPKG -raster,vector- (rw+vs): GeoPackage`

and also check that your input file format is listed

3. You can check what options you have to create a GPKG with:

`ogrinfo --format GPKG`

Help on options for GeoPackage can can be found at:

https://gdal.org/drivers/vector/gpkg.html

and

https://gdal.org/drivers/raster/gpkg.html

and

https://gdal.org/programs/ogr2ogr.html

4. use `ogr2oger` to create and update your GeoPackage

For example to add a directory of shapefiles use:

`ogr2ogr -f "GPKG" filename.gpkg ./path/to/dir`

and to add data to this geopackage (say from an Oracle table) you could use:

`ogr2ogr -f "GPKG" filename.gpkg oraSource.ovf -nln my_new_layer_name -update"`

Where `oraSource.ovf` is a virtual layer containing information about the Oracle database like:

.. code-block:: xml

    <?xml version="1.0" encoding="UTF-8"?>
    <OGRVRTDataSource xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
     xsi:noNamespaceSchemaLocation="http://ogc2.bgs.ac.uk/xs/ogrvrt.xsd">
        <OGRVRTLayer name="mintell">
            <SrcDataSource>OCI:USER/Password@//host:port/sid</SrcDataSource>
            <SrcSQL>
                SELECT *
                FROM PUBLISHED.XXX
            </SrcSQL>
            <GeometryType>wkbNone</GeometryType>
        </OGRVRTLayer>
    </OGRVRTDataSource>

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
