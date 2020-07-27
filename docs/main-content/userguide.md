*BGS Groundhog Desktop*

User Guide v2.1.0 (BETA)

July 2020

![](./media/image1.png)

![](./media/image2.png)![](./media/image3.png)

**© Copyright British Geological Survey (UKRI) 2020. All rights
reserved.**

This document is intended as a general guide to the operation of the BGS
Groundhog Desktop software (Groundhog) and no warranty is given as to
the completeness or accuracy of the information contained within. The
contents of this document are subject to change without notice.

Except for any third-party images and content, logos or other corporate
branding materials, this document is licensed under the UK Open
Government License.

<http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/>

Topographic basemap images used within this user guide use OS open data
layers. Contains OS Data © Crown Copyright and Database Right.

**Versions**

BGS Groundhog Desktop (Groundhog) is available in two versions badged
(1) ***Community*** and (2) ***Professional***. Community is free-to-use
under the UK Open Government Licence. Professional has extended features
for building conceptual and 3D site and geological models and is
available under a commercial license via our UK commercial reseller,
Land Quality Management Ltd. (LQM).

**Contact Information**

BGS Groundhog Desktop (Groundhog) is software created and maintained by
the British Geological Survey. Further information about the development
project, and the software download, can be found on our website.

[www.bgs.ac.uk/groundhog](http://www.bgs.ac.uk/groundhog)

For general enquiries about the Groundhog project, please email us.

<groundhog@bgs.ac.uk>

**Distribution**

Licenses for Groundhog Professional are distributed by Land Quality
Management Ltd. (LQM). Further information can be obtained via their
website.

<https://www.lqm.co.uk/csm/>

<judith@lqm.co.uk>

![](./media/image3.png)![](./media/image2.png)

# Contents

Introduction 6

[About Groundhog 7](#about-groundhog)

[Installation 7](#installation)

[First Use 8](#first-use)

[Digital License Activation 8](#digital-license-activation)

[Data Objects 10](#data-objects)

[Object Tree 11](#object-tree)

[Site / Project Folder 11](#site-project-folder)

[Models Folder 15](#models-folder)

[System Objects Folder 15](#system-objects-folder)

[User Interface 18](#user-interface)

[Main Panels 19](#main-panels)

[Main Toolbar **\[1\]** 19](#main-toolbar-1)

[Session Panel **\[2\]** 19](#session-panel-2)

[Map Window **\[3\]** 20](#map-window-3)

[Map Window Layer Control **\[4\]** 24](#map-window-layer-control-4)

[Cross-Section Window **\[5\]** 27](#cross-section-window-5)

[Cross-Section Window Layer Control **\[6\]**
29](#cross-section-window-layer-control-6)

[Status Bar **\[7\]** 32](#status-bar-7)

[Importing & Exporting Data 33](#_Toc46143806)

[Images 34](#images)

[Shapefiles 38](#shapefiles)

[ASCII Grids 39](#ascii-grids)

[OBJ Files 40](#obj-files)

[Working With Borehole Logs 42](#_Toc46143811)

[Borehole Data Import 43](#borehole-data-import)

[CSV/TXT Format 43](#csvtxt-format)

[Importing CSV 44](#importing-csv)

[Importing Tabular Data 52](#importing-tabular-data)

[Importing AGS Format Data 57](#importing-ags-format-data)

[Importing LAS Format Data 58](#importing-las-format-data)

[BGS Borehole Records 62](#bgs-borehole-records)

[Displaying Boreholes 66](#displaying-boreholes)

[Creating Borehole Log Templates 67](#creating-borehole-log-templates)

[Editing Borehole Log Templates 68](#editing-borehole-log-templates)

[Editing Borehole Data 85](#editing-borehole-data)

[Drawing Points, Shapes & Annotations 92](#_Toc46143823)

[Creating New Layers 93](#creating-new-layers)

[Creating and Editing Point Layers
93](#creating-and-editing-point-layers)

[Creating & Editing Shape Layers 97](#creating-editing-shape-layers)

[Creating & Editing Annotation Layers
105](#creating-editing-annotation-layers)

[Drawing Cross-Sections 114](#drawing-cross-sections)

[Creating the Cross-Section Alignment
115](#creating-the-cross-section-alignment)

[Creating Cross-Sections Without an Alignment
115](#creating-cross-sections-without-an-alignment)

[Drawing a Polyline for the Alignment
115](#drawing-a-polyline-for-the-alignment)

[Including Boreholes in the Cross-Section Alignment
117](#including-boreholes-in-the-cross-section-alignment)

[Modifying the Alignment 117](#modifying-the-alignment)

[Viewing and Editing the Cross-Section
120](#viewing-and-editing-the-cross-section)

[Topographic Profile 121](#topographic-profile)

[Viewing Boreholes 122](#viewing-boreholes)

[Buffering Boreholes Into a Cross-Section
124](#buffering-boreholes-into-a-cross-section)

[Registering Images in Cross-Section
125](#registering-images-in-cross-section)

[Drawing Geology 127](#drawing-geology)

[Developing Conceptual Site Models 135](#_Toc46143840)

[Introduction 136](#introduction-1)

[Constructing the Data Model 136](#constructing-the-data-model)

[Creating Pollutant Linkages 138](#creating-pollutant-linkages)

[Displaying a Network Diagram 140](#displaying-a-network-diagram)

[Drawing CSM Objects in Map and Cross-Section
144](#drawing-csm-objects-in-map-and-cross-section)

[Shapes 144](#shapes)

[Annotations 145](#annotations)

[Drawing Water Levels and Defining Aquifers
146](#drawing-water-levels-and-defining-aquifers)

[Accessing Historic Maps 150](#accessing-historic-maps)

[Building Geological Models 153](#_Toc46143850)

[Intro 154](#intro)

[Defining the Model Grid 154](#defining-the-model-grid)

[Creating Model Layers 156](#creating-model-layers)

[Additional Tools 177](#additional-tools)

[3D Graphics 186](#_Toc46143855)

[About 187](#about)

[First Use 187](#first-use-1)

[User Interface 187](#user-interface-1)

[The control panel 188](#the-control-panel)

[Layer Control 188](#layer-control)

[Object Explorer 190](#object-explorer)

[Clipping Controls 190](#clipping-controls)

[Configurations 192](#configurations)

[The Hot Bar 193](#the-hot-bar)

[The Scene 193](#the-scene)

[Settings 194](#settings)

[Borehole Settings 194](#borehole-settings)

[Saving 195](#saving)

[Cross Sections 196](#cross-sections)

[Models 196](#models)

[Surfaces 196](#surfaces)

[Videos 196](#videos)

[Configurations 197](#configurations-1)

# Introduction

This section provides an overview of Groundhog and information about how
to install the software and activate a license.

![](./media/image4.jpeg)

*Photo by Hosea Georgeson on Unsplash*

## About Groundhog

BGS Groundhog Desktop (Groundhog) is geological software created and
maintained by a team at the British Geological Survey. It is available
in two versions, (1) ***Community*** and (2) ***Professional***.

***Community*** is free-to-use, including for commercial applications,
under the UK Open Government Licence. You can use it to import and
explore your site geological data such as maps and boreholes. It allows
you to create custom borehole log templates, develop map line-work and
draw geological cross-sections.

***Professional*** includes all of the features of Community and adds a
range of modelling capability. Use it to create annotated, conceptual
site models. You can also use it to develop full 3D geological framework
models. Professional requires a digital activation key which is
available from our commercial reseller, Land Quality Management
[www.lqm.co.uk](http://www.lqm.co.uk)

This user guide covers both versions. Please note that not all features
described here are available in all versions of the software. Where a
particular feature relates only to the Groundhog Professional version it
will be highlighted like this:

*Professional*

Groundhog is currently BETA software and not all of the available
features of Groundhog are necessarily documented in this guide. Whilst
considerable effort has gone into its design and testing, please be
aware that the software is still in very active development and may not
be completely stable in all situations. We are very happy to receive
feedback from users by email <groundhog@bgs.ac.uk>

A basic set of tutorial videos is available at;

<https://www.youtube.com/channel/UCQc4rWxP2sMPNFhHq6xOthQ/videos>

## Installation

**Please read all steps carefully to ensure correct installation of
Groundhog\!**

You can obtain the installer for Groundhog from the BGS website. There
is only one installer, you do not need a separate installer for
Community and Professional because the two versions are controlled by
the digital license which is available from Land Quality Management.

[www.bgs.ac.uk/groundhog](http://www.bgs.ac.uk/groundhog)

[www.lqm.co.uk](http://www.lqm.co.uk)

Groundhog can only be installed on Windows computers. There are no
specific minimum system requirements to run Groundhog, but you may find
the 3D graphics capability performs better on a computer with a
dedicated graphics card.

The download is in ZIP archive format which contains an installer
executable (setup.exe). Extract the contents of the ZIP file to a
temporary location.

\<Right-click\> on the \<setup.exe\> file and choose \<Run as
administrator\>

**IMPORTANT:** Depending on your organisation’s security policies you
may need assistance from your IT support department to carry out the
software install.

The installation wizard guides you through a series of screens.

You will be prompted to choose an **installation folder**, which is
usually C:\\Program Files\\BGS Groundhog Desktop, but you can install
Groundhog wherever you prefer.

## First Use

The first time you start Groundhog you will see a screen like this.

![](./media/image5.PNG)

If you have previously used Groundhog, you may already have a Groundhog
Home area set up on your computer. However, there have been many changes
in this release, so it is advisable to create a new area, which will
enable Groundhog to copy into this area all the files that are required
for successful running of Groundhog. You may have files which you wish
to keep in your previous Groundhog home area. These can be copied across
to your new Groundhog home area after the install process has completed.

Once you have provided a valid, writable area for the Groundhog home
folder, Groundhog will copy the required folders and files from the
install area to here and Groundhog will be ready to use. If you had
previously upgraded Groundhog to Professional and this is not
automatically enabled in your new Groundhog version, please contact the
Groundhog team.

## Digital License Activation

Groundhog will automatically run in Community mode right away. There is
no need to activate this version in any way. You can get started using
it immediately and use it for as long as you like. We do humbly request
that you consider acknowledging your use of Groundhog in your projects
because this helps our project gain exposure, but you do not have to\!

If you are upgrading to the Professional version of Groundhog you will
need a digital activation key. Keys can be obtained from our commercial
reseller, Land Quality Management Ltd.

[www.lqm.co.uk](http://www.lqm.co.uk)

When you purchase your digital license for Groundhog Professional you
will be asked for your email address. This information is only used for
the purposes of generating a unique digital key and is not stored
anywhere except on your own computer as part of the procedure.

By return you will receive an email containing a digital license
activation key. Start Groundhog and select \<Help\> \<Licensing\>
\<Activate Professional Edition\> from the main menu button.

![](./media/image6.png)

When prompted, enter your email address and the digital key you
received. ![](./media/image7.png)

Once activated you will need to re-start Groundhog to switch to
Professional mode. From now on, Groundhog will run in Professional mode
for the duration of you license.

If you experience any difficulties with your activation, please contact
the person who issued your digital key by email.

#   
Data Objects

This section provides an overview of the key data object types supported
by Groundhog, where they are held in the project structure and how to
both create and import your own data structures into a Groundhog
project.

![](./media/image8.jpeg)

*Photo by João Silas on Unsplash*

## Object Tree

Project data is held as various objects within the object tree. The
object tree is found along the left side of the main user interface
under the \<Workspace\> tab. For more details on the other components of
the user interface please refer to the next main section of the user
guide.

![](./media/image9.png)

This tree panel is a typical multi-level object structure, like a
Windows file explorer navigation panel. Expand the various folder nodes
to explore your data at different levels. Note that not all folder nodes
are available in all versions of Groundhog.

The object tree is arranged into three top-level folders.

![](./media/image10.png)

### Site / Project Folder

Contains the key site investigation data types such as GIS-style point
and shape layers, borehole data, cross-sections, project phase and CSM
information, annotations and linked files such as images.

![](./media/image11.png)

#### Location Layers Folder

This folder holds both GIS-style point layers and also borehole dataset
layers. Borehole layers are effectively treated as a special flavour of
point layer, which is why they are grouped together as Location Layers.

Make new, empty layers using \<right-click\> \<New Layer\>.

![](./media/image12.png)

Enter a name.

![](./media/image13.png)

Click \<Yes\> if you want to make a layer for boreholes, click \<No\> to
make a layer for point data.

![](./media/image14.png)

This is the effect of doing both a borehole layer and a point layer.
Note the different icons.

![](./media/image15.png)

In the case of boreholes, a \<Right-Click\> option allows for data
import. For more details on data import see the main user guide chapter
**Importing & Exporting Data**.

![](./media/image16.PNG)

#### Shape Layers Folder

This folder holds GIS-style shape layers (lines and polygons). Groundhog
makes no distinction between lines and polygons, so they are grouped
together into generic shape layers.

Make new, empty layers using \<right-click\> \<New Layer\>

![](./media/image17.png)

Enter a name.

![](./media/image18.png)

Empty layer is added to the folder.

![](./media/image19.png)

#### Cross-Sections Folder

This is where drawn cross-sections will appear. At the moment, Groundhog
stores all of these in a single folder. Typically you will create new
cross-sections by drawing them in the map – please refer to the
**Drawing Cross-Sections** chapter of the user guide for more
information. However, it is possible to create non-spatially referenced
cross-section objects directly from the tree if you just want to draw a
cross-section without placing it in the map context via \<right-click\>
\<Tools\> \<Create New Cross-Section\>.

![](./media/image20.png)

Enter a name.

![](./media/image21.png)

Specify a length in metres.

![](./media/image22.png)

![](./media/image23.png)

Cross-sections created in this way are all registered starting at \[0,
0\] grid coordinates.

#### Annotations Folder

Annotations layers hold labels, callouts and graphics icons to label and
represent objects within the project or the conceptual site model.
Create a new layer for holding annotation objects via \<Right-Click\>
\<New Layer\>.

*Professional*

![](./media/image24.png)

Enter a name.

![](./media/image25.png)

![](./media/image26.png)

Annotation layers can be created and edited in Professional mode and
viewed in Community mode.

#### Phases Folder

The phases folder is specific to developing conceptual site models
(CSMs) in Groundhog. For more details please refer to the **Developing
Conceptual Site Models** chapter of the user guide. Phases hold the
structure for the CSM, allowing multiple CSMs to be developed and
related back to different phases of a project or site development.
Create a new layer for holding phase objects via \<Right-Click\> \<New
Phase\>.

*Professional*

![](./media/image27.png)

#### Associated Files Folder

Certain types of imported file will appear in this folder when they are
imported. A good example is imported image files which have their own
specific sub-folder.

![](./media/image28.png)

### Models Folder

Contains the key data types related to 2.5D and 3D models and related
information.

![](./media/image29.png)

#### Layer Models Folder

This folder holds layer-based 3D geological models as well as other
types of more 2.5D models such as surface or gridded property models
such as water levels or chemical concentration maps. In Community mode
this folder will display the available models in an existing project. In
Professional mode you are able to create new models and edit existing
models. Creating models is an in-depth topic. Please refer to the
chapter on **Building Geological Models** in this user guide for more
information.

*Professional*

#### Reference Grids Folder

This folder holds any loaded grid layers. Typically, these are imported
from ESRI ASCII grid format. Examples include DEM or DTM layers that you
wish to use as topographic profiles for cross-section drawing and for
acting as the topographic cap of 3D geological models. You can also
bring in other layers such as water levels and engineering layers and
display these in various ways within the software. For more information
on how to get grid data into Groundhog workspaces and projects please
refer to the Importing and Exporting Data section of this user guide.

#### Modelled Objects Folder

This folder can be used to hold reference 3D objects such as models of
infrastructure and buildings and other site objects. These objects can
then be visualized using the 3D graphics window. Typically, such objects
are imported from an OBJ file. Note that OBJ files can only be viewed
using the 3D graphics window in Groundhog.

### System Objects Folder

This folder stores system-level objects which are typically available
across all of your Groundhog projects.

![](./media/image30.png)

#### Pick Lists Folder

This folder holds pick list or dictionary objects. These are pre-set
lists of values and descriptions that are used in various places within
Groundhog to perform lookups. Although you can define your own pick
lists, typically you do not need to interact with this folder in the
current version of Groundhog. Examples include a pick list of possible
contaminants for conceptual site models, or dictionary lookups for
geotechnical data in AGS format.

![](./media/image31.png)

![](./media/image32.png)

#### Templates Folder

This folder holds borehole log templates. When Groundhog is first
installed it will only contain a couple of default templates. You can
add your own blank Template objects and then design them using the log
window. For more information on how to design your own log templates
please refer to the **Working With Borehole Logs** chapter of this user
guide.

To make a new template use \<right-click\> \<New Template\>.

![](./media/image33.png)

Enter a name.

![](./media/image34.PNG)

If Project is selected, this template will be saved when you save the
project and will be available to this project only. Otherwise, when you
choose to save this template, it will be saved in the Ground Home
WORKSPACE folder and will be available to all projects in the future.

The new template is added to the folder and is ready to be worked on.

![](./media/image35.PNG)

#### Web Map Services Folder

This folder lists the available Web Map Services (WMS) in the workspace.
Groundhog comes pre-loaded with BGS WMS layers and these will always be
listed here, so long as Groundhog was able to load them at start up
(requires an internet connection). Typically you will not interact with
the object in this folder directly, but you will be able to add them as
layers to map window.

# User Interface

This section provides an overview of the graphical user interface and
key panels and buttons within Groundhog.

![](./media/image36.jpeg)

*Original photo by Kobu Agency on Unsplash*

## Main Panels

The Groundhog user interface is arranged into a number of panels
containing data objects and graphics. Because Groundhog is a highly
interactive graphical tool you will benefit significantly from using a
good-quality mouse equipped with a mouse wheel – a laptop track-pad is
not a good match with Groundhog.

![](./media/image37.png)

### Main Toolbar **\[1\]**

Contains high-level buttons for key operations.

| ![](./media/image38.png) | Main Menu       | This is the main menu button providing access to a series of high-level functions such as import/export.                                                                                                                                                                                            |
| ------------------------ | --------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![](./media/image39.png) | Open Project    | Opens a file chooser for opening Groundhog projects in the \*.gop file format.                                                                                                                                                                                                                      |
| ![](./media/image40.png) | Save Project    | Opens a file chooser for saving the current session to a Groundhog \*.gop file format.                                                                                                                                                                                                              |
| ![](./media/image41.png) | Open Map Window | Allows the creation of a new map (plan-view) window. When you create a new map window you will be prompted to select the data layers you want to see in the window. The available layers will depend on the data contained within your workspace or project. Press \<Skip\> to open a blank window. |
| ![](./media/image42.png) | Open 3D Window  | Opens the 3D graphics window.                                                                                                                                                                                                                                                                       |

### Session Panel **\[2\]**

A tabbed panel containing a range of session-level objects.

![](./media/image43.PNG)

#### Workspace

This contains the main Object Tree panel with a hierarchical list of all
data objects in the session. For more details please refer to the Object
Tree section of this user guide.

#### Library

![](./media/image44.png)A panel containing a configurable library of
available drawing codes (geology codes and other special codes).
Single-click on an entry to select it as the active drawing code – this
sets the code as active in all windows. The below example shows
“BOULDERS” as the selected drawing code. Note that the special codes
“SHAPE” and “FAULT” are always at the top, and the rest of the list is
sorted alphabetically. Type into the search box to find codes. Click
\<All\> to reset the list back to all values after searching.

![](./media/image45.png)

| ![](./media/image46.png) | Add Code     | Add a drawing code, and optionally a matching colour, to the library. |
| ------------------------ | ------------ | --------------------------------------------------------------------- |
| ![](./media/image47.png) | Add Colour   | Add a colour value to the library.                                    |
| ![](./media/image48.png) | Save Codes   | Saves all current drawing codes to the global workspace.              |
| ![](./media/image49.png) | Save Colours | Saves all current colour values to the global workspace.              |

#### Time Controls

Where data and models have time-stamp information it is possible to use
this as a filter for selective display of a particular time interval
within the project. For example, you may have water level readings with
time-stamps in your borehole data which can be displayed and animated
with time. These features are currently undocumented. Please contact
<groundhog@bgs.ac.uk> for information.

![](./media/image50.png)

### Map Window **\[3\]**

A tabbed component capable of displaying multiple map panels. Each map
panel can display map data layers and can be used for digitizing points
and shapes, constructing cross-section alignments and for placing
borehole locations.

When you create a new map window you will be prompted to select the data
layers you want to see in the map. The icons for each layer indicate the
layer’s data type. The available layers will depend on what data you
have in your workspace and project.

![](./media/image51.png)

The panel on the left shows data layers in the session and the panel on
the right typically displays any web map services that are available.
Single-click on individual entries to select them. If you want to select
multiple layers hold the CTRL key, or to select a range of layer hold
the SHIFT key, as-per typical list controls in Windows programs.

Some layers are ALWAYS available, including ***Cross-Sections*** (the
default cross-sections folder) and ***Graticule*** (a grid overlay with
scale bar and north arrow).

You will also have the option here to **Create New Layer**.

When you save your project it will store the configuration and scale of
all opened map windows ready for your next session.

When you are working in the map view, if you are working in the UK it is
a good idea to always add the default ***Topographic Basemap*** layer
that is included with Groundhog for orientation purposes. Otherwise, you
may wish to import a geo-registered image of your site/project area for
the same purpose.

#### General Navigation

Each graphics panel works like most interactive online map applications.
The mouse is inherently multi-mode, reducing the need to constantly
select different tools to pan and zoom. Click and hold mouse button 1
(typically the left button) and drag the mouse to pan the map around.
Use the mouse wheel to zoom in and out (a good mouse wheel is very
important for effective Groundhog operation). The mouse zoom is
dynamically targeted to the mouse cursor position, allowing for very
rapid and precise zoom in from small scale to large scale maps.

Certain types of object such as cross-sections and boreholes can be
previewed or queried by holding down the SHIFT key whilst hovering over
the object. Here is an example of hovering over a cross-section
alignment whilst holding the SHIFT key.

![](./media/image52.png)

#### Toolbar

![](./media/image53.png)

<table>
<thead>
<tr class="header">
<th><img src="./media/image54.png" style="width:0.29167in;height:0.28125in" /></th>
<th>Zoom To Extent</th>
<th>Zooms to the full extent of all layers in the map panel, or to the currently active layer, if one is selected.</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="./media/image55.png" style="width:0.27083in;height:0.27083in" /></td>
<td>Zoom In</td>
<td>Incrementally zooms the map to a larger scale with each successive click.</td>
</tr>
<tr class="even">
<td><img src="./media/image56.png" style="width:0.26042in;height:0.28125in" /></td>
<td>Zoom Out</td>
<td>Incrementally zooms the map to a smaller scale with each successive click.</td>
</tr>
<tr class="odd">
<td><img src="./media/image57.png" style="width:0.26042in;height:0.26042in" /></td>
<td>Gazetteer</td>
<td><p>Search for places (UK only) by place name, street+placement or county. Examples:</p>
<p>“Nottingham”</p>
<p>“Main Street, Keyworth”</p>
<p>“Rutland”</p></td>
</tr>
<tr class="even">
<td><img src="./media/image58.png" style="width:0.79104in;height:0.22356in" /></td>
<td>Select Drawing Code</td>
<td>Click to open the drawing code library panel in order to change the active drawing code. Also displays the currently active drawing code, including its colour and ornament if they are available.</td>
</tr>
<tr class="odd">
<td><img src="./media/image59.png" style="width:0.27083in;height:0.27083in" /></td>
<td>Print</td>
<td>Send the current map view to a printer.</td>
</tr>
<tr class="even">
<td><img src="./media/image60.png" style="width:0.30208in;height:0.25in" /></td>
<td>Save Image</td>
<td>Save the current map view to an image (JPEG or PNG).</td>
</tr>
<tr class="odd">
<td><img src="./media/image61.png" style="width:0.26042in;height:0.26042in" /></td>
<td>Save PDF</td>
<td>Save the current map view to a PDF document.</td>
</tr>
<tr class="even">
<td><img src="./media/image62.png" style="width:0.53125in;height:0.26042in" /></td>
<td>Toggle Slider</td>
<td><p>The layer slider allows partial view of a user-defined collection of map data layers for rapid comparison. With the slider toggled on, use the mouse to drag the slider position in the map panel. The below example shows the BGS geology map WMS active as the active slider layer on top of a topographic basemap. For information about how to make a particular layer active in the slider refer to the section on the Map Window Layer Control below.</p>
<p><img src="./media/image63.png" style="width:3.63433in;height:1.75101in" /></p></td>
</tr>
</tbody>
</table>

#### Right-Click Operations

The map panel supports a number of context-sensitive right-click
operations. These will depend on whether you are right-clicking on a
specific data object such as a cross-section alignment or a point
object, or whether you are in a “whitespace” area (a non-specific
portion of the panel). In general, a “whitespace” click will present the
following options.

![](./media/image64.png)

<table>
<thead>
<tr class="header">
<th>Centre The Map</th>
<th>Enter a [X, Y] coordinate to centre the map at a specific location.</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Set Map Scale</td>
<td>Enter a value to zoom the map to an approximate scale. For example, enter “10000” to scale to 1:10k. Note that the exact scaling is dependent on screen resolution.</td>
</tr>
<tr class="even">
<td>Find A Place</td>
<td><p>(Gazetteer) Search for places (UK only) by place name, street+place name or county. Examples:</p>
<p>“Nottingham”</p>
<p>“Main Street, Keyworth”</p>
<p>“Rutland”</p></td>
</tr>
<tr class="odd">
<td>Show Grid Info</td>
<td>Show UK grid reference for the mouse cursor position, e.g. <img src="./media/image65.png" style="width:1.64925in;height:0.73092in" /></td>
</tr>
<tr class="even">
<td>Site Investigation</td>
<td>Currently contains one option to hyperlink out to the historic map(s) available from the NLS for the clicked-on location. For more information please refer to the main section on developing conceptual site models.</td>
</tr>
</tbody>
</table>

### Map Window Layer Control **\[4\]**

When you create a new map window you will be prompted to select which
data layers you want to add to the window. You can add layers layer on
too. The layers you choose will be added to this layer control panel.
The panel also has its own toolbar.

#### Toolbar

![](./media/image66.png)

| ![](./media/image67.png) | Add Layers        | Opens a list of available layers that can be added to the map. Note that the list does not present layers which are already in the map.                       |
| ------------------------ | ----------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![](./media/image68.png) | Undo              | Undo on the last operation. **IMPORTANT:** please note that the undo only becomes active when a data layer is made active – i.e., the undo is layer-specific. |
| ![](./media/image69.png) | Redo              | Redo on the last operation. **IMPORTANT:** please note that the redo only becomes active when a data layer is made active – i.e., the redo is layer-specific. |
| ![](./media/image70.png) | Remove All Layers | Clears the map of all data layers.                                                                                                                            |
| ![](./media/image71.png) | Window Settings   | Access high-level settings for the map window.                                                                                                                |
| ![](./media/image72.png) | Background Colour | Change the background colour of the map panel. This can be useful for improving clarity of certain types of data.                                             |

#### Layers

The layers panel lists all currently loaded layers within the map
window. Different map windows can have different layers loaded.

![](./media/image73.png)

Checking the main tick-box on and off controls the visibility of each
layer. In the example below, ***Topographic Basemap*** is not visible in
the map panel, and ***Graticule*** is.

![](./media/image74.png)

The slider controls under the name of each layer control the
transparency of the layers. Slide the bar all the way to the left to
make the layer completely transparent. Slide the bar all the way to the
right to make the layer completely opaque.

![](./media/image75.png)

Single-click on a layer to make it the active layer. Depending on the
layer type this may activate drawing/editing tools, query tools, or it
may do nothing. When a layer is active it displays in orange. Only one
layer can be active at a time. Single-click on the active layer to
de-activate it. The example below shows the Cross-Sections layer as
active.

![](./media/image76.png)

The order of the layers in the panel dictates the drawing order in the
map panel. The layer at the top of the list will be drawn as the top
layer in the map graphics panel. The exception to this is that the
active layer is always drawn on top of everything else.

To change the drawing order of a layer, single-click and hold on the
layer, and drag it to re-position it in the list. In the example below,
the Cross-Sections layer is being dragged upwards.

![](./media/image77.png)

Each layer has four buttons on the right-hand side of its row.

![](./media/image78.png)

| ![](./media/image79.png)                          | Settings            | Access layer-specific settings.                                                                                                                                                             |
| ------------------------------------------------- | ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![](./media/image80.png) ![](./media/image81.png) | Toggle Slider Layer | Toggles the layer in and out of the active slider layer (see above for information about the slider controls). When the toggle button is orange it means the layer is active in the slider. |
| ![](./media/image82.png)                          | Filter              | At the moment this button is disabled for all layers pending future filtering capability.                                                                                                   |
| ![](./media/image83.png)                          | Remove              | Removes the layer from the current window (does ***not*** delete the layer from the project\!)                                                                                              |

There are a number of operations available by right-clicking in any
blank or “whitespace” portion of the layer control.

![](./media/image84.PNG)

**Add Layers** is the same as the Add Layers button at the top of the
layer control panel. The other options allow for the creation of new
data layers directly in the map, but (depending on version) are
currently restricted to Point, Borehole, Shape and Annotation\*.

\* *Professional*

#### Active Layer: Draw, Edit & Identify

Depending on the type of the layer certain editing, drawing and querying
operations may be available on the active map layer. When a layer can be
edited or drawn into it typically presents a tool palette in the map
graphics panel when the layer becomes active. The example below shows
the palette which has appeared in the top-left of the map panel by
making a shape layer active in the layer control.

![](./media/image85.png)

You can move the palette around in the map panel by dragging the green
bar along the top of the box. Note that the palette becomes less
transparent when the mouse cursor is over it.

![](./media/image86.png)

For more detailed information on the various tools available in the
palette, depending on the layer type, please refer to the section
**Drawing Points & Shapes** within this user guide.

When a layer is active you may see variations on the right-click option
available in the map window and also depending on whether you have
right-clicked on an object or whitespace.

Some layers have identify capability when they are active. The identify
operation is not a separate tool within groundhog – instead, with a
layer active, just single-click on an object or location. A good example
is the BGS WMS layers where the identify is active everywhere on the
geology map. If the identify query yields results they will be displayed
in the lower half of the map window layer control.

![](./media/image87.PNG)

Notice the two options circled in red. These are **Copy the identify
data to the clipboard** and **Add the lexicon code to the library
panel**.

### Cross-Section Window **\[5\]**

A tabbed component capable of displaying multiple cross-section panels.
Each cross-section panel can display profile data layers and can be used
for drawing geological interpretations, viewing borehole transects and
digitizing points and shapes. Unlike the map window, you can’t just
create a new, empty window. To open a section window you must open a
specific cross-section object. You can do this either by double-clicking
on its entry in the object tree, or by right-click on the section
alignment in a map window.

When you open a cross-section in the cross-section window, some data
layers are ALWAYS available, including ***Terrain Profile*** (the
topographic profile for the cross-section), ***Geology*** (for drawing a
geological interpretation), ***Graticule*** (a grid overlay with scale
bars) and ***Boreholes*** (even if there are no boreholes in the
alignment).

When you save your project it will store the configuration and scale of
all opened cross-section windows ready for your next session.

#### General Navigation

Each graphics panel works like most interactive online map applications.
The mouse is inherently multi-mode, reducing the need to constantly
select different tools to pan and zoom. Click and hold mouse button 1
(typically the left button) and drag the mouse to pan the cross-section
around. Use the mouse wheel to zoom in and out (a good mouse wheel is
very important for effective Groundhog operation). The mouse zoom is
dynamically targeted to the mouse cursor position, allowing for very
rapid and precise zoom in from small scale to large scale views.

#### Toolbar

![](./media/image88.png)

<table>
<thead>
<tr class="header">
<th><img src="./media/image89.png" style="width:0.72917in;height:0.35417in" /></th>
<th>Vertical Exaggeration</th>
<th>Sets the vertical exaggeration for the panel. Contains a list of pre-set values and can also be typed into for custom values.</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="./media/image90.png" style="width:0.27083in;height:0.27083in" /></td>
<td>Zoom To Extent</td>
<td>Zooms to the full extent of all the cross-section.</td>
</tr>
<tr class="even">
<td><img src="./media/image91.png" style="width:0.22917in;height:0.25in" /></td>
<td>Marquee Zoom</td>
<td>Draw a box to zoom to that area of the panel.</td>
</tr>
<tr class="odd">
<td><img src="./media/image92.png" style="width:0.30208in;height:0.28125in" /></td>
<td>Incrementally zooms the panel to a smaller scale with each successive click.</td>
<td>Incrementally zooms the cross-section to a smaller scale with each successive click.</td>
</tr>
<tr class="even">
<td><img src="./media/image93.png" style="width:0.28125in;height:0.30208in" /></td>
<td>Refresh</td>
<td>Refreshes the graphics panel.</td>
</tr>
<tr class="odd">
<td><img src="./media/image94.png" style="width:0.75in;height:0.29167in" /></td>
<td>Select Drawing Code</td>
<td>Click to open the drawing code library panel in order to change the active drawing code. Also displays the currently active drawing code, including its colour and ornament if they are available.</td>
</tr>
<tr class="even">
<td><img src="./media/image59.png" style="width:0.27083in;height:0.27083in" /></td>
<td>Print</td>
<td>Send the current cross-section view to a printer.</td>
</tr>
<tr class="odd">
<td><img src="./media/image60.png" style="width:0.30208in;height:0.25in" /></td>
<td>Save Image</td>
<td>Save the current cross-section view to an image (JPEG or PNG).</td>
</tr>
<tr class="even">
<td><img src="./media/image61.png" style="width:0.26042in;height:0.26042in" /></td>
<td>Save PDF</td>
<td>Save the current cross-section view to a PDF document.</td>
</tr>
<tr class="odd">
<td><img src="./media/image62.png" style="width:0.53125in;height:0.26042in" /></td>
<td>Toggle Slider</td>
<td><p>The layer slider allows partial view of a user-defined collection of cross-section data layers for rapid comparison. With the slider toggled on, use the mouse to drag the slider position in the graphics panel. The below example shows the Geology layer as the active slider layer on top of a Terrain Profile layer. For information about how to make a particular layer active in the slider refer to the section on the Cross-Section Window Layer Control below.</p>
<p><img src="./media/image95.png" style="width:3.53671in;height:1.14181in" /></p></td>
</tr>
</tbody>
</table>

#### Right-Click Operations

The map panel supports a number of context-sensitive right-click
operations. These will depend on whether you are right-clicking on a
specific data object such as a geology line or a shape object, or
whether you are in a “whitespace” area (a non-specific portion of the
panel). In general, a “whitespace” click will present the following
options.

![](./media/image96.png)

<table>
<thead>
<tr class="header">
<th>Create Line [CODE]</th>
<th>Allows creation of a fixed-elevation geology line using the currently active drawing code.</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>New Shape Layer</td>
<td>Creates a new cross-section shape layer which you can draw into.</td>
</tr>
<tr class="even">
<td>New Annotation Layer</td>
<td><p>Creates a new annotation layer which can be used to add labels, arrows and graphics to the cross-section.</p>
<p><em>Professional</em></p></td>
</tr>
</tbody>
</table>

### Cross-Section Window Layer Control **\[6\]**

This panel lists the data layers which are currently added to the
cross-section window. The panel also has its own toolbar.

#### Toolbar

![](./media/image97.png)

| ![](./media/image67.png) | Add Layers        | Opens a list of available layers that can be added to the window. Note that the list does not present layers which are already in the list. |
| ------------------------ | ----------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| ![](./media/image68.png) | Undo              | Undo on the last operation. **IMPORTANT:** please note that the undo is global across all layers.                                           |
| ![](./media/image69.png) | Redo              | Redo on the last operation. **IMPORTANT:** please note that the redo is global across all layers.                                           |
| ![](./media/image71.png) | Window Settings   | Access high-level settings for the cross-section window.                                                                                    |
| ![](./media/image72.png) | Background Colour | Change the background colour of the graphics panel. This can be useful for improving clarity of certain types of data.                      |

#### Layers

The layers panel lists all currently loaded layers within the
cross-section window. Different windows can have different layers
loaded.

![](./media/image98.png)

Checking the main tick-box on and off controls the visibility of each
layer. In the example below, ***Terrain Profile*** is not visible in the
section panel, and ***Graticule*** is.

![](./media/image99.png)

The slider controls under the name of each layer control the
transparency of the layers. Slide the bar all the way to the left to
make the layer completely transparent. Slide the bar all the way to the
right to make the layer completely opaque.

![](./media/image100.png)

Single-click on a layer to make it the active layer. Depending on the
layer type this may activate drawing/editing tools, query tools, or it
may do nothing. When a layer is active it displays in orange. Only one
layer can be active at a time. Single-click on the active layer to
de-activate it. The example below shows the ***Geology*** layer as
active.

![](./media/image101.png)

The order of the layers in the panel dictates the drawing order in the
cross-section panel. The layer at the top of the list will be drawn as
the top layer in the graphics panel. The exception to this is that the
active layer is always drawn on top of everything else.

To change the drawing order of a layer, single-click and hold on the
layer, and drag it to re-position it in the list. In the example below,
the Cross-Sections layer is being dragged upwards.

![](./media/image102.png)

Each layer has four buttons on the right-hand side of its row.

![](./media/image78.png)

| ![](./media/image79.png)                          | Settings            | Access layer-specific settings.                                                                                                                                                             |
| ------------------------------------------------- | ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![](./media/image80.png) ![](./media/image81.png) | Toggle Slider Layer | Toggles the layer in and out of the active slider layer (see above for information about the slider controls). When the toggle button is orange it means the layer is active in the slider. |
| ![](./media/image82.png)                          | Filter              | At the moment this button is disabled for all layers pending future filtering capability.                                                                                                   |
| ![](./media/image83.png)                          | Remove              | Removes the layer from the current window (does ***not*** delete the layer from the project\!)                                                                                              |

There are a number of operations available by right-clicking in any
blank or “whitespace” portion of the layer control.

![](./media/image103.PNG)

The **Add Layer** option presents the same dialogue as choosing this
option from the top of this panel. The other options allow for the
creation of new data layers directly in the section, but (depending on
version) are currently restricted to Shape and Annotation\*.

\* *Professional*

#### Active Layer: Draw, Edit & Identify

Depending on the type of the layer certain editing, drawing and querying
operations may be available on the active cross-section window layer.
When a layer can be edited or drawn into it typically presents a tool
palette in the graphics panel when the layer becomes active. The example
below shows the palette which has appeared in the top-left of the map
panel by making the Geology layer active in the layer control.

![](./media/image104.png)

You can move the palette around in the panel by dragging the green bar
along the top of the box. Note that the palette becomes less transparent
when the mouse cursor is over it.

![](./media/image105.png)

For more detailed information on the various tools available in the
palette, depending on the layer type, please refer to the **Drawing
Points, Shapes & Annotations** and the **Drawing Cross-Sections**
chapters within this user guide.

When a layer is active you may see variations on the right-click option
available in the cross-section window and also depending on whether you
have right-clicked on an object or whitespace.

### Status Bar **\[7\]**

The status bar displays certain information and controls related to the
current session.

#### Global Borehole Log Template 

User this to set the default (global) borehole log template to use for
the session.

![](./media/image106.png)

#### Progress Bar

This displays the progress of certain processing operations, such as
project loading and model building operations.

![](./media/image107.png)

# Importing & Exporting Data

This section provides details of the various import and export
capabilities of Groundhog.

![](./media/image108.jpeg)

*Photo by Mika Baumeister on Unsplash*

## Images

You can import images into your project in JPG/JPEG and PNG file
formats. There are several ways to import them.

\<Main Menu\> \<Import\> \<Image\>.

![](./media/image109.png)

\<Right-Click\> on Images sub-folder.

![](./media/image110.png)

Drag image file from folder or desktop.

![](./media/image111.png)

Drag image from web browser (browser dependent, test using Google
Chrome).

![](./media/image112.png)

If you have difficulty dragging an image from the web browser,
right-click on the image and open it in a new browser tab and try again.

When images are loaded they appear in the object tree under \<Site /
Project\> \<Associated Files\> \<Images\>.

![](./media/image113.png)

Double-click the entry in the tree, or use \<Right-Click\> \<View
Image\> to view the image.

![](./media/image114.png)

![](./media/image115.png)

If the image is geo-registered and the world file is present, Groundhog
will load the image together with its geo-registration information. When
you add the image to a map window as a new layer it will display in the
correct spatial location.

If you have an image that is not geo-registered, you can still add it to
a map window as a layer. By default it will fill the available panel.
Make the image layer editable and use the blue drag handles to register
the image to the correct location.

![](./media/image116.png)

![](./media/image117.png)

![](./media/image118.png)

When the project is saved, Groundhog will generate a world file for the
registration information.

## Shapefiles

Groundhog has basic support for ESRI shapefiles (\*.shp). However, the
shapefile format is proprietary and Groundhog relies on 3<sup>rd</sup>
party libraries to support the import filter. Therefore, not all
features of the file format are necessarily available, but most Point
and Line type files should load. Complex multi-polygon files may be less
reliable.

Import the file using \<Main Menu\> \<Import\> \<Shapefile (\*.shp)\>.

![](./media/image119.png)

Alternatively, drag the \*.shp file into Groundhog from a folder or the
desktop.

The data is imported as a new folder under the Location Layers (points)
of Shape Layers (polyline), respectively. These folders can be added to
any map window as a layer for display.

![](./media/image120.png)

A right-click option provides access to a simple view (non-editable) of
the attribute table.

![](./media/image121.png)

![](./media/image122.png)

You can export Point and Shape type layers to shapefile format using
\<Right-Click\> \<Import / Export\> \<Export\> \<Shapefile (\*.SHP)\>

![](./media/image123.png)

![](./media/image124.png)

## ASCII Grids

ASCII grids can be imported and used either to display profiles or set
as the surface layer (topography, i.e. DEM/DTM). Groundhog supports
grids in ESRI’s ASCII format.

<https://en.wikipedia.org/wiki/Esri_grid>

The grid data can be imported manually via \<Main Menu\> \<Import\>
\<ESRI ASCII Grid (\*.asc)\>

![](./media/image125.png)

Alternatively, and especially for a series of files, paste them into
either the WORKSPACE or the PROJECT directory and restart Groundhog.

When ASCII grids are loaded into Groundhog they are converted to a
binary equivalent called a BGRID. This is so that the data can be
queried more efficiently without loading the whole grid to memory.

Loaded grids appear in the object tree under \<Models\> \<Reference
Grids\> and each label displays the extent of the grid object.

![](./media/image126.png)

At present there is only a simple way to display the grid in the map,
and that is as a simple extent rectangle. To do so, highlight the
desired grid object in the tree and a blue rectangle will appear in the
map window showing the extent of that grid.

![](./media/image127.png)

You can set a grid to be the default topographic surface layer within
the project. This means the grid will be used as the basis of terrain
profile (topography) generation in cross-sections by default.

\<Right-Click\> \<Set As ‘Surface Layer’\>

![](./media/image128.png)

The currently set ‘surface layer’ grid will be displayed as bold in the
object tree list.

![](./media/image129.png)

## OBJ Files

3D objects can be imported from the industry-standard OBJ data format.

![](./media/image130.png)

Loaded objects will appear in the data tree.

![](./media/image131.png)

OBJ objects can be added to the 3D view.

# Working With Borehole Logs

This section provides details on how to import and display your borehole
data, make edits to the data and design your own custom log templates.
It includes discussion of how to handle geotechnical and geophysical
borehole data in AGS and LAS formats.

![](./media/image132.jpeg)

*Photo by Sven Mieke on Unsplash*

## Borehole Data Import

Groundhog supports a range of borehole data models and import options.
When borehole data is loaded it will appear in the object tree under
***Site / Project \> Location Layers***.

![](./media/image133.PNG)

Borehole datasets are arranged into folders. Each data import will
create a separate folder. Within each folder there are three types of
sub-folder;

1.  Attributes,

2.  Data Tables,

3.  0, 1, or more borehole objects.

The **Attributes** sub-folder contains the attribution at the dataset or
project level. The **Data Tables** sub-folder contains associated
tabular data (see later section on tabular data). Each **Borehole**
object acts as a sub-folder and contains the geology/interval log and
any additional metadata attributes for each individual location.

### CSV/TXT Format

You can import borehole data from delimited text files. The data can
either be contained in a single file, or in two files (one containing
the collar information and one containing the log data). If the data is
split between two files make sure each file contains an ID field that
can be used to match the logs to the correct collar.

Here is a very simple example of a suitable format as text and as loaded
into MS Excel. **This is a single file** containing the collar
information and the geology log for **two boreholes**, BH 1 and BH 2.
Note that because this is a single file, **the collar information is
repeated for each geology interval**. It is also possible to store the
collar information and the geology log **in separate files**.

In this example the NAME field can be used as the borehole ID. Groundhog
can import as many fields as you like for each log interval, so you can
include fields for lithology, litho-stratigraphy, descriptions, etc. The
field names are not prescribed as they will be mapped during the import.

![](./media/image134.PNG)

![](./media/image135.PNG)

In the following example the collar and geology data are split between
two separate CSV files. Note that both files have a field that contains
the name of the borehole, which will be mapped as the ID field for
matching up the geology records to the correct location. This field does
not have to be called NAME, it can be called anything as it will be
mapped on import. It can also have different names in the collar and
geology files. The file names are also not important.

![](./media/image136.PNG)

Collar.csv

![](./media/image137.PNG)

Geology.csv

![](./media/image138.PNG)

### Importing CSV

There are two routes to import boreholes from CSV.

1.  Combined collar and geology import,

2.  Individual import.

#### Combined Import

This option allows provides a short-cut to import both the collar and
geology data in a single step. It will work whether your data is split
into separate collar and geology data files, or merged into a single
file.

***Main Menu \> Import \> Borehole Data***

![](./media/image139.PNG)

The dialog contains a tab for the collar and a tab for the geology.
Click on the ***Choose File*** button on each tab to load up the data.

![](./media/image140.PNG)

The names of the fields in the data file are listed to the left of the
panel. Ignore the UNIT and TYPE columns.

Use the drop-down options in the **ALIAS** column to tell Groundhog the
meaning of each field in the imported data file. Choose **\<\< Exclude
From Import \>\>** for any redundant fields. The required fields for the
import type are marked in red in the drop-down list of possible
**ALIAS** values.

![](./media/image141.PNG)

In this example we are working with the combined data file that contains
both the collar and geology data. Note the mappings, including the
fields that have been excluded.

![](./media/image142.PNG)

Note that the **LEVEL** field from the data file (which is the start
height or elevation of the borehole) has been mapped to **Z**. This
field is not mandatory for the import, but if there is a value available
for this you should always map it.

Next, switch to the Geology tab and bring in the CSV file containing the
geology data. Again, in this example, the data is in the same single
file as the collar data.

The fields required for the geology import are different than for the
collar data. Again, they are highlighted in red in the drop-down list.

![](./media/image143.PNG)

![](./media/image144.PNG)

**IMPORTANT:** Make sure to use the correct field to map the **LOCATION
ID** alias, as this will be used to match the records between the collar
and geology data. GEOL and DESCRIPTION are both important fields that we
want to see in the geology log, but they do not need to be mapped to any
specific expected Groundhog field. So, they will just be imported using
the name used in the data file.

Click ***OK***.

If you have missed out any required fields in the **ALIAS** mappings,
you will see this message. Go back into the mappings panels and correct
these.

![](./media/image145.png)

Otherwise, the import will proceed and a new borehole dataset folder
will be created in the data tree.

![](./media/image146.PNG)

#### Individual Import

This option allows the borehole dataset to be assembled one data file at
a time. It also leads into the import of generic tabular data which is
described in the following section.

First, create an empty borehole dataset folder in the tree.

![](./media/image147.PNG)

Enter a name for the folder.

![](./media/image148.png)

When prompted, click ***Yes*** to specify a borehole layer.

![](./media/image149.PNG)

The new, empty borehole dataset folder will be created in the data tree.

Use ***Right-Click \> Import / Export \> Import \> Collar*** on the
borehole folder and select the file containing the collar data.

![](./media/image150.PNG)

![](./media/image151.png)

Use the pull-down ALIAS options to map the imported fields to the fields
expected by Groundhog and click Apply. In the case of collar data this
could be;

  - LOCATION ID

  - X

  - Y

  - Z (collar height or ground level)

![](./media/image152.png)

The imported collar entries are added to the data tree.

![](./media/image153.png)

Next, import the geology data using ***Right-Click \> Import /Export \>
Import \> Geology Intervals*** on the borehole folder and select the
file containing the geology interval/log data.

![](./media/image154.PNG)

![](./media/image155.png)

If the depth values in the log file are elevation, as opposed to
depth-down-hole, check the special option box on the right of the file
chooser dialog (**NOTE:** this function will only work if the collar has
a Z, or ground level, value).

Map the fields using the drop-down options in the **ALIAS** column of
the import screen. Required fields are highlighted in red. Click Apply.

![](./media/image156.PNG)

Inspect the data tree to see the imported geology logs.

![](./media/image157.PNG)

### Importing Tabular Data

Besides the collar data and geology interval logs, Groundhog can also
import any arbitrary down-hole data in tabular format. For example,
sample and test data (in-situ and laboratory), geophysical measurements,
installation and monitoring data, etc.

It is important to note that tabular data is held at the borehole
dataset folder level and not against individual boreholes.

![](./media/image158.PNG)

The rows within each table are mapped to the appropriate borehole object
using an ID field.

To import a table of data use ***Right-Click \> Import / Export \>
Import \> Tabular Data***

![](./media/image159.PNG)

Use the file chooser dialog to select the CSV file containing the data.

![](./media/image160.png)

Next, use the field mapping dialog to specify the meaning of the key
fields in the import file and to choose whether to exclude any. When
importing tabular data you will need to map the fields within the data
file to those expected, or treated specially, within Groundhog. This is
done by selecting ALIAS values for each field in the data file in the
mapping dialog. All fields are imported with their original name from
the data file, but the ALIAS field tells Groundhog to treat particular
fields as special values, such as depth, id, etc. Use the pull-down
options against each field in the mapping dialog. You can also choose to
exclude specific fields from the import. The image below shows a set of
mappings for a typical import.

![](./media/image161.png)

You can also preview the data in the file using the Data tab, **but
currently you can’t edit the data**.

![](./media/image162.png)

Here is an example of a CSV file viewed in Excel, containing sample
information for two boreholes with FROM and TO depth fields.

![](./media/image163.PNG)

![](./media/image164.PNG)

Once imported, the table will appear in the data tree.

![](./media/image165.PNG)

Double-click on the table entry, or use right-click, to view the table
and edit the field mappings once loaded.

![](./media/image166.PNG)

The following example shows how to import a depth-related value, such as
geophysical test data, with a single test DEPTH field.

![](./media/image167.PNG)

![](./media/image168.png)

The following image below shows how the data from the tables can be used
in log templates, for example.

![](./media/image169.PNG)

### 

### Importing AGS Format Data

The AGS standard is a file format for the transfer of factual site
investigation data in the UK and elsewhere. It is supported as an import
option within Groundhog and, once imported, is treated as a set of data
tables, much the same as a standard CSV import would be.

From the main menu, choose ***Import \> AGS Data Format Tables***

![](./media/image170.PNG)

Select the AGS file (v3.1 and v4 is are both supported). The imported
data will take the form of a borehole dataset folder. Expand the folder
to explore the imported geology logs (if present in the data file) and
the various test and descriptive tables.

![](./media/image171.PNG)

Sample AGS data taken from the AGS data format v4 example data file.

### Importing LAS Format Data

Groundhog supports the industry-standard Canadian Well Logging LAS data
format for geophysical wireline log data. The imported data is stored in
Groundhog data tables, similar to data imported from a tabular format
such as CSV.

From the main menu, choose ***Import \> Well Log Data (\*.las)***

![](./media/image172.PNG)

The collar data is attached to the borehole entry in the data tree as a
series of attributes.

![](./media/image173.PNG)

The test data appears as a table called Curve Data under the Data Tables
sub-folder of the borehole dataset folder (example file shown courtesy
of Kansas Geological Survey download portal -
<http://www.kgs.ku.edu/Magellan/Logs/>).

![](./media/image174.PNG)

Double-click the table, or use right-click to view and edit the table
mappings and to preview the data values (not editable).

![](./media/image175.png)

![](./media/image176.png)

The data in the table can be used in log templates, as-per any tabular
data.

![](./media/image177.png)

### BGS Borehole Records

There are two ways to view borehole records held by the BGS, (1) view
original driller’s logs and (2) download AGS data.

#### Viewing Driller’s Logs From BGS

BGS holds driller’s logs as scanned images for many of the borehole
records. The locations of the records are available as a WMS (Web Map
Service) which can be displayed in the Groundhog map window as a layer.

![](./media/image178.png)

From the panel on the right of the layer selection dialog, select the
layer called **\[GeoIndex Boreholes theme\] Borehole records**.

![](./media/image179.png)

Zoom into an area to see the available records as a point layer.

![](./media/image180.png)

Make the WMS points layer active by clicking on it in the layer control.
When it is active it will turn orange. Now that the layer is active,
click on any dot in the map to perform an identify query. The results
will display in a panel on the right.

![](./media/image181.png)

In the identify results panel, click on the borehole stick icon to
hyperlink to the BGS record (opens in default web browser).

![](./media/image182.png)

![](./media/image183.png)

#### Downloading AGS Data From BGS

The BGS’ NGDC Digital Data Deposit Application can be used by industry
and the public to deposit data into the BGS archives.

<http://transfer.bgs.ac.uk/ingestion>

Any AGS format data locations that are ingested are served back at as a
WMS (Web Map Service) layer that can be displayed and queried within
Groundhog.

In a map window, open the add layers dialog.

![](./media/image178.png)

From the panel on the right of the layer selection dialog, select the
layer called **\[AGS Export\] Boreholes**.

![](./media/image184.png)

Zoom into an area to see the available records as a point layer.

![](./media/image185.png)

Make the WMS points layer active by clicking on it in the layer control.
When it is active it will turn orange. Now that the layer is active,
click on any dot in the map to perform an identify query. The results
will display in a panel on the right.

![](./media/image186.png)

![](./media/image187.png)

Click on the AGS save button in the identify results panel to attempt a
download of the corresponding AGS data from the BGS database. Not all
records have AGS data attached, but most should work.

![](./media/image188.png)

Click \<No\>

![](./media/image189.png)

![](./media/image190.png)

The data will appear in the object tree as a new borehole dataset folder
ad can be worked with like any imported borehole dataset.

## 

## Displaying Boreholes

Borehole data is displayed using custom templates. These are
column-based design templates and you can create your own within
Groundhog. Once you have designed your template you can re-use it in
each session and you can also share it with other Groundhog users.

### Creating Borehole Log Templates

The first step is to create a new, blank template in the object tree via
\<System Objects\> \<Templates\> \<right-click\> \<New Template\>

![](./media/image191.png)

Enter a name.

![](./media/image192.png)

Next, send a borehole to the blank template using \<right-click\> \<View
Borehole Log\> either in the object tree on from a borehole position in
a map window.

![](./media/image193.png)

![](./media/image194.png)

When prompted, choose the new template that you just created.

![](./media/image195.png)

Decide whether to always use this template for this borehole.

![](./media/image196.png)

The borehole will attempt to display in the blank template, but will
most likely look incorrect/blank because at this stage the template has
no way of knowing which data fields to display. To make the template
look how you want it you will need to make some edits to the design.

![](./media/image197.png)

### Editing Borehole Log Templates

This section assumes a new, blank template (see previous section) is the
starting point for creating a template design, but the same principles
also apply to existing templates.

Switch the template to edit mode. You can use either the edit mode
button, or you can right-click in the template itself and choose \<Edit
Template\>.

![](./media/image198.png)

When the log template is in edit mode, the border lines will turn blue
and an editing label will appear in red at the top of the page. To exit
edit mode, press the \<Stop Editing Template\> button again.

![](./media/image199.png)

Groundhog arranges the log design into three areas, the header, columns
and footer.

![](./media/image200.png)

The size and width of the top-level areas can be modified by hovering
over a template line and dragging it. When a line is drag-able, as the
mouse hovers over it, it will highlight as an extended green line.

![](./media/image201.png)

#### Header

The header is a tabular component which can be used to display a
document title, data fields, free-text labels and a corporate logo. To
edit the contents of a cell, use right-click.

![](./media/image202.png)

![](./media/image203.png)

![](./media/image204.png)

The field and title values can be free text or taken from data fields in
the borehole data itself. When you edit such a cell, you will be
presented with the field editing dialog. This dialog presents a list of
available dynamic fields, both pre-set (e.g. date/time, page number) and
data-driven (e.g. borehole attributes).

![](./media/image205.png)

The text field at the top contains the value that will be displayed. The
list below presents a range of data fields that can be inserted into the
value to create dynamic values. The available data fields are a mixture
of fields found in the borehole data and default fields such as
date/time and page numbers. The output value can be formed of any
combination of free-text and dynamic fields. To add a dynamic field to
the value, place the cursor at the desired position in the Value field,
highlight the desired data field in the list below, and click the
\<Insert\> button. Note that dynamic fields must have a space each side
of them.

Here is an example of a field value using a field called LOCA\_ID and
some free-text. LOCA\_ID is a field typically found in UK AGS format
geotechnical log files and is just used here as an example of a field.
The fields available will depend on the format and nature of your own
borehole data.

![](./media/image206.png)

And this is how the value appears in the template once applied.

![](./media/image207.png)

You can also add values from any of the data tables attached to the
borehole dataset using the Table Lookup button.

![](./media/image208.png)

Drill down to extract the desired field. In the example below, the
project name field is being added from an AGS 4 dataset. In the case of
AGS this is the PROJ\_NAME field within the attached PROJ table. The
Label field is not used in this feature.

![](./media/image209.png)

If you select a field from a table that has multiple rows, the value
will be assigned according to the following policy;

1.  If the data table contains a borehole ID field, the first row with a
    matching ID will be used as the basis of the query,

2.  If the data table has no ID field, the first row in the table will
    be used as the basis of the query.

You can add/remove columns and rows to the header table using
right-click.

![](./media/image210.png)

Here is an example of a header table with a number of rows and columns
added and some field defined.

![](./media/image211.png)

You can add a logo to the template using \<right-click\> \<Import Logo
From \[Workspace or File\]\>.

![](./media/image212.png)

Select the image to use. Here we are choosing one that is already loaded
as an image in the session or workspace.

![](./media/image213.png)

![](./media/image214.png)

#### Columns

The columns area is where the borehole log data is placed. It is
arranged as one or more data columns. Each column can have a different
graphical type and pull on different data fields within the borehole.
Each column is divided into a header and a log column.

Start by adding a new column to the blank template. Hover over the
header portion of a pre-existing log column and \<Insert Column on
\[Left or Right\]\>.

![](./media/image215.png)

A prompt asks you to choose a graphical column type. Note that not all
column types will work with all types of borehole or data field. Here we
are adding a text column.

![](./media/image216.png)

The available column types are;

  - **Borehole Installation** – can be used to show backfill and pipe
    installation details.

  - **Curve** – plots values at a depth in the form of a curve or a
    series of dots, for example a Gamma Log or CPT log.

  - **Depth Scale** – a vertical depth scale in metres or feet.

  - **Interval (Geology Log)** – used to plot geology intervals in an
    interpreted log.

  - **Marker Depths** – plots depth boxes for intervals within the log.

  - **Samples** – displays depths and types of samples.

  - **Test Results** – displays any test result data as a label,
    including in-situ and laboratory test values. Can also be used to
    display water levels.

  - **Text** – shows any text-based data down the log, for example a
    detailed stratum description.

  - **Water Strikes** – shows strike and rest levels as symbols.

When a new column is inserted into the template typically you will be
prompted to choose the field containing the data to use for that column.
The exception is the depth scale, which is not based on a data field.
The prompt usually takes the form of a drill-down. Select the folder or
table, and then the field containing the data. Below are some examples
based on an imported AGS 4 file;

![](./media/image217.png)

GEOL\_LEG field from the geology log (geology intervals folder)

![](./media/image218.png)

ISPT\_MAIN data field in the ISPT test result table.

Come column types show more than one data field simultaneously. For
example the borehole installation column, which can show backfill and
pipe data together. In such cases the mapping dialog will contain
multiple tabs allowing the necessary field to be mapped.

![](./media/image219.png)

Once the data field mapping is completed, the column will be added to
the template. You can access and edit the settings after the column is
added using \<Right-Click\> \<Edit TYPE Column\> \<Column Settings\> in
the header of each column, for example;

![](./media/image220.png)

![](./media/image221.png)

The settings dialog will look slightly different, depending on the type
of the column. Often, the settings dialogs have additional settings that
are not accessible when you first add the column, so they are worth
exploring.

To remove a column from the template \<Right-Click\> on the column
header and select \<Delete Column\>

![](./media/image222.png)

Here are typical examples of each of the available column types, shown
here using an example AGS 4 format borehole data file and a LAS format
geophysical file.

**Borehole Installation Column**

![](./media/image223.png)

Example using BKFL.BKFL\_LEG for the backfill mapping and
PIPE.PIPE\_TYPE for the pipe installation mapping.

**Curve Column**

![](./media/image224.png)

Example using GR field from an imported LAS Curve Data table.

**Depth Scale Log**

![](./media/image225.png)

Showing feet and metres scales.

**Interval (Geology Log) Column**

![](./media/image226.png)

Example using GEOL.GEOL\_LEG field.

**Marker Depths Column**

![](./media/image227.png)

Example using GEOL.GEOL\_LEG field, shown against a corresponding
interval column.

**Samples Column**

![](./media/image228.png)

Example using SAMP.SAMP\_TYPE field.

**Test Results Column**

![](./media/image229.png)

Example using ISPT.ISPT\_REP field.

**Text Column**

![](./media/image230.png)

Example using GEOL.GEOL\_DESC field.

**Water Strikes Column**

![](./media/image231.png)

Example using dual mapping of WSTD.WSTD\_DPTH and WSTD.WSTD\_POST for
strike and rest level.

Here is an example with several different column types added to a
template based on AGS data.

![](./media/image232.png)

**IMPORTANT:** As you build up your template it is a good idea to save
it regularly. Templates are held in the global workspace of Groundhog so
that they can be used across all of your projects, so they need to be
saved separately.

#### Footer

Having added some columns, let’s set up the template footer.

![](./media/image233.png)

![](./media/image234.png)

#### Page Setup

And finally, let’s set the page size to A4, set the number of metres to
display per-page, and fit the template to the page.

![](./media/image235.png)

![](./media/image236.png)

Flip to landscape orientation.

![](./media/image237.png)

\<Right-Click\> anywhere \<Fit To Page\>

![](./media/image238.png)

![](./media/image239.png)

Here is an example of a wireline log style template.

![](./media/image240.png)

Note that the design template can also be used in the cross-section
view.

![](./media/image241.png)

## 

## Editing Borehole Data

You can enter and edit borehole data directly within Groundhog. To
demonstrate this, we will create a blank borehole dataset to work into.

From the object tree Location Layers folder \<right-click\> \<New
Layer\>.

![](./media/image242.png)

![](./media/image243.png)

![](./media/image244.png)

Or from the layers panel of a map window.![](./media/image245.png)

![](./media/image243.png)

If the new layer is not already visible in a map window, add it.

![](./media/image246.png)

![](./media/image247.png)

Make the layer active in the map by clicking on it in the layers panel
(turns orange when active).

![](./media/image248.png)

In the drawing palette, pick up the borehole placement tool (turns
orange when selected).

![](./media/image249.png)

Single-click in the map to place new borehole object. Borehole collar
dialog appears. Enter a name for the new borehole, adjust X,Y as desired
to set a specific location. Also, if you have a suitable DEM/DTM loaded
and set as the surface layer in the session, click the \<Set from
Surface Layer\> button for the start height (ground level) field to set
an elevation value for the top of the borehole, or type one manually if
you have a more accurate one.

![](./media/image250.png)

Borehole appears in the map. Add as many boreholes as you like and then
de-activate the borehole layer in the map.

![](./media/image251.png)

Hover the mouse over a borehole location and select \<right-click\>
\<New Geology Log\>

![](./media/image252.png)

When prompted for a name for the log, just enter “1”.

![](./media/image253.png)

This creates a geology interval log with 1m interval of SAND added to
initialize the data structure. The log turns blue in the map to indicate
the presence of a geology log.

![](./media/image254.png)

In the object tree, note the options available on the interval of SAND.

![](./media/image255.png)

Edit the interval using the dialog. Here we change the depth to the base
of the first interval to be 7.4m (all values are depths, not elevations)
and change its geology code to PEAT by typing it in.

![](./media/image256.png)

Use the \<Add/Delete Attribute\> button to set new attribution on the
interval. Here we add a field for a description.

![](./media/image257.png)

![](./media/image258.png)

![](./media/image259.png)

![](./media/image260.png)

Type a value for the new field into the new entry row that has appeared.

![](./media/image261.png)

Add new geology intervals in the same way using the interval editing
dialog.

![](./media/image262.png)

![](./media/image263.png)

![](./media/image264.png)

# Drawing Points, Shapes & Annotations

This section provides details on how to digitize into point and shape
layers, including borehole-type point layers. It also covers how to add
annotations such as labels, callouts, arrows and graphical icons. It
does not include how to draw into the Geology layer of a cross-section –
for that please refer to **Drawing Cross-Sections**.

![](./media/image265.jpeg)

*Photo by Plush Design Studio on Unsplash*

## Creating New Layers

You can use Groundhog to create and draw point and shape layers and to
create annotation layers containing labels, callouts, arrows and icon
graphics. You can also import GIS shapefiles as these types of layers –
for more details please refer to the chapter on **Importing & Exporting
Data**.

Points and shapes can carry attribution and be styled in certain simple
ways. Their attribution can form the basis of geological interpretation,
for example by carrying a geology code they can be used to develop
geological contact maps and structure contour maps, which can then be
used as inputs to 3D models.

Shapes drawn into the map plane can be projected into the alignments of
cross-sections so that you can match your subsurface correlation to the
map line-work in order to create spatially and geologically consistent
conceptual models.

### Creating and Editing Point Layers

Point layers are map layers only (they can’t be drawn into
cross-sections). Create a new point layer from the object tree by
right-clicking on the Location Layers folder, or from the map layer
control panel by right-clicking in a blank whitespace area of the panel.

![](./media/image266.png)

Or…

![](./media/image267.png)

Enter a name for the layer.

![](./media/image268.png)

Make the layer active in the map by clicking on it in the layer control
panel. It will turn orange when active.

![](./media/image269.png)

The drawing tool for points appears as a floating drawing tools palette.
You can drag the palette around using the green bar at the top.

![](./media/image270.png)

To draw points, pick up the point drawing tool from the palette by
clicking on it. When it is active it will turn orange.

![](./media/image271.png)

Single-click in the map to place points at the desired locations. When
you are finished, de-activate the point layer in the map.

![](./media/image272.png)

![](./media/image273.png)

Set the colour of the points using the point layer settings in the layer
control panel.

![](./media/image274.png)

![](./media/image275.png)

![](./media/image276.png)

![](./media/image277.png)

#### Attributing Points

You can set name-value pair attributes on any point objects. With the
layer active in the map, hover the mouse over a point and use
\<right-click\> \<Attribute Location\>.

![](./media/image278.PNG)

Specify an attribute name and value.

![](./media/image279.PNG)

The dictionary on button on the right allows you to select from a list
of commonly used attribute names.

You can then set the field as the label for the points using the layer
settings.

#### Add Dip Measurement

Presents a dialogue box requesting Dip, Azimuth, Radius and Geology.

Radius is the distance in metres that the point affects and setting this
measurement varies the size of the dip measurement

![](./media/image280.PNG) ![](./media/image281.PNG)

Geology is optional and is available as a shortcut way of entering this
attribute.

![](./media/image274.png)

![](./media/image282.png)

![](./media/image283.png)

### Creating & Editing Shape Layers

Shape layers are map or cross-section layers (they can also be drawn
into cross-sections). Create a new shape layer from the object tree by
right-clicking on the Shape Layers folder, or from the map layer control
panel by right-clicking in a blank whitespace area of the panel.

![](./media/image284.png)

Or…

![](./media/image285.png)

Enter a name for the layer.

![](./media/image286.png)

Make the layer active in the map by clicking on it in the layer control
panel. It will turn orange when active.

![](./media/image287.png)

The drawing tool for points appears as a floating drawing tools palette.
You can drag the palette around using the green bar at the top.

![](./media/image288.png)

The drawing palette contains a number of drawing tools. Hover over each
tool to see a short description.

![](./media/image289.png)

The following tools are available,

  - **Polyline** – a digitizing tool, single-click to place vertices,
    double-click to finish,

  - **Pen** – hodl the mouse down and drag to create a free-form line

  - **Polygon** – same as the polyline tool but snaps the two ends of
    the line to form a polygon

  - **Rectangle** – click and drag to create a rectangle

  - **Ellipse** – click and drag to create an ellipse

Single-click on a tool to select it. When a tool is active it will turn
orange. In the following example we are using the polyline tool to
digitize lines.

![](./media/image290.png)

![](./media/image291.png)

If you want to convert a polyline to a polygon, drag the last vertex
towards the first vertex until it “snaps”. Alternatively, on the line
itself, \<right-click\> \<Male Polygon\>.

When a line is active its vertices show as green dots and the line can
be edited;

  - Move vertices by dragging them,

  - Delete vertices by double-clicking on top of them,

  - Add new vertices by double clicking on a line segment.

![](./media/image292.png)

When editing a line, labels appear showing the angles (in degrees)
between adjacent segments.

![](./media/image293.png)

#### Attributing & Tagging Shapes

You can set name-value pair attributes on any shape objects. With the
layer active in the map, hover the mouse over a line and use
\<right-click\> \<Attribute Shape\>.

![](./media/image294.png)

Specify an attribute name and value. In this example we are setting a Z
value so that the line could represent a structure contour, for example.

![](./media/image295.PNG)

You can then set the field as the label for the shapes using the layer
settings and also set colour and line thickness.

![](./media/image296.png)

![](./media/image297.png)

![](./media/image298.png)

You can tag shapes with a geology code automatically as you draw just by
setting an active drawing code other than “Shape”.

![](./media/image299.png)

![](./media/image300.png)

With a geology drawing code set, draw the shape and it will be attribute
with a field called “GEOLOGY” containing the drawing code that was
active at the time.

![](./media/image301.png)

You can also tag a shape with certain pre-set special attribute value.
These are accessible by hover on the line and using \<right-click\>

![](./media/image302.png)

![](./media/image303.png)

These tags cause the objects to act in certain special ways. For
example, tagging a site boundary will style the shape as a bold, red
line.

![](./media/image304.png)

#### Polygons With Holes

You can draw polygons with holes and Groundhog can automatically convert
them into coverage envelopes. First, draw a series of polygons into a
shape layer. Make sure each shape is a polygon either by dragging the
last vertex towards the first to snap together, or via \<Right-Click\>
\<Make Polygon\> on each line.

![](./media/image305.png)

Next, in the data tree, use \<Right-Click\> \<Tools\> \<Build
Multi-Polygons\> on the shape layer.

![](./media/image306.png)

![](./media/image307.png)

Groundhog will auto-detect the holes. This function operates to any
level of nested detail. For very complex shape layers the auto-detection
may take several moments to complete.

![](./media/image308.png)

### Creating & Editing Annotation Layers

*Professional*

Annotation layers let you add a descriptive and symbolic layer to your
projects, both in map and cross-section views. You can only create or
edit annotation layers using Groundhog Professional, but you can view
annotations in existing projects using Community.

Annotations can take the form of;

  - Labels – styled labels with boxes,

  - Callouts – like labels, but with a pointer,

  - Arrows – styled arrow shapes,

  - Graphics – icon pictures that can be placed to represent key
    components of a conceptual model or interpretation.

Use \<right-click\> \<New Annotation Layer\> in the layer control panel
of either a map window or a cross-section window. In the following
example we are working into a cross-section.

![](./media/image309.png)

Enter a name. Note that you can have as many annotation layers as you
like.

![](./media/image310.png)

Make the layer active so that we can draw into it. When active it will
display in orange.

![](./media/image311.png)

When the layer is active the floating drawing tool palette will appear
with a series of annotation-specific tools available.

![](./media/image312.png)

| ![](./media/image313.png) | Label   | Place a label into the layer        |
| ------------------------- | ------- | ----------------------------------- |
| ![](./media/image314.png) | Callout | Place a callout into the layer      |
| ![](./media/image315.png) | Graphic | Place a graphic into the layer      |
| ![](./media/image316.png) | Arrow   | Place an arrow shape into the layer |

#### Labels

Select a tool to start drawing. In this case, the labels tool. When the
tool is active is will highlight in orange and it will stay active for
as long as you want to keep placing annotations of that type. Click the
button again to switch the tool off.

![](./media/image317.png)

Single-click in the graphics panel (map or cross-section) to place the
annotation object. Continue clicking to add more.

![](./media/image318.png)

With the annotations layer active, each annotation will have green
control nodes visible. Drag these to move the annotations around.

\<Right-Click\> on the green control nodes shows a context menu. In the
case of labels we can use this to edit the label text.

![](./media/image319.png)

![](./media/image320.png)

When the annotations layer is active the labels appear orange to show
they are in the active layer. De-activate the annotations layer to see
them in their standard colour.

![](./media/image321.png)

#### Callouts

Activate the callout tool and place some callouts.

![](./media/image322.png)

Note that callouts are like labels, but with a tail.

![](./media/image323.png)

Move the label portion of the callout using the green control node
inside the label.

![](./media/image324.png)

Move the tail by dragging the green control node at the end of the tail.

![](./media/image325.png)

Right-click on the control node at the end of the tail to access the
label editing dialog.

![](./media/image326.png)

![](./media/image327.png)

#### Arrows

Activate the arrow tool in the drawing palette and single-click in the
panel to place arrows.

![](./media/image328.png)

![](./media/image329.png)

Drag the green nodes at either end of the arrows to size and position
them.

![](./media/image330.png)

\<Right-Click\> on the first node of the arrow to access editing and
ordering option.

![](./media/image331.PNG)

Use the dialog accessible under \<Edit Arrow Text/Settings\> option to
set the appearance and label (if one is needed) of each arrow.

![](./media/image332.PNG)

You can also set global setting for the entire layer via the settings
button of the annotations layer.

![](./media/image333.png)

![](./media/image334.PNG)

#### Graphics (Pictures)

You can add graphical pictures into an annotation layer in both map and
cross-section. Groundhog comes pre-loaded with a suite of pictures that
you can use.

Select the graphic tool from the drawing palette.

![](./media/image335.png)

Single-click in the graphics panel to place pictures. You will be
prompted to select the graphic picture to use. Click on the picture you
want and click \<OK\>.

![cid:56bf7827-d83e-41d9-a893-ba263016cf41](./media/image336.jpeg)

Use the green and white control nodes to move and re-size the picture,
respectively.

![](./media/image337.png)

Annotation layers have two zoom modes. By default, the pictures will
re-scale as you zoom in and out (dynamic re-sizing).

![](./media/image338.png)

![](./media/image339.png)

Alternatively, you can switch to non dynamic re-sizing via the layer
settings dialog.

![](./media/image340.png)

![](./media/image341.png)

Add as many annotations as you wish. Here are some examples of the
graphics supported within Groundhog. You are free to use these in
outputs/reports, including for commercial projects.

![](./media/image342.png)

# Drawing Cross-Sections

This section provides details on how to construct and digitise
spatially-referenced geological cross-sections using Groundhog.

![](./media/image343.jpeg)

*Photo by Ivars Krutainis on Unsplash*

## Creating the Cross-Section Alignment

The first step in creating a cross-section is to construct its alignment
on the map.

### Creating Cross-Sections Without an Alignment

If you do not care about the map alignment and you just want to draw a
cross-section of a specific length in isolation then you can use
\<right-click\> \<Tools\> \<Create New Cross-Section\> in the object
tree.

![](./media/image344.png)

This will prompt you for a name and a length and will then open up the
cross-section in a new window ready for drawing, etc. Note that the
cross-section does still have a spatial alignment beginning at \[0, 0\]
in the map.

### Drawing a Polyline for the Alignment

However, you typically want to draw the cross-section alignment in the
map interactively. First, make sure you have a map window open. Create a
new map window for this purpose if necessary. If you are working in the
UK it is a good idea to add the default ***Topographic Basemap*** layer
that is included with Groundhog for orientation purposes or
alternatively import a geo-registered image of your site/project.

![](./media/image345.png)

In the map window, zoom in to the approximate desired location of the
cross-section, making sure that the extent of the map covers the entire
cross-section alignment.

If it isn’t already there, add the default ***Cross-Sections*** layer to
the window.

![](./media/image346.png)

![](./media/image347.png)

You are going to be drawing into the Cross-Sections layer, so make it
active by single-clicking on it in the layer control panel. When it’s
active it will highlight in orange colour.

![](./media/image348.png)

When the layer becomes active a drawing tool palette will appear in the
map panel. There is only one tool available in cross-section layer mode,
which is polyline. Pick this tool up by single-clicking on its icon in
the palette. When it is active the tool will highlight in orange.

![](./media/image349.png)

Start drawing the alignment. **Single-click to add positions** to the
alignment. **Double-click at the last vertex** of the alignment to
complete the operation. Cross-sections can have as many inflections as
you like, or they can be just straight by only placing two vertices into
the polyline.

![](./media/image350.png)

Enter a name for the cross-section. If you wish to abandon the line you
have drawn, simply cancel the name input dialog.

![](./media/image351.png)

Continue drawing polylines to create cross-section alignments. When you
are done drawing, make sure to de-activate the polyline tool by clicking
on it so that it is no longer highlighted in orange.

![](./media/image352.png)

With the cross-section drawing complete it will be added to the object
tree and is now available for display and digitizing operations (see
later sub-section of this chapter).

### Including Boreholes in the Cross-Section Alignment

You can force cross-section alignments through borehole locations so
that you can use them for correlation. First, make sure to add the
desired borehole folder to the map as a layer so that the borehole
locations are visible. Now, as you draw the polyline for the
cross-section alignment in the map, if you move the mouse cursor close
to the location of a borehole object it will show a log preview of the
borehole. This confirms that Groundhog has detected the borehole
location, so single-clicking at that location will add the borehole
itself to the cross-section alignment.

![](./media/image353.png)

### Modifying the Alignment

Once a cross-section alignment has been drawn in the map you can still
modify it. First, make sure the **Cross-Sections** layer is visible and
active in the map.

![](./media/image348.png)

#### Insert New Position

Right-click on the segment of the polyline where you wish to insert a
new map position and choose \<Insert New Position Into Cross-Section\>.

![](./media/image354.png)

![](./media/image355.png)

Click on the desired location in the map to insert it into that segment
of the line.

![](./media/image356.png)

#### Extending a Cross-Section

You can extend a cross-section at either end. Right-click on the segment
at the desired end of the cross-section. If the cross-section only has
one segment (i.e. it is a straight section), make sure to right click
closer to the end of the line that you wish to extent. Choose \<Extend
Cross-Section\>. The examples below show extending the cross-sections to
the East (right).

![](./media/image357.png)

![](./media/image358.png)

![](./media/image359.png)

![](./media/image360.png)

#### Removing a Position From the Alignment

To remove a specific position from the alignment polyline, right click
on the desired position (one of the section ends or an inflection point)
and choose \<Remove Position From Cross-Section\>.

![](./media/image361.png)

![](./media/image362.png)

**IMPORTANT:** Please note that modifying cross-section alignments may
have adverse effects on any correlated geology linework or other
geometry objects that have already been drawn into the cross-section.

## Viewing and Editing the Cross-Section

To open a cross-section in a cross-section window, (1) double-click on
it in the object tree or (2) use \<right-click\> \<View Cross-Section\>
in the tree or (3) \<right-click\> on the alignment in the map and
choose \<View Cross-Section\>. The cross-section window opens in a new
tab.

![](./media/image363.png)

![](./media/image364.png)

Zoom to full extent to centre the data in the panel.

### Topographic Profile

If a default surface layer (topography grid such as a DEM/DTM) is loaded
and configured in the session then a topographic profile will be
automatically generated and added as a ***Terrain Profile*** layer.

![](./media/image365.png)

If there is no grid available for this a flat profile will be generated.
To change or update the topographic profile, open the settings for the
***Terrain Profile*** layer.

![](./media/image366.png)

Choose which grid layer to use for the profile generation and set a
level of detail. If you want to sample the grid at full resolution,
select “FULL” in this list.

![](./media/image367.png)

Click \<Apply\> to make the changes. The profile will be updated. When
using “FULL” resolution on fine grids the update may take a few moments
as the grid query is performed. Also, with the profile at very
high-resolution you may find the graphics a little slower.

If you do not have a suitable grid to use for the topographic profile,
simply drop an ASCII grid (\*.asc) file into the folder where your
Groundhog project is saved and restart Groundhog. The grid will be
picked up and added to the session as an option. For more detail on
working with grid data please refer to the **Importing & Exporting
Data** chapter.

### Viewing Boreholes

If you have drawn your cross-section alignment through any borehole
locations they will be displayed as a ***Boreholes*** layer.

![](./media/image368.png)

To begin with you may find that your boreholes appear as empty boxes
with odd labels.

![](./media/image369.png)

This usually happens when the active log template is unsuitable for the
data contained within the boreholes themselves. Change to a more
suitable template using either the global template settings in the main
status bar of Groundhog.

![](./media/image370.png)

Or, access the settings for the Borehole layer in the section window and
choose a more appropriate template.

![](./media/image371.png)

In the settings dialog choose a suitable template and also specify the
width (in metres) of the log sticks until the logs appear as you want
them.

![](./media/image372.png)

![](./media/image373.png)

If you don’t have a suitable log template then you can design one. For
more details please refer to the **Working With Borehole Logs** chapter.
You can design templates to show different types of borehole data such
as geotechnical test data and geophysical logs.

### Buffering Boreholes Into a Cross-Section

If you have not drawn your alignment directly through the boreholes,
with the ***Cross-Sections*** layer active in the map, you can use a
buffering operation to project them into the alignment using
\<right-click\> \<Project Nearby Boreholes Into Cross-Section\>. Enter a
buffer distance. The projection is performed orthogonal to the
alignment. To remove the buffered boreholes, perform the same operation
and enter a buffer distance of 0 (zero).

![](./media/image374.png)

### Registering Images in Cross-Section

You can add images to a cross-sections as layers. This can be useful for
showing geophysical data, for example. First, load the desired image
into the project via \<Main Menu\> \<Import\> \<Image\>.

![](./media/image375.png)

Position the cross-section panel to the approximate extent where you
want the image to display. Add the image as a layer to the cross-section
window.

![](./media/image376.png)

Select the image you wish to add.

![](./media/image377.png)

Image will appear, filling the visible extent of the graphics panel.

![](./media/image378.png)

Click on the image layer to make it active. Note that square, blue
control handles appear in the top-left and bottom-right of the image.

![](./media/image379.png)

Use the top-left handle to move the image around and use the
bottom-right handle to re-size the image. Whenever possible, try to use
an image that has scale-bars included so that you can compare the values
to the mouse cursor position in order to fine-tune the image
registration.

![](./media/image380.png)

### Drawing Geology

Geological interpretation is drawn into the ***Geology*** layer. The
***Geology*** layer is added to cross-section windows by default, but if
you can’t see it then you can re-add it.

![](./media/image381.png)

![](./media/image382.png)

Make the Geology layer the active layer by clicking on it. It will turn
orange when it is active (to de-activate it, click on it again).

![](./media/image383.png)

When the Geology layer is active the drawing tool palette will appear in
the graphics panel, with the polyline and pen tools available.

![](./media/image384.png)

Before you start to draw geology you need to select a drawing code. The
default drawing code is a generic code labelled “Shape”. Instead, you
need to select a geology code. Click on the drawing code selector button
and pick a geology code from the list.

![](./media/image385.png)

![](./media/image386.png)

Note that the drawing code you select is then set as the active code and
the button changes to display that code. In the above example, PEAT has
been selected.

#### Polyline Tool

The polyline tool allows for accurate digitizing by placing each vertex
individually. Click the button in the drawing tools palette to activate
the polyline tool. When it is active it will turn orange.

![](./media/image387.png)

Single-click in the section to place vertices. Double-click to finish
the line. Switch the polyline tool off when you are done drawing by
clicking on it again in the palette.

![](./media/image388.png)

#### Pen Tool

The pen tool allows for rapid, fluid drawing. Click the button in the
drawing tools palette to activate the pen tool. When it is active it
will turn orange.

![](./media/image389.png)

Click and hold at the start of the line and drag the mouse to draw.
Release the mouse button to stop drawing the line. When you are done
drawing, switch off the pen tool by clicking on it again in the palette.

![](./media/image390.png)

To re-shape a line, click on it to make it active (vertices turn green)
and then drag any of the vertices to re-shape. Double-click on a vertex
to delete it. Double click on a line segment to insert a new vertex.

#### Snapping Geology Lines

To begin with, just draw approximate lines when correlating the geology.
Once you have drawn a line you then need to snap it to other lines in
the section in order to get it to colour up as polygons. There are a few
rules to follow and you need to remember that Groundhog treats geology
lines as deposit BASES, not tops. When snapping, you can -

1.  Snap the end of lines to the edges of the cross-section,

2.  Snap the end of lines to the topographic (terrain) profile,

3.  Snap the end of lines **upwards** onto other correlation lines
    (because the lines are deposit bases).

To snap the end of a line to something else, first make the line active
by clicking on it. When the line is active its vertices will turn green.
Once active, drag the vertex at each end of the line towards another
line, based on the three rules listed above.

![](./media/image391.png)

If you snap the end of a line to the terrain profile, you will be
prompted like this. Click \<No\> if you just want to keep a static
profile, or \<Yes\> to sample more accurate Z values from the terrain
grid at the snap location.

![](./media/image392.png)

A special icon will appear at any snap positions.

![](./media/image393.png)

When both ends of a geology correlation line are snapped to something,
the polygon builder will create a filled polygon for the deposit.

![](./media/image394.png)

Click away from the active line to de-activate it. Continue drawing and
snapping to build up the cross-section. Remember to select the
appropriate drawing code before drawing each line. If you forget, make
the line active by clicking on it then use \<right-click\> \<Change
Geology Code\> and type in the new geology code.

![](./media/image395.png)

![](./media/image396.png)

![](./media/image397.png)

Don’t worry if some existing polygons fail to render as you continue
drawing. They should resolve themselves as soon as you snap the line you
are working on. For example –

![](./media/image398.png)

![](./media/image399.png)

Moving any snapped positions will cause an edit to both correlation
lines (except at the topographic profile).

![](./media/image400.png)

If you need to un-snap a snap location, hold the CTRL key as you drag
the node away from the snap location.

![](./media/image401.png)

Create a correlation line at a fixed elevation using \<right-click\>
\<Create Line \[DRAWING CODE\]\> anywhere in the panel.

![](./media/image402.png)

Choose the datum (O.D. or DEPTH).

![](./media/image403.png)

![](./media/image404.png)

![](./media/image405.png)

The geology that has been drawn into a cross-section can be previewed
rapidly in the map by holding the SHIFT key and hovering over the
alignment. If there is geological line-work at that location the
sequence and thicknesses will be shown in a schematic image.

![](./media/image52.png)

#### Split Geology Line

A geology line can now be split into two lines by right clicking on the
line at the position where it should be split and selecting
**\<split\>**

![](./media/image406.PNG)

![](./media/image407.PNG)

In order to move the new node that has been placed in the split
position, you will need to hold down the CTRL key, to prevent the two
lines from re-joining together.

# Developing Conceptual Site Models

This section provides details on how to develop a conceptual model based
around your site data within Groundhog.

*Professional*

![](./media/image408.jpeg)

*Photo by Shane McLendon on Unsplash*

## Introduction

With a *Professional* license, you can use Groundhog to develop site
conceptual models (CSM). A CSM in Groundhog is a digital representation
of the pathways, or linkages, between contaminants, sources of
contaminants, the potential receptors and the migration pathways that
connect them. The CSM exists as a separate data structure or layer on
top of the Groundhog project and allows you to integrate your conceptual
understanding of pollutant linkages, for example within a catchment or a
site, with the available site data and geological interpretation.

*Professional*

## Constructing the Data Model

A CSM is attached to a notional project “Phase”. This allows you to
develop separate models for different phases of a project, for example
desk study, remediation, monitoring. Create a Phase object to contain
the CSM using on Phases Folder.

![](./media/image409.PNG)

Enter a name.

![](./media/image410.PNG)

This initializes a CSM structure in the object tree as a series of
folders, one per component type within the CSM.

![](./media/image411.PNG)

The available CSM component types are;

> *1. Contaminants*
> 
> *2. Sources*
> 
> *3. Pathways*
> 
> *4. Receptors*

Create any one of these using \<Right-click\> on the appropriate folder
\<Add \[Component Type\]\> for example \<Add Source\>.

![](./media/image412.PNG)

Enter a name for the component and an optional description. You can also
use the picklist key to browse a list of pre-set options.

![](./media/image413.PNG)

The component is added to the folder. In this case, expanding the new
source object reveals a series of attributes.

![](./media/image414.PNG)

The CSM\_HANDLE is the unique ID attributed to the component in the
system.

Continue adding as many components as you wish to the model.

![](./media/image415.PNG)

## Creating Pollutant Linkages 

With the desired model components in place you can now define the
pollutant linkages within the system. on any model component to create a
linkage to or from that linkage.

Here we link the contaminant “Benzene” to the Source “Filling Station”.

![](./media/image416.PNG)

Click \<Contaminant -\> Source\> button.

![](./media/image417.PNG)

Highlight the Source component you wish to link to the Benzene
contaminant (in this case, there is only one, “Filling Station”).

![](./media/image418.PNG)

Click \<Copy to selection \>\>\> to add “Filling Station” to the panel
on the right and click \<Apply\> to create the linkage in the data
model.

![](./media/image419.PNG)

Continue in this way, creating all of the conceptual linkages within the
model. You can create the following types of linkage;

¬ Contaminant ◊ Source – a linkage between a particular source component
and its potential contaminants.

  - **Contaminant -\> Pathway** – linkages which describe how particular
    contaminants are able physically to migrate.

  - **Source -\> Pathway** – linkages which show how particular sources
    are connected to particular migration pathways.

  - **Pathway -\> Receptor** – linkages which show how particular
    pathways are connected to particular receptors.

Note that the linkage dialog will only present the currently available
options for creating new links. If no further linking is possible a
warning message will be displayed.

The linkages are displayed in the Pollutant Linkages folder.

![](./media/image420.PNG)

\<Right-Click\> on a linkage to delete it. You can also “break” the
linkage, which allows you to record information about how the linkage
has been broken within the conceptual model.

![](./media/image421.PNG)

When a linkage is broken it shows that it has been addressed and will
display with a green tick mark. Hovering over the linkage will display
the description of the break. The break can be removed using

\<Right-Click\>\<Un-break Linkage\>.

![](./media/image422.PNG)

![](./media/image423.PNG)

**IMPORTANT:** note that if you decide to delete a CSM component that is
used by any of the linkages, all of those linkages will also be
automatically deleted from the model.

## Displaying a Network Diagram

With the conceptual model data structure in place, and the pollutant
linkages configured, you can create network diagrams automatically.
Network diagrams show schematically and conceptually how all of the
components of the model are connected in terms of pollutant linkages.

\<Right-Click\> on the Network Diagrams sub-folder of the CSM structure
in the object tree and click \<Create Network Diagram\>.

![](./media/image424.PNG)

There are three types of diagram to choose from.

![](./media/image425.PNG)

1.  S-P-R – Source-Pathway-Receptor

2.  C-P-R – Contaminant-Pathway-Receptor

3.  S-C-P-R – Source-Contaminant-Pathway-Receptor

Here we show an S-C-P-R diagram.

![](./media/image426.png)

Drag the component boxes and the labels around as desired.

![](./media/image427.PNG)

Use the handles in the bottom-right of each box to re-size.

![](./media/image428.PNG)

\<Right-Click\> in a CSM model component box to edit settings like
colour and to create new linkages.

![](./media/image429.PNG)

\<Right-Click\> \<Add Label\> in any whitespace region of the panel to
create new text labels.

![](./media/image430.PNG)

\<Right-Click\> on individual labels to edit the text or delete the
label.

![](./media/image431.PNG)

\<Right-Click\> \<Add Arrow Label\> in any whitespace region of the
panel to create new labels which will be attached to a line, which can
be used to point to the required linkage arrow.

![](./media/image432.PNG)

![](./media/image433.PNG)

\<Right-Click\> on the label to edit it

![](./media/image434.PNG)

Click and drag the blue box at the end of the line to move it

![](./media/image435.PNG)

Note the **Add Image** option does not currently work.

\<Right-Click\> near to the end of a linkage, close to where it enters
the next component box and select \<Break Linkage\> to break the linkage
in the system.

![](./media/image436.PNG)

Broken linkages display as partial grey lines with a red cross on them.

![](./media/image437.PNG)

You can un-break a linkage using \<Right-Click\> \<Un-break Linkage\>.

**IMPORTANT:** at the moment, network diagrams are not saved as part of
the project. Once you have the diagram looking how you want it, make
sure to export it as an image for use in reports.

The following buttons are available in the network diagram toolbar.

| ![](./media/image438.png) | Export Image    | Save a copy of the diagram to JPEG or PNG format image.                                                                        |
| ------------------------- | --------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| ![](./media/image439.png) | Refresh         | Re-builds the diagram, picking up any new CSM model components that have been added and removing those that have been deleted. |
| ![](./media/image440.png) | Hide components | Hides any non-linked CSM model components from the diagram.                                                                    |
| ![](./media/image441.png) | New colours     | Allocates new, random, colours to the linkages. Useful if the default colour scheme is undesirable.                            |
| ![](./media/image442.png) | Print           | Send the diagram to a printer.                                                                                                 |

## Drawing CSM Objects in Map and Cross-Section

Certain objects that you draw or place into both map and cross-section
can be tagged as being related to CSM model components. For example, you
could draw the boundary of a landfill and attach it to the landfill
object in your CSM.

More details on how to use the drawing tools please refer to the chapter
on ***Drawing Points, Shapes & Annotations***.

### Shapes

First, add the Phase object to the window (map or cross-section) as a
layer and click on it to make it active. The layer will turn orange when
it is active.

![](./media/image443.PNG)

Once active, the drawing tools will appear allowing you to draw into the
Phase layer. Draw a shape into the layer. When you double-click to
finish the shape you will be prompted to tag it as a CSM model
component. All shapes drawn into Phase layers MUST be tagged with a CSM
model component.

![](./media/image444.PNG)

If you have drawn a polyline, you can make the line active and then snap
the two ends together to form a polygon.

The shape will adopt the default colour for the component type (in this
case receptor colour) and a label with the name of the component will
appear. The example below show a polygon drawn to indicate the extent of
a proposed residential development.

![](./media/image445.PNG)

### Annotations

You can also tag picture objects and arrows in annotation layers as CSM
model component objects.

**Pictures**

When a picture is added, if a Phase exists within the session, you will
be prompted to tag the picture with a CSM component. Pressing \<Cancel\>
on this prompt results in the picture being added with no tag.

![](./media/image446.png)

![](./media/image447.PNG)

A picture can also be tagged with a CSM component after it has been
added to the Map or Section window. To do this, with an annotation layer
active, \<Right-Click\> on the centre node of a picture object and
select a component type from the \<Site Investigation\> menu.

**Arrows**

Arrows work in the same manner as pictures, in that they can be tagged
with a CSM component when they are added, or after they have been added.
To do this, with an annotation layer active, \<Right-Click\> on the
first node of an arrow object and select a component type from the
\<Site Investigation\> menu.

![](./media/image448.PNG)

### Drawing Water Levels and Defining Aquifers

Special tools have been added to allow the definition of aquifer layers
in drawn cross-sections and a water level can also be superimposed to
define the saturated zone.

First, draw the geology into the cross-section.

![](./media/image449.PNG)

To draw the water level, create a new shape layer in the cross-section
using \<Right-Click\> \<New Shape Layer\> in the layer control panel.

![](./media/image450.PNG)

Enter a name (the name is not important).

![](./media/image451.PNG)

The layer will be added and will become active automatically so that you
can draw into it. Pick up a drawing tool and draw the water level.

![](./media/image452.PNG)

Switch off the drawing tool and click on the line to make it active.
When it is active the line vertices will turn green.

![](./media/image453.PNG)

\<Right-Click\> on the line and select \<Tag Shape As…\>

![](./media/image454.PNG)

In the options that appear, select “WATER LEVEL”.

![](./media/image455.PNG)

De-activate the shape layer in the layer control. The water level line
will appear styled in a particular way to denote water level.

![](./media/image456.PNG)

Next, you need to tell Groundhog which geological unit is the aquifer
unit. This is linked to the CSM, so you will need to make sure you have
an aquifer model component defined (i.e. as a receptor component) within
the model.

![](./media/image457.PNG)

Make the Geology layer active in the layer control. \<Right-Click\> in
the cross-section on the geological unit that corresponds to the aquifer
and select \<Site Investigation\> \<Tag as Aquifer?\>.

![](./media/image458.PNG)

Select the Phase.

![](./media/image459.PNG)

Select the aquifer from the list of receptors.

![](./media/image460.PNG)

Click \<Yes\>

![](./media/image461.PNG)

The aquifer unit will be outlined in blue and the saturated zone shaded
in blue. Use the transparency of the Geology layer to get the best
image.

![](./media/image462.PNG)

## Accessing Historic Maps

Historic maps are important in contaminated land and brownfield site
studies because they provide insight into the historic land use. To help
with this, Groundhog has a hyperlink functionality that will take you to
the website of the National Library of Scotland, which has an archive of
high-resolution scanned historic maps for the UK.

<https://maps.nls.uk/>

This feature is provided as a convenient 3<sup>rd</sup> party web link
and in no way implies that the NLS has any connection to, or endorsement
of, the Groundhog software.

\<Right-Click\> at the desired location in the map and select \<Site
Investigation\> \<Browse Historic Maps\>.

![](./media/image463.PNG)

You will be shown this message:

![](./media/image464.PNG)

The NLS website should open in your default web browser. Typically, when
the website first opens, an info box obscures the map view. Click the
cross in the top right corner to close this.

![](./media/image465.png)

You should now see the historic map view zoomed to approximately the
same scale and location as your Groundhog map view.

![](./media/image466.png)

Single-click anywhere in the map. A panel should appear on the right
showing a list view of the vintages of historic map available for that
location.

![](./media/image467.PNG)

Click on the hyperlinks in this list panel to open the map you want to
view. The interactive map view will load. Zoom and pan in the historic
map to see the area you are interested in.

![](./media/image468.PNG)

*NLS Website Image*

# Building Geological Models

This section provides details on how to construct 2.5D and 3D property
and structural framework models of measurements and geology within
Groundhog.

*Professional*

![](./media/image469.jpeg)

*Photo by Ruslan Keba on Unsplash*

## Intro

You can use the *Professional* edition of Groundhog to build simple 3D
geological models. Model building in Groundhog is based on a
multi-input, dynamic workflow and uses a gridding method to build each
deposit or layer within the model sequence. The workflow allows you to
use a range of different inputs in various combination, together with
simple algorithm selection, in order to rapidly build models. You can
work directly from your data, or layer on your own interpretation using
additional points and lines to shape the model. The workflow is rapid
and allows for testing of different hypotheses and application of
different datasets to see the effect. Each layer is constrained by
inputs in the form of;

  - Fixed thickness, depth or elevation,

  - Borehole picks,

  - Control points,

  - Drawn-cross-sections,

  - Structure contours,

  - Map linework,

  - Dip and azimuth values,

  - Variable thickness rules.

Models are based on a simple grid data structure, but can be clipped out
to project boundaries or other irregular polygonal shapes.

*Professional*

## Defining the Model Grid

In the object tree, navigate to *Models \> Layer Models* and select
*Right-Click \> New Model*.

![](./media/image470.png)

The model editing dialog appears. Enter the necessary information to set
the name of the model (free-text), choose which elevation model from the
workspace to use as the topographic top of the model, and then enter the
bounding box of the model area and an initial cellsize to use. Set a
coarse resolution for the moment, you can refine it later. If you have a
map window open and zoomed to the model area, you can use the *Extent
From Map* button to populate the bounding box fields automatically.

![](./media/image471.png)

Review the input dialog an make sure you have set the following;

1.  Min/max X and Y,

2.  Cellsize (set this to a large value, i.e. low resolution, to begin
    with – you can change it later)

3.  Name

4.  Clipping Layer – select a grid, e.g. a DEM, from the workspace.

Click *Apply*. The model definition will be added to the object tree.

![](./media/image472.png)

Add the model to a map window.

![](./media/image473.png)

![](./media/image474.png)

Open the settings for the model in the map window.

![](./media/image475.png)

Check-on Model Outline and Model Grid.

![](./media/image476.png)

Model outline and grid are now visible in the map.

![](./media/image477.png)

**IMPORTANT: Now save the project.** For model building, Groundhog needs
an output folder.

## Creating Model Layers

Each layer in the model can be based on a range of different inputs,
including (depending on the layer type);

1.  Borehole picks

2.  Outcrop/subcrop points

3.  Control points

4.  Outcrop/subcrop linework

5.  Structure contours

6.  Cross-sections

7.  Fixed depth or elevation

8.  Dip and azimuth values

9.  Fixed or graduated thickness values

The following example shows how to build up a layer from a set of
different inputs. To begin with we will create some bedrock-style layers
which are based on an implicit function controlled by a set of
user-added inputs.

To get started, let’s define some outcrop positions. Right-click to
create a new point layer in the map.

![](./media/image478.png)

![](./media/image479.png)

Make the new layer editable and place some points. Here we are using the
BGS 50k Bedrock Web Map Service as a guide to positioning these points
at the BASE of a mapped unit. When the points have been placed,
de-activate the point layer.

![](./media/image480.png)

In the object tree, *right-click on the model object \> Edit Model*

![](./media/image481.png)

Click the Create Layer button in the model editing dialog.

![](./media/image482.png)

If the model is new and the project has not been saved, you will see
this.

![](./media/image483.png)

As models are calculated, their outputs are saved to the project folder.
For this, Groundhog needs to know where the folder lives, so save the
project somewhere and then repeat the Create Layer action again.

In the create layer dialog, enter a name for the layer and click the Add
Inputs button.

![](./media/image484.png)

This is where we can select which data or parameters to use as input to
the layer. Select the point layer we created as the input and click OK.

![](./media/image485.png)

The points are now added as an input to the layer. Click *Apply*.

![](./media/image486.png)

In the model editing dialog, click *Apply and Build*. If the model
editing dialog is not open, right-click on the model in the object tree
and select *Build*. The model will calculate, and the progress will be
shown in the main progress bar.

![](./media/image487.png)

Or…

![](./media/image488.png)

Go back to the settings dialog for the model layer in the map window and
tick-on the new layer. Also, switch to map coverage view.

![](./media/image489.png)

![](./media/image490.png)

The calculated extent of the layer will be shown in the map. If it is
unclear on top of the other layers, decrease the layer transparency
using the slider bar in the layer control.

![](./media/image491.png)

Next we will add some geological map linework. This could be imported
from a shapefile, but for this example we will draw it by hand. Create a
new shape layer in the map window and make it editable.

![](./media/image492.png)

![](./media/image493.png)

In the model editing dialog, open the settings for Layer A.

![](./media/image494.png)

Add the new linework to the layer input list.

![](./media/image495.png)

![](./media/image496.png)

Apply and then re-build the model.

![](./media/image497.png)

Note that there is a portion of Layer A in the south-west that does not
match the geological map. Draw a cross-section through the model to
inspect it at this location.

![](./media/image498.png)

View the cross-section and add the model to the view as a layer.

![](./media/image499.png)

Let’s add a component of dip to the layer using a structure contour.
Draw a new line into the Layer A map.

![](./media/image500.png)

Switch the drawing tool off and right-click on the new line \>
*Attribute Shape*.

![](./media/image501.png)

Set an attribute called “Z” with a value of “10”. This attributes an
elevation value of ten metres to the line, thereby making it a structure
contour.

![](./media/image502.png)

This adds some additional dip to the layer, but still has not resolved
the unwanted outlier in the south west.

![](./media/image503.png)

Draw another structure contour in the West, setting a Z value of 60m.
This is effectively a structure contour in the air which can be used to
pull the calculated surface up out of the ground.

![](./media/image504.png)

Re-build the model. The layer is now correctly resolved relative to the
outcrop pattern.

![](./media/image505.png)

In the model editing dialog, increase the resolution of the model (e.g.
to 10m cellsize from 100m) and re-build it.

![](./media/image506.png)

![](./media/image507.png)

Next we will add another bedrock layer with a fixed elevation. Add a new
layer to the model using the model editing dialog.

![](./media/image508.png)

Make the input to this layer a Fixed Elevation parameter.

![](./media/image509.png)

Here we set the elevation at 30m, for example.

![](./media/image510.png)

There are now two layers in the model. Re-build the model.

![](./media/image511.png)

Go to the settings for the model layer in the map window and check-on
the visibility of the new layer.

![](./media/image512.png)

![](./media/image513.png)

Note that the outcrop pattern of the new layer has been generated
automatically, based on the intersection with the topography, and also
that the sub-crop position caused by the erosional contact against the
base of the layer above has also been detected automatically. Setting
the model as semi-transparent in the map window shows the sub-crop map
of Layer B beneath Layer A.

![](./media/image514.png)

Next we will create a Quaternary-style layer based on map linework and a
thickness value. Create a new shape layer in the map to draw into.

![](./media/image515.png)

![](./media/image516.png)

Make the new line active and snap the two ends together to form a
polygon or right-click on the line and select *Make Polygon*.

![](./media/image517.png)

Create a new layer using the model editing dialog. Add the Quaternary
map layer as the input and make sure to select a layer type of
“Patches”.

![](./media/image518.png)

Switch to the Algorithm tab of the dialog and set the thickness value to
8 (m).

![](./media/image519.png)

In the model editing dialog, note that the layer is at the bottom of the
list. This list is used as the stratigraphic scheme and we need the
Quaternary layer on top of the stack, so drag it to reposition at the
top of the list.

![](./media/image520.png)

![](./media/image521.png)

Re-build the model and make the new layer visible in the map. Note that
the “patches” type layer honours the drawn map exactly, unlike the
bedrock model layers which predict the outcrop pattern automatically.

![](./media/image522.png)

In profile, see how the layer thins out towards the edges of the mapped
polygon.

![](./media/image523.png)

Toggle the map view to isopach (thickness) view to get an impression of
how the thickness setting has been graduated within the mapped polygon.

![](./media/image524.png)

![](./media/image525.png)

Edit the map layer and add some windows into the layer.

![](./media/image526.png)

Re-build the model. Note how the hierarchy of windows and islands within
the deposit is resolved automatically. This can be taken to any level or
nesting required.

![](./media/image527.png)

By default, model extents are rectangular. To define a polygonal
boundary, create a shape layer and draw the boundary. Make sure to
convert the shape to a polygon.

![](./media/image528.png)

In the model editing dialog, click the *Extent From Shape* button and
select the model boundary shape layer as the input.

![](./media/image529.png)

![](./media/image530.png)

Re-build the model.

![](./media/image531.png)

Draw into the cross-section to use as an input to bedrock layers. Choose
a drawing code for the layer. Here we use GRAVEL, but the code can be
whatever you like. To draw geology, make the Geology layer active in the
section window.

![](./media/image532.png)

![](./media/image533.png)

Add the cross-section information as an input to Layer A. Go to the
settings for Layer A and choose Cross-Sections as a new input to the
layer. When prompted, choose the drawing code “GRAVEL” as the filter for
the input. This will use all instances of “Gravel” from all
cross-sections as input to the layer calculation.

![](./media/image534.png)

![](./media/image535.png)

![](./media/image536.png)

Re-build the model. Note that the correlation linework in the
cross-section has been used to control the Layer A surface.

![](./media/image537.png)

You can add models as a layer to the 3D view to visualise them. For more
details, refer to the next chapter on using the 3D graphics window.

![](./media/image538.png)

### Additional Tools

The above section provides a general introduction to building layer
models using Groundhog. Here we detail a few extra, specific tools that
are of use during the modelling process.

#### Dip and Azimuth Inputs

Dip and azimuth (structural) inputs are treated as points. To convert a
point object to a structural point that can be used in the modelling,
first make the point layer active. ***\<Right-click\>*** on the desired
point and choose ***\<Add Dip Measurement\>***

![](./media/image539.png)

Use the input dialog to set the DIP, AZIMUTH and RADIUS values. RADIUS
controls the zone of influence of the data point. You can also set a
GEOLOGY code if you wish to have a single point layer containing
structural points from different model layers.

![](./media/image540.png)

The point becomes an arrow showing the AZIMUTH. The length of the arrow
shows the RADIUS of influence the point will have if used in a
calculation.

![](./media/image541.png)

#### Coverage Mode

When working with stratigraphic layers, by default Groundhog will
auto-predict the outcrop/subcrop of each layer in the model. However, if
you wish to have hard control over the calculation boundaries then you
can draw (or import) a polygonal map to act as the boundary of the model
calculation for the layer. This is known as COVERAGE mode. When you are
working in this mode, Groundhog will not compute the presence of the
layer anywhere outside the coverage polygon.

Draw the polygons for the coverage map into a shape layer (or import
from a Shapefile, but make sure they are polygons). After drawing each
shape, ensure it is a polygon either by dragging the last node towards
the first node to snap it, or using ***\<Right-Click\> \<Make
Polygon\>***

![](./media/image542.png)

Here is an example if a coverage polygon drawn for a layer.

![](./media/image543.png)

Note that a coverage can be composed of multiple polygons, including
polygons-with-holes (nested to any level of detail.

Next, add the shape layer to the desired model layer as an input.

![](./media/image544.png)

When prompted to set the shape input as a COVERAGE layer, click
***\<Yes\>***

![](./media/image545.png)

Note that shape layers which are acting as coverage layers are labelled
thus in the input list.

![](./media/image546.png)

If you need to change the status of the layer you should delete it from
the inputs list and then re-add it.

Calculate the model. Note that the calculation of the layer stays within
the shapes of the coverage layer.

![](./media/image547.png)

Working at a higher resolution shows the effect of this more clearly,
especially if the coverage map is very detailed with lots of small holes
and islands.

![](./media/image548.png)

#### Control Points

Points from point layers can be used as control points. Control points
act to remove an area of modelling and are a quick way to clean up
models. Below is an example of a model layer with an area that needs to
be cleaned up (highlighted by the arrows).

![](./media/image549.png)

To set a point as a control point, place the point in the desired
location and then use ***\<Right-Click\> \<Modelling Tools\> \<Clean
Up\>***

![](./media/image550.png)

The point is displayed as a cross icon.

![](./media/image551.png)

Re-build the model.

![](./media/image552.png)

# 3D Graphics

This section provides details on how to operate the 3D graphics
component within Groundhog.

![](./media/image553.jpeg)

*Photo by Nathan Duck on Unsplash*

##   
About

The 3D window in groundhog has been developed in order to visualize the
data that you import and create in 2D. All of the features of the 3D
window are available in community edition. From viewing boreholes and
cross sections, as you can in the map and section views, as solid,
spatially referenced objects to elevation grids as surfaces and block
geology models.

## First Use

To open the 3D window, click the ![](./media/image554.png)3D window
button and you will be presented with the user interface.

## User Interface

![](./media/image555.png)

The window has three main areas of control:

### The control panel

![](./media/image556.png)

The control panel is where you will manipulate what data you are viewing
and how you will view it in 3D. The controls are split into tabs for
easy navigation and there are three controlling buttons at the top:

1.  ![](./media/image557.png) Move: This will allow you to rotate, pan
    and zoom in the 3D scene.

2.  ![](./media/image558.png) Pick: This button is currently in beta but
    when the window is in this mode, you can no longer move around but
    instead select objects by clicking them. When an object is selected
    (clicked on) it will open in the object explorer tab which we will
    visit later. (As his is in beta only some data types are supported)

3.  ![](./media/image559.png)Save: Self-explanatory but with many
    functions, the save button will allow you to save a variety of items
    from the configuration of the window (camera position and layers) to
    mp4 videos you record to .OBJ exports of supported layers in the
    window.

### Layer Control

![](./media/image560.png)The first of the tabs in the control panel is
the **layer control** with which you will be familiar from the map and
section window. Along the top, left to right, there is:

1.  The add layer button, opening the usual dialogue

2.  The global setting button which opens this dialogue:
    ![](./media/image561.png)

> Here you can set the vertical scale of the window, the maximum
> vertical scale for the slider and turn on and off the axes in the
> window.

3.  The background colour button, which changes the background colour of
    the 3D window

4.  The clear layers button which will remove all of the layers from the
    window.

The next item is the representation of a layer.

![](./media/image562.png)

Here you can see the name of the layer, the icon of the layers type, in
this case borehole, a checkbox for the visibility of the layer, a slider
for the transparency and 4 buttons. From left to right, top to bottom:

1.  Settings: this will open up any settings for the layer (some of
    which will be described below)

2.  Filter: this will open any filters for the layer

3.  Object Explore: Will open the layer in the object explorer (the next
    tab we will look at)

4.  Remove: which will remove the layer from the window.

When multiple layers are in the layer control, they can be dragged
around, just as in the map and section layer controls, to change the
drawing order and allow certain objects to be seen through others.

### 

### ![](./media/image563.png)Object Explorer

The next tab is the **object explorer** which allows a particular layer
to be interrogated. By opening the above borehole layer in the object
explorer, we can see the two boreholes that are in the dataset are shown
in the panel. Each borehole can then be turned on and off with the
checkbox and its transparency changed with the slider. Right click on a
borehole or any object in the explorer, that item will become the
**pivot** of the window. There may also be settings for an object which
can be accessed through the settings button.

If you double click an object in the explorer, that object will be
“opened”.

![](./media/image564.png)Here, the object BH502 has been opened and you
can now see all of the logs and manipulate them as with any other
object.

The arrow buttons can be used to move backwards and forwards in and out
of objects.

### Clipping Controls

![](./media/image565.png)After the object explorer, you will find the
**clipping controls** tab. The add button will give you two options:

1.  Add new clipping Plane: this will add a new clipping plane to the
    scene, allowing you to slice and interrogate your data at whatever
    angle you wish wherever.

This is particularly useful for viewing 3D geological models produced in
Groundhog Professional.

![](./media/image566.png)![](./media/image567.png)

When you create a clipping plane, you will be greeted with a control
that looks like this:

![](./media/image568.png)To rotate the plane, drag the circle at the end
of the line, and to move the center point of the plane, drag the center
circle in that direction.

If you are struggling with this control, by clicking the settings
button, you can also incrementally change the positions.

![](./media/image569.png)A is for azimuth as an angle in degrees.

If you choose a **clipping slice** the controls are much the same, with
the addition of a thickness. On the graphical control:
![](./media/image570.png)and by buttons is represented by T:
![](./media/image571.png)

The difference with a clipping slice over a clipping plane is that there
is somewhat a slice of cake taken out of a model :

![](./media/image572.png)

### Configurations

**Configurations** is the final tab in the control panel and its purpose
is to provide shortcuts to nice “views” of your data.

If you like an angle of looking at your data or particular clip, you can
press the save button ![](./media/image559.png)and all the information
will be saved, a link to it being shown then in the configurations tab.

![](./media/image573.png)Select the saved configuration you would like
to see and you will be taken there.

While a configuration is selected, selecting this button will allow you
to rename the configuration

The bin will remove all configurations.

### The Hot Bar

![](./media/image574.png)

The hot bar is the area at the bottom of the groundhog 3D window which
looks like the screenshot above. Here you can find useful information
and some quick access tools.

The first item is the loading bar. ![](./media/image575.png) This will
give you information on the progress of any actions such as loading and
saving.

Next is the vertical exaggeration slider. ![](./media/image576.png)By
moving this slider, you will increase or decrease the vertical
exaggeration on the window.

The following tools you will find are the recording and playback tools.
![](./media/image577.png) In order to create a playback, click the
record button, maneuver around the scene in the order you wish to
re-watch and, finally, click the stop button that will have replaced the
record button.![](./media/image578.png)

In order to watch your playback, simply click the play button.

When the play button becomes available, you will be able to save a
playback as an MP4 by clicking the save button ![](./media/image559.png)
and selecting the playback option from the dropdown.

Finally, on the hot bar, there is the message area.
![](./media/image579.png) Useful tips will be displayed here.

### The Scene

This is the final area of the 3D window and is where all of the data
appears.

![](./media/image580.png)

This area is very minimal, here we have:

1.  The data: Whatever you have added to the scene from the add layers
    button.

2.  The compass: Showing the direction you are looking

3.  The axes: giving the scale of the data you are viewing

Navigation of the scene is broken into three types:

1.  Rotation: press and hold left click and drag the mouse to rotate the
    scene.

2.  Zoom: use scroll to zoom in and out from the data.

3.  Pan: press down on the scroll wheel and hold then drag the mouse to
    pan around the scene.

## Settings

### Borehole Settings

![](./media/image581.png)

## Saving

The save button ![](./media/image559.png) is a multi-functional save
tool which will allow the saving of any savable layers or items that are
currently existent within your current session. These could include 3D
objects, videos and the configuration of your window.

When the save button is pressed, the following dropdown box will appear.

![](./media/image582.png)

All of the options in the dropdown can be saved to their stated format
and the possible options are as follows.

### Cross Sections

Cross sections can be saved from the 3D window to the .OBJ format which
can then be imported into GeoVisionary and many other CAD platforms.
There will be a selection of files exported which will be one for each
unit and one which will represent all of the sections. All will be
placed in a single folder in your chosen location called “Cross
Sections”.

### Models

Geological models can also be saved to the .OBJ format and there will be
a file created for each stratigraphic layer of your model. These will
all be saved to the folder of your choosing.

### Surfaces

Keeping consistent with the other layers, surfaces too will be export as
.OBJ files. There will be three files output.

![](./media/image583.png)

These three should be kept together; there is one for the shapes, one
for the colours and optionally one which will be the image used for the
surface.

### Videos

If the playback function has been used then there will be the option to
save this to an mp4 video. During the saving of the video, the window
will be temporarily out of action and appear to move by itself, this is
so that the information can be collected. Please do not interrupt this.

### Configurations

![](./media/image573.png)The final option is the current map window
configuration and as previously mentioned will save the view on the
screen as a waypoint which you will be able to click and return to at a
later date. Once you have provided a memorable name, it will appear in
the configurations tab like this:
