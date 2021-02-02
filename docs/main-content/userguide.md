*BGS Groundhog Desktop*

User Guide v2.2.0 (BETA)

January 2021

![](media\image1.png){width="6.158649387576553in"
height="4.162790901137358in"}

![](media\image2.png){width="2.0535640857392825in"
height="0.6016951006124235in"}![](media\image3.png){width="1.3546970691163605in"
height="0.5679997812773403in"}

**© Copyright British Geological Survey (UKRI) 2021. All rights
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

![](media\image3.png){width="1.3546970691163605in"
height="0.5679997812773403in"}![](media\image2.png){width="2.0535640857392825in"
height="0.6016951006124235in"}

# Contents {#contents .TOC-Heading}

[Introduction 6](#_Toc62653285)

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

[Importing & Exporting Data 33](#_Toc62653304)

[Images 34](#images)

[Shapefiles 38](#shapefiles)

[ASCII Grids 39](#ascii-grids)

[OBJ Files 40](#obj-files)

[Working With Borehole Logs 42](#_Toc62653309)

[Borehole Data Import 43](#borehole-data-import)

[CSV/TXT Format 43](#csvtxt-format)

[Importing CSV 44](#importing-csv)

[Importing Tabular Data 52](#importing-tabular-data)

[Importing AGS Format Data 57](#importing-ags-format-data)

[Importing LAS Format Data 59](#importing-las-format-data)

[BGS Borehole Records 63](#bgs-borehole-records)

[Displaying Boreholes 67](#displaying-boreholes)

[Creating Borehole Log Templates 68](#creating-borehole-log-templates)

[Editing Borehole Log Templates 69](#editing-borehole-log-templates)

[Viewing AGS Boreholes 86](#viewing-ags-boreholes)

[Exporting Logs as PDF 87](#exporting-logs-as-pdf)

[Exporting Boreholes as CSV 88](#exporting-boreholes-as-csv)

[Editing Borehole Data 89](#editing-borehole-data)

[Drawing Points, Shapes & Annotations 96](#_Toc62653324)

[Creating New Layers 97](#creating-new-layers)

[Creating and Editing Point Layers
97](#creating-and-editing-point-layers)

[Creating & Editing Shape Layers 101](#creating-editing-shape-layers)

[Creating & Editing Annotation Layers
109](#creating-editing-annotation-layers)

[Drawing Cross-Sections 118](#drawing-cross-sections)

[Creating the Cross-Section Alignment
119](#creating-the-cross-section-alignment)

[Creating Cross-Sections Without an Alignment
119](#creating-cross-sections-without-an-alignment)

[Drawing a Polyline for the Alignment
119](#drawing-a-polyline-for-the-alignment)

[Including Boreholes in the Cross-Section Alignment
121](#including-boreholes-in-the-cross-section-alignment)

[Modifying the Alignment 121](#modifying-the-alignment)

[Viewing and Editing the Cross-Section
124](#viewing-and-editing-the-cross-section)

[Topographic Profile 125](#topographic-profile)

[Viewing Boreholes 126](#viewing-boreholes)

[Buffering Boreholes Into a Cross-Section
128](#buffering-boreholes-into-a-cross-section)

[Registering Images in Cross-Section
129](#registering-images-in-cross-section)

[Drawing Geology 131](#drawing-geology)

[Developing Conceptual Site Models 139](#_Toc62653341)

[Introduction 140](#introduction-1)

[Constructing the Data Model 140](#constructing-the-data-model)

[Creating Pollutant Linkages 142](#creating-pollutant-linkages)

[Displaying a Network Diagram 144](#displaying-a-network-diagram)

[Drawing CSM Objects in Map and Cross-Section
148](#drawing-csm-objects-in-map-and-cross-section)

[Shapes 148](#shapes)

[Annotations 149](#annotations)

[Drawing Water Levels and Defining Aquifers
150](#drawing-water-levels-and-defining-aquifers)

[Accessing Historic Maps 154](#accessing-historic-maps)

[Building Geological Models 157](#_Toc62653351)

[Intro 158](#intro)

[Defining the Model Grid 158](#defining-the-model-grid)

[Creating Model Layers 160](#creating-model-layers)

[Additional Tools 181](#additional-tools)

[Model Outputs 189](#model-outputs)

[3D Graphics 191](#_Toc62653357)

[About 192](#about)

[First Use 192](#first-use-1)

[User Interface 192](#user-interface-1)

[The control panel 193](#the-control-panel)

[Layer Control 193](#layer-control)

[Object Explorer 195](#object-explorer)

[Clipping Controls 195](#clipping-controls)

[Configurations 197](#configurations)

[The Hot Bar 198](#the-hot-bar)

[The Scene 199](#the-scene)

[Settings 200](#settings)

[Borehole Settings 200](#borehole-settings)

[Saving 201](#saving)

[Cross Sections 202](#cross-sections)

[Models 202](#models)

[Surfaces 202](#surfaces)

[Videos 202](#videos)

[Configurations 202](#configurations-1)

[Appendix -- Configuring the Groundhog Home Area
204](#appendix-configuring-the-groundhog-home-area)

[Groundhog New User 205](#groundhog-new-user)

[Upgrading from a previous version of Groundhog to version 2.2
206](#upgrading-from-a-previous-version-of-groundhog-to-version-2.2)

[Other Groundhog Home Functions 207](#other-groundhog-home-functions)

[Open Home Folder 207](#open-home-folder)

[Create New 207](#create-new)

[Report 208](#report)

[Clean Up 209](#clean-up)

# Introduction

This section provides an overview of Groundhog and information about how
to install the software and activate a license.

![](media\image4.jpeg){width="6.268055555555556in"
height="4.178472222222222in"}

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
Groundhog!**

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

**IMPORTANT:** Depending on your organisation's security policies you
may need assistance from your IT support department to carry out the
software install.

The installation wizard guides you through a series of screens.

You will be prompted to choose an **installation folder**, which is
usually C:\\Program Files\\BGS Groundhog Desktop, but you can install
Groundhog wherever you prefer.

## First Use

The first time you start Groundhog you will see a screen like this.

![](media\image5.PNG){width="6.213888888888889in"
height="2.859031058617673in"}

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
because this helps our project gain exposure, but you do not have to!

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

![](media\image6.png){width="5.4375in" height="2.9166666666666665in"}

When prompted, enter your email address and the digital key you
received. ![](media\image7.png){width="3.1354166666666665in"
height="1.6145833333333333in"}

You will be asked to accept the terms of the license agreement, then an
*Upgrade Success* message will be displayed. If you receive any other
message, please try the process again, making sure you paste the entire
license key into the appropriate text box.

Once activated you will need to re-start Groundhog to switch to
Professional mode. From now on, Groundhog will run in Professional mode
for the duration of you license.

If you experience any difficulties with your activation, please contact
the person who issued your digital key by email.

#  Data Objects

This section provides an overview of the key data object types supported
by Groundhog, where they are held in the project structure and how to
both create and import your own data structures into a Groundhog
project.

![](media\image8.jpeg){width="6.268055555555556in"
height="4.178472222222222in"}

*Photo by João Silas on Unsplash*

## Object Tree

Project data is held as various objects within the object tree. The
object tree is found along the left side of the main user interface
under the \<Workspace\> tab. For more details on the other components of
the user interface please refer to the next main section of the user
guide.

![](media\image9.png){width="1.960987532808399in"
height="5.113043525809274in"}

This tree panel is a typical multi-level object structure, like a
Windows file explorer navigation panel. Expand the various folder nodes
to explore your data at different levels. Note that not all folder nodes
are available in all versions of Groundhog.

The object tree is arranged into three top-level folders.

![](media\image10.png){width="1.4791666666666667in"
height="1.0104166666666667in"}

### Site / Project Folder

Contains the key site investigation data types such as GIS-style point
and shape layers, borehole data, cross-sections, project phase and CSM
information, annotations and linked files such as images.

![](media\image11.png){width="1.5833333333333333in"
height="1.6979166666666667in"}

#### Location Layers Folder

This folder holds both GIS-style point layers and also borehole dataset
layers. Borehole layers are effectively treated as a special flavour of
point layer, which is why they are grouped together as Location Layers.

Make new, empty layers using \<right-click\> \<New Layer\>.

![](media\image12.png){width="2.1354166666666665in"
height="0.5520833333333334in"}

Enter a name.

![](media\image13.png){width="2.365217629046369in"
height="1.0930172790901138in"}

Click \<Yes\> if you want to make a layer for boreholes, click \<No\> to
make a layer for point data.

![](media\image14.png){width="2.634782370953631in"
height="1.093153980752406in"}

This is the effect of doing both a borehole layer and a point layer.
Note the different icons.

![](media\image15.png){width="1.5833333333333333in"
height="0.6354166666666666in"}

In the case of boreholes, a \<Right-Click\> option allows for data
import. For more details on data import see the main user guide chapter
**Importing & Exporting Data**.

![](media\image16.PNG){width="5.37575021872266in"
height="2.5836942257217848in"}

#### Shape Layers Folder

This folder holds GIS-style shape layers (lines and polygons). Groundhog
makes no distinction between lines and polygons, so they are grouped
together into generic shape layers.

Make new, empty layers using \<right-click\> \<New Layer\>

![](media\image17.png){width="1.8333333333333333in" height="0.5625in"}

Enter a name.

![](media\image18.png){width="2.5304352580927385in"
height="1.1693678915135608in"}

Empty layer is added to the folder.

![](media\image19.png){width="2.1041666666666665in"
height="0.4791666666666667in"}

#### Cross-Sections Folder

This is where drawn cross-sections will appear. At the moment, Groundhog
stores all of these in a single folder. Typically you will create new
cross-sections by drawing them in the map -- please refer to the
**Drawing Cross-Sections** chapter of the user guide for more
information. However, it is possible to create non-spatially referenced
cross-section objects directly from the tree if you just want to draw a
cross-section without placing it in the map context via \<right-click\>
\<Tools\> \<Create New Cross-Section\>.

![](media\image20.png){width="4.979166666666667in"
height="0.5833333333333334in"}

Enter a name.

![](media\image21.png){width="2.4in" height="1.1090912073490813in"}

Specify a length in metres.

![](media\image22.png){width="2.356521216097988in"
height="1.0889982502187228in"}

![](media\image23.png){width="1.3333333333333333in"
height="0.4479166666666667in"}

Cross-sections created in this way are all registered starting at \[0,
0\] grid coordinates.

#### Annotations Folder

Annotations layers hold labels, callouts and graphics icons to label and
represent objects within the project or the conceptual site model.
Create a new layer for holding annotation objects via \<Right-Click\>
\<New Layer\>.

*Professional*

![](media\image24.png){width="1.8645833333333333in"
height="0.6041666666666666in"}

Enter a name.

![](media\image25.png){width="2.3043482064741907in"
height="1.0648884514435695in"}

![](media\image26.png){width="1.375in" height="0.4895833333333333in"}

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

![](media\image27.png){width="2.7708333333333335in"
height="0.5208333333333334in"}

#### Associated Files Folder

Certain types of imported file will appear in this folder when they are
imported. A good example is imported image files which have their own
specific sub-folder.

![](media\image28.png){width="1.6875in" height="0.875in"}

### Models Folder

Contains the key data types related to 2.5D and 3D models and related
information.

![](media\image29.PNG){width="2.2086417322834646in"
height="1.062648731408574in"}

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

![](media\image30.png){width="1.8333333333333333in"
height="0.9895833333333334in"}

#### Pick Lists Folder

This folder holds pick list or dictionary objects. These are pre-set
lists of values and descriptions that are used in various places within
Groundhog to perform lookups. Although you can define your own pick
lists, typically you do not need to interact with this folder in the
current version of Groundhog. Examples include a pick list of possible
contaminants for conceptual site models, or dictionary lookups for
geotechnical data in AGS format.

![](media\image31.png){width="2.6145833333333335in" height="1.9375in"}

![](media\image32.png){width="2.6145833333333335in"
height="1.1041666666666667in"}

#### Templates Folder

This folder holds borehole log templates. When Groundhog is first
installed it will only contain a limited number of default templates.
You can add your own blank Template objects and then design them using
the log window. For more information on how to design your own log
templates please refer to the **Working With Borehole Logs** chapter of
this user guide.

To make a new template use \<right-click\> \<New Template\>.

![](media\image33.png){width="2.03125in" height="0.5833333333333334in"}

Enter a name.

![](media\image34.PNG){width="3.3301017060367455in"
height="1.3421708223972004in"}

If **Project Template** is selected, this template will be saved when
you save the project and will be available to this project only.
Otherwise, when you choose to save this template, it will be saved in
the Ground Home WORKSPACE folder and will be available to all projects
in the future.

The new template is added to the folder and is ready to be worked on.

![](media\image35.PNG){width="1.9169346019247595in"
height="0.2604527559055118in"}

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

![](media\image36.jpeg){width="6.268055555555556in"
height="4.178472222222222in"}

*Original photo by Kobu Agency on Unsplash*

## Main Panels

The Groundhog user interface is arranged into a number of panels
containing data objects and graphics. Because Groundhog is a highly
interactive graphical tool you will benefit significantly from using a
good-quality mouse equipped with a mouse wheel -- a laptop track-pad is
not a good match with Groundhog.

![](media\image37.png){width="6.268055555555556in"
height="3.395138888888889in"}

### Main Toolbar **\[1\]**

Contains high-level buttons for key operations.

  ![](media\image38.png){width="0.4166666666666667in" height="0.4270833333333333in"}   Main Menu         This is the main menu button providing access to a series of high-level functions such as import/export.
  ------------------------------------------------------------------------------------ ----------------- -----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  ![](media\image39.png){width="0.3958333333333333in" height="0.3958333333333333in"}   Open Project      Opens a file chooser for opening Groundhog projects in the \*.gop file format.
  ![](media\image40.png){width="0.3854166666666667in" height="0.4270833333333333in"}   Save Project      Opens a file chooser for saving the current session to a Groundhog \*.gop file format.
  ![](media\image41.png){width="0.3958333333333333in" height="0.4166666666666667in"}   Open Map Window   Allows the creation of a new map (plan-view) window. When you create a new map window you will be prompted to select the data layers you want to see in the window. The available layers will depend on the data contained within your workspace or project. Press \<Skip\> to open a blank window.
  ![](media\image42.png){width="0.4270833333333333in" height="0.4270833333333333in"}   Open 3D Window    Opens the 3D graphics window.

### Session Panel **\[2\]**

A tabbed panel containing a range of session-level objects.

![](media\image43.PNG){width="2.6670384951881014in"
height="0.3750524934383202in"}

#### Workspace

This contains the main Object Tree panel with a hierarchical list of all
data objects in the session. For more details please refer to the Object
Tree section of this user guide.

#### Library

![](media\image44.png){width="0.8656714785651793in"
height="0.29289588801399824in"}A panel containing a configurable library
of available drawing codes (geology codes and other special codes).
Single-click on an entry to select it as the active drawing code -- this
sets the code as active in all windows. The below example shows
"BOULDERS" as the selected drawing code. Note that the special codes
"SHAPE" and "FAULT" are always at the top, and the rest of the list is
sorted alphabetically. Type into the search box to find codes. Click
\<All\> to reset the list back to all values after searching.

![](media\image45.png){width="3.186567147856518in"
height="2.401338582677165in"}

  ![](media\image46.png){width="0.7291666666666666in" height="0.34375in"}              Add Code       Add a drawing code, and optionally a matching colour, to the library.
  ------------------------------------------------------------------------------------ -------------- -----------------------------------------------------------------------
  ![](media\image47.png){width="0.6979166666666666in" height="0.34375in"}              Add Colour     Add a colour value to the library.
  ![](media\image48.png){width="0.8229166666666666in" height="0.3333333333333333in"}   Save Codes     Saves all current drawing codes to the global workspace.
  ![](media\image49.png){width="0.84375in" height="0.3541666666666667in"}              Save Colours   Saves all current colour values to the global workspace.

#### Time Controls

Where data and models have time-stamp information it is possible to use
this as a filter for selective display of a particular time interval
within the project. For example, you may have water level readings with
time-stamps in your borehole data which can be displayed and animated
with time. These features are currently undocumented. Please contact
<groundhog@bgs.ac.uk> for information.

![](media\image50.png){width="6.268055555555556in"
height="0.34305555555555556in"}

### Map Window **\[3\]**

A tabbed component capable of displaying multiple map panels. Each map
panel can display map data layers and can be used for digitizing points
and shapes, constructing cross-section alignments and for placing
borehole locations.

When you create a new map window you will be prompted to select the data
layers you want to see in the map. The icons for each layer indicate the
layer's data type. The available layers will depend on what data you
have in your workspace and project.

![](media\image51.png){width="6.268055555555556in"
height="4.198611111111111in"}

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

When you are working in the map view, if you are working in Great
Britain it is a good idea to always add the default ***Topographic
Basemap*** layer that is included with Groundhog for orientation
purposes. **Please note: the GB basemap is provided by a 3^rd^ party web
service and we make no warranty as to its accuracy or ongoing
availability**. Otherwise, you may wish to import a geo-registered image
of your site/project area for the same purpose.

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

![](media\image52.png){width="5.208333333333333in" height="2.65625in"}

#### Toolbar

![](media\image53.PNG){width="4.6360640857392825in"
height="0.6771773840769904in"}

+----------------------+----------------------+----------------------+
| ![](media\i          | Zoom To Extent       | Zooms to the full    |
| mage54.png){width="0 |                      | extent of all layers |
| .2916666666666667in" |                      | in the map panel, or |
| height="0.28125in"}  |                      | to the currently     |
|                      |                      | active layer, if one |
|                      |                      | is selected.         |
+======================+======================+======================+
| ![](media\i          | Zoom In              | Incrementally zooms  |
| mage55.png){width="0 |                      | the map to a larger  |
| .2708333333333333in" |                      | scale with each      |
| height="0.           |                      | successive click.    |
| 2708333333333333in"} |                      |                      |
+----------------------+----------------------+----------------------+
| ![](media\i          | Zoom Out             | Incrementally zooms  |
| mage56.png){width="0 |                      | the map to a smaller |
| .2604166666666667in" |                      | scale with each      |
| height="0.28125in"}  |                      | successive click.    |
+----------------------+----------------------+----------------------+
| ![](media\i          | Gazetteer            | Search for places    |
| mage57.png){width="0 |                      | (UK only) by place   |
| .2604166666666667in" |                      | name,                |
| height="0.           |                      | street+placement or  |
| 2604166666666667in"} |                      | county. Examples:    |
|                      |                      |                      |
|                      |                      | "Nottingham"         |
|                      |                      |                      |
|                      |                      | "Main Street,        |
|                      |                      | Keyworth"            |
|                      |                      |                      |
|                      |                      | "Rutland"            |
+----------------------+----------------------+----------------------+
| ![](media\i          | Select Drawing Code  | Click to open the    |
| mage58.png){width="0 |                      | drawing code library |
| .7910444006999126in" |                      | panel in order to    |
| height="0.2          |                      | change the active    |
| 2355643044619422in"} |                      | drawing code. Also   |
|                      |                      | displays the         |
|                      |                      | currently active     |
|                      |                      | drawing code,        |
|                      |                      | including its colour |
|                      |                      | and ornament if they |
|                      |                      | are available.       |
+----------------------+----------------------+----------------------+
| ![](media\i          | Print                | Send the current map |
| mage59.png){width="0 |                      | view to a printer.   |
| .2708333333333333in" |                      |                      |
| height="0.           |                      |                      |
| 2708333333333333in"} |                      |                      |
+----------------------+----------------------+----------------------+
| ![](media\i          | Save Image           | Save the current map |
| mage60.png){width="0 |                      | view to an image     |
| .3020833333333333in" |                      | (JPEG or PNG).       |
| height="0.25in"}     |                      |                      |
+----------------------+----------------------+----------------------+
| ![](media\i          | Save PDF             | Save the current map |
| mage61.png){width="0 |                      | view to a PDF        |
| .2604166666666667in" |                      | document.            |
| height="0.           |                      |                      |
| 2604166666666667in"} |                      |                      |
+----------------------+----------------------+----------------------+
| ![                   | Save Vector Graphics | Save the current map |
| ](media\image62.gif) |                      | view as a Vector     |
|                      |                      | Graphics (SVG)       |
|                      |                      | object               |
+----------------------+----------------------+----------------------+
| ![](media\image63.pn | Toggle Slider        | The layer slider     |
| g){width="0.53125in" |                      | allows partial view  |
| height="0.           |                      | of a user-defined    |
| 2604166666666667in"} |                      | collection of map    |
|                      |                      | data layers for      |
|                      |                      | rapid comparison.    |
|                      |                      | With the slider      |
|                      |                      | toggled on, use the  |
|                      |                      | mouse to drag the    |
|                      |                      | slider position in   |
|                      |                      | the map panel. The   |
|                      |                      | below example shows  |
|                      |                      | the BGS geology map  |
|                      |                      | WMS active as the    |
|                      |                      | active slider layer  |
|                      |                      | on top of a          |
|                      |                      | topographic basemap. |
|                      |                      | For information      |
|                      |                      | about how to make a  |
|                      |                      | particular layer     |
|                      |                      | active in the slider |
|                      |                      | refer to the section |
|                      |                      | on the Map Window    |
|                      |                      | Layer Control below. |
|                      |                      |                      |
|                      |                      | ![](media\i          |
|                      |                      | mage64.png){width="3 |
|                      |                      | .6343285214348207in" |
|                      |                      | height="1.           |
|                      |                      | 7510148731408575in"} |
+----------------------+----------------------+----------------------+

#### Right-Click Operations

The map panel supports a number of context-sensitive right-click
operations. These will depend on whether you are right-clicking on a
specific data object such as a cross-section alignment or a point
object, or whether you are in a "whitespace" area (a non-specific
portion of the panel). In general, a "whitespace" click will present the
following options.

![](media\image65.png){width="1.7083333333333333in"
height="1.1770833333333333in"}

+--------------------+------------------------------------------------+
| Centre The Map     | Enter a \[X, Y\] coordinate to centre the map  |
|                    | at a specific location.                        |
+====================+================================================+
| Set Map Scale      | Enter a value to zoom the map to an            |
|                    | approximate scale. For example, enter "10000"  |
|                    | to scale to 1:10k. Note that the exact scaling |
|                    | is dependent on screen resolution.             |
+--------------------+------------------------------------------------+
| Find A Place       | (Gazetteer) Search for places (GB only) by     |
|                    | place name, street+place name or county.       |
|                    | Examples:                                      |
|                    |                                                |
|                    | "Nottingham"                                   |
|                    |                                                |
|                    | "Main Street, Keyworth"                        |
|                    |                                                |
|                    | "Rutland"                                      |
|                    |                                                |
|                    | **Please note: this is a 3^rd^ party web       |
|                    | service and we make no guarantee as to         |
|                    | accuracy or availability.**                    |
+--------------------+------------------------------------------------+
| Show Grid Info     | Show UK grid reference for the mouse cursor    |
|                    | position, e.g.                                 |
|                    | ![](m                                          |
|                    | edia\image66.png){width="1.6492541557305336in" |
|                    | height="0.730919728783902in"}                  |
+--------------------+------------------------------------------------+
| Site Investigation | Currently contains one option to hyperlink out |
|                    | to the historic map(s) available from the NLS  |
|                    | for the clicked-on location (England and Wales |
|                    | only). For more information please refer to    |
|                    | the main section on developing conceptual site |
|                    | models.                                        |
+--------------------+------------------------------------------------+

### Map Window Layer Control **\[4\]**

When you create a new map window you will be prompted to select which
data layers you want to add to the window. You can add layers layer on
too. The layers you choose will be added to this layer control panel.
The panel also has its own toolbar.

#### Toolbar

![](media\image67.png){width="3.84375in" height="0.3958333333333333in"}

  ![](media\image68.png){width="0.3333333333333333in" height="0.3229166666666667in"}    Add Layers          Opens a list of available layers that can be added to the map. Note that the list does not present layers which are already in the map.
  ------------------------------------------------------------------------------------- ------------------- ----------------------------------------------------------------------------------------------------------------------------------------------------------------
  ![](media\image69.png){width="0.2604166666666667in" height="0.28125in"}               Undo                Undo on the last operation. **IMPORTANT:** please note that the undo only becomes active when a data layer is made active -- i.e., the undo is layer-specific.
  ![](media\image70.png){width="0.2708333333333333in" height="0.2708333333333333in"}    Redo                Redo on the last operation. **IMPORTANT:** please note that the redo only becomes active when a data layer is made active -- i.e., the redo is layer-specific.
  ![](media\image71.png){width="0.23958333333333334in" height="0.2708333333333333in"}   Remove All Layers   Clears the map of all data layers.
  ![](media\image72.png){width="0.25in" height="0.2708333333333333in"}                  Window Settings     Access high-level settings for the map window.
  ![](media\image73.png){width="0.2604166666666667in" height="0.25in"}                  Background Colour   Change the background colour of the map panel. This can be useful for improving clarity of certain types of data.

#### Layers

The layers panel lists all currently loaded layers within the map
window. Different map windows can have different layers loaded.

![](media\image74.png){width="3.7708333333333335in"
height="1.4479166666666667in"}

Checking the main tick-box on and off controls the visibility of each
layer. In the example below, ***Topographic Basemap*** is not visible in
the map panel, and ***Graticule*** is.

![](media\image75.png){width="1.9166666666666667in"
height="1.0520833333333333in"}

The slider controls under the name of each layer control the
transparency of the layers. Slide the bar all the way to the left to
make the layer completely transparent. Slide the bar all the way to the
right to make the layer completely opaque.

![](media\image76.png){width="1.8854166666666667in"
height="1.4791666666666667in"}

Single-click on a layer to make it the active layer. Depending on the
layer type this may activate drawing/editing tools, query tools, or it
may do nothing. When a layer is active it displays in orange. Only one
layer can be active at a time. Single-click on the active layer to
de-activate it. The example below shows the Cross-Sections layer as
active.

![](media\image77.png){width="3.8020833333333335in"
height="1.4166666666666667in"}

The order of the layers in the panel dictates the drawing order in the
map panel. The layer at the top of the list will be drawn as the top
layer in the map graphics panel. The exception to this is that the
active layer is always drawn on top of everything else.

To change the drawing order of a layer, single-click and hold on the
layer, and drag it to re-position it in the list. In the example below,
the Cross-Sections layer is being dragged upwards.

![](media\image78.png){width="3.8333333333333335in" height="1.40625in"}

Each layer has four buttons on the right-hand side of its row.

![](media\image79.png){width="0.4895833333333333in" height="0.46875in"}

  ![](media\image80.png){width="0.2708333333333333in" height="0.25in"}                                                                                           Settings              Access layer-specific settings.
  -------------------------------------------------------------------------------------------------------------------------------------------------------------- --------------------- ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  ![](media\image81.png){width="0.23958333333333334in" height="0.23958333333333334in"}![](media\image82.png){width="0.28125in" height="0.20833333333333334in"}   Toggle Slider Layer   Toggles the layer in and out of the active slider layer (see above for information about the slider controls). When the toggle button is orange it means the layer is active in the slider.
  ![](media\image83.png){width="0.23958333333333334in" height="0.23958333333333334in"}                                                                           Filter                At the moment this button is disabled for all layers pending future filtering capability.
  ![](media\image84.png){width="0.25in" height="0.22916666666666666in"}                                                                                          Remove                Removes the layer from the current window (does ***not*** delete the layer from the project!)

There are a number of operations available by right-clicking in any
blank or "whitespace" portion of the layer control.

![](media\image85.PNG){width="1.802334864391951in"
height="1.250174978127734in"}

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

![](media\image86.png){width="6.268055555555556in"
height="1.7465277777777777in"}

You can move the palette around in the map panel by dragging the green
bar along the top of the box. Note that the palette becomes less
transparent when the mouse cursor is over it.

![](media\image87.png){width="3.156715879265092in"
height="1.7158661417322834in"}

For more detailed information on the various tools available in the
palette, depending on the layer type, please refer to the section
**Drawing Points & Shapes** within this user guide.

When a layer is active you may see variations on the right-click option
available in the map window and also depending on whether you have
right-clicked on an object or whitespace.

Some layers have identify capability when they are active. The identify
operation is not a separate tool within groundhog -- instead, with a
layer active, just single-click on an object or location. A good example
is the BGS WMS layers where the identify is active everywhere on the
geology map. If the identify query yields results they will be displayed
in the lower half of the map window layer control.

![](media\image88.PNG){width="6.268055555555556in"
height="2.0756944444444443in"}

Notice the two options circled in red. These are **Copy the identify
data to the clipboard** and **Add the lexicon code to the library
panel**.

### Cross-Section Window **\[5\]**

A tabbed component capable of displaying multiple cross-section panels.
Each cross-section panel can display profile data layers and can be used
for drawing geological interpretations, viewing borehole transects and
digitizing points and shapes. Unlike the map window, you can't just
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

![](media\image89.PNG){width="5.313241469816273in"
height="0.6980139982502187in"}

+----------------------+----------------------+----------------------+
| ![](media\i          | Vertical             | Sets the vertical    |
| mage90.png){width="0 | Exaggeration         | exaggeration for the |
| .7291666666666666in" |                      | panel. Contains a    |
| height="0.           |                      | list of pre-set      |
| 3541666666666667in"} |                      | values and can also  |
|                      |                      | be typed into for    |
|                      |                      | custom values.       |
+======================+======================+======================+
| ![](media\i          | Zoom To Extent       | Zooms to the full    |
| mage91.png){width="0 |                      | extent of all the    |
| .2708333333333333in" |                      | cross-section.       |
| height="0.           |                      |                      |
| 2708333333333333in"} |                      |                      |
+----------------------+----------------------+----------------------+
| ![](media\im         | Marquee Zoom         | Draw a box to zoom   |
| age92.png){width="0. |                      | to that area of the  |
| 22916666666666666in" |                      | panel.               |
| height="0.25in"}     |                      |                      |
+----------------------+----------------------+----------------------+
| ![](media\i          | Incrementally zooms  | Incrementally zooms  |
| mage93.png){width="0 | the panel to a       | the cross-section to |
| .3020833333333333in" | smaller scale with   | a smaller scale with |
| height="0.28125in"}  | each successive      | each successive      |
|                      | click.               | click.               |
+----------------------+----------------------+----------------------+
| ![](media\image94.pn | Refresh              | Refreshes the        |
| g){width="0.28125in" |                      | graphics panel.      |
| height="0.           |                      |                      |
| 3020833333333333in"} |                      |                      |
+----------------------+----------------------+----------------------+
| ![](media\image95    | Select Drawing Code  | Click to open the    |
| .png){width="0.75in" |                      | drawing code library |
| height="0.           |                      | panel in order to    |
| 2916666666666667in"} |                      | change the active    |
|                      |                      | drawing code. Also   |
|                      |                      | displays the         |
|                      |                      | currently active     |
|                      |                      | drawing code,        |
|                      |                      | including its colour |
|                      |                      | and ornament if they |
|                      |                      | are available.       |
+----------------------+----------------------+----------------------+
| ![](media\i          | Print                | Send the current     |
| mage59.png){width="0 |                      | cross-section view   |
| .2708333333333333in" |                      | to a printer.        |
| height="0.           |                      |                      |
| 2708333333333333in"} |                      |                      |
+----------------------+----------------------+----------------------+
| ![](media\i          | Save Image           | Save the current     |
| mage60.png){width="0 |                      | cross-section view   |
| .3020833333333333in" |                      | to an image (JPEG or |
| height="0.25in"}     |                      | PNG).                |
+----------------------+----------------------+----------------------+
| ![](media\i          | Save PDF             | Save the current     |
| mage61.png){width="0 |                      | cross-section view   |
| .2604166666666667in" |                      | to a PDF document.   |
| height="0.           |                      |                      |
| 2604166666666667in"} |                      |                      |
+----------------------+----------------------+----------------------+
| ![](media\im         | Save Vector Graphics | Save the current     |
| age96.gif){width="0. |                      | cross-section view   |
| 16666666666666666in" |                      | as a Vector Graphics |
| height="0.1          |                      | (SVG) object         |
| 6666666666666666in"} |                      |                      |
+----------------------+----------------------+----------------------+
| ![](media\image63.pn | Toggle Slider        | The layer slider     |
| g){width="0.53125in" |                      | allows partial view  |
| height="0.           |                      | of a user-defined    |
| 2604166666666667in"} |                      | collection of        |
|                      |                      | cross-section data   |
|                      |                      | layers for rapid     |
|                      |                      | comparison. With the |
|                      |                      | slider toggled on,   |
|                      |                      | use the mouse to     |
|                      |                      | drag the slider      |
|                      |                      | position in the      |
|                      |                      | graphics panel. The  |
|                      |                      | below example shows  |
|                      |                      | the Geology layer as |
|                      |                      | the active slider    |
|                      |                      | layer on top of a    |
|                      |                      | Terrain Profile      |
|                      |                      | layer. For           |
|                      |                      | information about    |
|                      |                      | how to make a        |
|                      |                      | particular layer     |
|                      |                      | active in the slider |
|                      |                      | refer to the section |
|                      |                      | on the Cross-Section |
|                      |                      | Window Layer Control |
|                      |                      | below.               |
|                      |                      |                      |
|                      |                      | ![](media\           |
|                      |                      | image97.png){width=" |
|                      |                      | 3.536712598425197in" |
|                      |                      | height="1            |
|                      |                      | .141809930008749in"} |
+----------------------+----------------------+----------------------+

#### Right-Click Operations

The cross-section panel supports a number of context-sensitive
right-click operations. These will depend on whether you are
right-clicking on a specific data object such as a geology line or a
shape object, or whether you are in a "whitespace" area (a non-specific
portion of the panel). In general, a "whitespace" click will present the
following options.

![](media\image98.png){width="1.8541666666666667in"
height="0.8541666666666666in"}

+----------------------+----------------------------------------------+
| Create Line \[CODE\] | Allows creation of a fixed-elevation geology |
|                      | line using the currently active drawing      |
|                      | code.                                        |
+======================+==============================================+
| New Shape Layer      | Creates a new cross-section shape layer      |
|                      | which you can draw into.                     |
+----------------------+----------------------------------------------+
| New Annotation Layer | Creates a new annotation layer which can be  |
|                      | used to add labels, arrows and graphics to   |
|                      | the cross-section.                           |
|                      |                                              |
|                      | *Professional*                               |
+----------------------+----------------------------------------------+

### Cross-Section Window Layer Control **\[6\]**

This panel lists the data layers which are currently added to the
cross-section window. The panel also has its own toolbar.

#### Toolbar

![](media\image99.png){width="3.03125in" height="0.4270833333333333in"}

  ![](media\image68.png){width="0.3333333333333333in" height="0.3229166666666667in"}   Add Layers          Opens a list of available layers that can be added to the window. Note that the list does not present layers which are already in the list.
  ------------------------------------------------------------------------------------ ------------------- ---------------------------------------------------------------------------------------------------------------------------------------------
  ![](media\image69.png){width="0.2604166666666667in" height="0.28125in"}              Undo                Undo on the last operation. **IMPORTANT:** please note that the undo is global across all layers.
  ![](media\image70.png){width="0.2708333333333333in" height="0.2708333333333333in"}   Redo                Redo on the last operation. **IMPORTANT:** please note that the redo is global across all layers.
  ![](media\image72.png){width="0.25in" height="0.2708333333333333in"}                 Window Settings     Access high-level settings for the cross-section window.
  ![](media\image73.png){width="0.2604166666666667in" height="0.25in"}                 Background Colour   Change the background colour of the graphics panel. This can be useful for improving clarity of certain types of data.

#### Layers

The layers panel lists all currently loaded layers within the
cross-section window. Different windows can have different layers
loaded.

![](media\image100.png){width="4.276119860017498in"
height="1.6521369203849519in"}

Checking the main tick-box on and off controls the visibility of each
layer. In the example below, ***Terrain Profile*** is not visible in the
section panel, and ***Graticule*** is.

![](media\image101.png){width="1.6145833333333333in" height="0.96875in"}

The slider controls under the name of each layer control the
transparency of the layers. Slide the bar all the way to the left to
make the layer completely transparent. Slide the bar all the way to the
right to make the layer completely opaque.

![](media\image102.png){width="1.3507458442694664in"
height="1.5744892825896764in"}

Single-click on a layer to make it the active layer. Depending on the
layer type this may activate drawing/editing tools, query tools, or it
may do nothing. When a layer is active it displays in orange. Only one
layer can be active at a time. Single-click on the active layer to
de-activate it. The example below shows the ***Geology*** layer as
active.

![](media\image103.png){width="3.6791043307086615in"
height="1.413267716535433in"}

The order of the layers in the panel dictates the drawing order in the
cross-section panel. The layer at the top of the list will be drawn as
the top layer in the graphics panel. The exception to this is that the
active layer is always drawn on top of everything else.

To change the drawing order of a layer, single-click and hold on the
layer, and drag it to re-position it in the list. In the example below,
the Cross-Sections layer is being dragged upwards.

![](media\image104.png){width="3.962687007874016in"
height="1.5410454943132108in"}

Each layer has four buttons on the right-hand side of its row.

![](media\image79.png){width="0.4895833333333333in" height="0.46875in"}

  ![](media\image80.png){width="0.2708333333333333in" height="0.25in"}                                                                                           Settings              Access layer-specific settings.
  -------------------------------------------------------------------------------------------------------------------------------------------------------------- --------------------- ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  ![](media\image81.png){width="0.23958333333333334in" height="0.23958333333333334in"}![](media\image82.png){width="0.28125in" height="0.20833333333333334in"}   Toggle Slider Layer   Toggles the layer in and out of the active slider layer (see above for information about the slider controls). When the toggle button is orange it means the layer is active in the slider.
  ![](media\image83.png){width="0.23958333333333334in" height="0.23958333333333334in"}                                                                           Filter                At the moment this button is disabled for all layers pending future filtering capability.
  ![](media\image84.png){width="0.25in" height="0.22916666666666666in"}                                                                                          Remove                Removes the layer from the current window (does ***not*** delete the layer from the project!)

There are a number of operations available by right-clicking in any
blank or "whitespace" portion of the layer control.

![](media\image105.PNG){width="2.7295472440944883in"
height="1.5627176290463691in"}

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

![](media\image106.png){width="4.514925634295713in"
height="2.189433508311461in"}

You can move the palette around in the panel by dragging the green bar
along the top of the box. Note that the palette becomes less transparent
when the mouse cursor is over it.

![](media\image107.png){width="4.111940069991251in"
height="2.293594706911636in"}

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

![](media\image108.png){width="1.9895833333333333in"
height="1.7604166666666667in"}

#### Progress Bar

This displays the progress of certain processing operations, such as
project loading and model building operations.

![](media\image109.png){width="2.21875in" height="0.375in"}

# Importing & Exporting Data

This section provides details of the various import and export
capabilities of Groundhog.

![](media\image110.jpeg){width="6.268055555555556in"
height="4.184722222222222in"}

*Photo by Mika Baumeister on Unsplash*

## Images

You can import images into your project in JPG/JPEG and PNG file
formats. There are several ways to import them.

\<Main Menu\> \<Import\> \<Image\>.

![](media\image111.png){width="4.53125in" height="1.5104166666666667in"}

\<Right-Click\> on Images sub-folder.

![](media\image112.png){width="2.4375in" height="2.1666666666666665in"}

Drag image file from folder or desktop.

![](media\image113.png){width="3.4260870516185475in"
height="2.4174332895888013in"}

Drag image from web browser (browser dependent, test using Google
Chrome).

![](media\image114.png){width="6.268055555555556in"
height="3.0993055555555555in"}

If you have difficulty dragging an image from the web browser,
right-click on the image and open it in a new browser tab and try again.

When images are loaded they appear in the object tree under \<Site /
Project\> \<Associated Files\> \<Images\>.

![](media\image115.png){width="3.3958333333333335in" height="2.40625in"}

Double-click the entry in the tree, or use \<Right-Click\> \<View
Image\> to view the image.

![](media\image116.png){width="3.9583333333333335in"
height="1.3333333333333333in"}

![](media\image117.png){width="4.2in" height="2.103626421697288in"}

If the image is geo-registered and the world file is present, Groundhog
will load the image together with its geo-registration information. When
you add the image to a map window as a new layer it will display in the
correct spatial location.

If you have an image that is not geo-registered, you can still add it to
a map window as a layer. By default it will fill the available panel.
Make the image layer editable and use the blue drag handles to register
the image to the correct location.

![](media\image118.png){width="4.634782370953631in"
height="2.1505063429571303in"}

![](media\image119.png){width="6.268055555555556in"
height="4.579166666666667in"}

![](media\image120.png){width="6.268055555555556in"
height="3.895138888888889in"}

When the project is saved, Groundhog will generate a world file for the
registration information.

## Shapefiles

Groundhog has basic support for ESRI shapefiles (\*.shp). However, the
shapefile format is proprietary and Groundhog relies on 3^rd^ party
libraries to support the import filter. Therefore, not all features of
the file format are necessarily available, but most Point and Line type
files should load. Complex multi-polygon files may be less reliable.

Import the file using \<Main Menu\> \<Import\> \<Shapefile (\*.shp)\>.

![](media\image121.png){width="4.385416666666667in" height="1.84375in"}

Alternatively, drag the \*.shp file into Groundhog from a folder or the
desktop.

The data is imported as a new folder under the Location Layers (points)
of Shape Layers (polyline), respectively. These folders can be added to
any map window as a layer for display.

![](media\image122.png){width="6.268055555555556in"
height="1.5159722222222223in"}

A right-click option provides access to a simple view (non-editable) of
the attribute table.

![](media\image123.png){width="3.15625in" height="0.9375in"}

![](media\image124.png){width="6.268055555555556in"
height="1.7534722222222223in"}

You can export Point and Shape type layers to shapefile format using
\<Right-Click\> \<Import / Export\> \<Export\> \<Shapefile (\*.SHP)\>

![](media\image125.png){width="5.270833333333333in" height="1.5625in"}

![](media\image126.png){width="5.416666666666667in" height="1.4375in"}

## ASCII Grids

ASCII grids can be imported and used either to display profiles or set
as the surface layer (topography, i.e. DEM/DTM). Groundhog supports
grids in ESRI's ASCII format.

<https://en.wikipedia.org/wiki/Esri_grid>

The grid data can be imported manually via \<Main Menu\> \<Import\>
\<ESRI ASCII Grid (\*.asc)\>

![](media\image127.png){width="4.458333333333333in"
height="1.6145833333333333in"}

**Alternatively, and especially for a series of files, paste them into
either the WORKSPACE or the PROJECT directory and restart Groundhog.
This makes the grid data available across all sessions/projects.**

When ASCII grids are loaded into Groundhog they are converted to a
binary equivalent called a BGRID. This is so that the data can be
queried more efficiently without loading the whole grid to memory.

Loaded grids appear in the object tree under \<Models\> \<Reference
Grids\> and each label displays the extent of the grid object.

![](media\image128.png){width="6.268055555555556in" height="2.78125in"}

At present there is only a simple way to display the grid in the map,
and that is as a simple extent rectangle. To do so, highlight the
desired grid object in the tree and a blue rectangle will appear in the
map window showing the extent of that grid.

![](media\image129.png){width="5.0625in" height="1.625in"}

You can set a grid to be the default topographic surface layer within
the project. This means the grid will be used as the basis of terrain
profile (topography) generation in cross-sections by default.

\<Right-Click\> \<Set As 'Surface Layer'\>

![](media\image130.png){width="2.8854166666666665in"
height="0.7083333333333334in"}

The currently set 'surface layer' grid will be displayed as bold in the
object tree list.

![](media\image131.png){width="2.8541666666666665in"
height="1.2916666666666667in"}

## OBJ Files

3D objects can be imported from the industry-standard OBJ data format.

![](media\image132.png){width="6.268055555555556in"
height="2.6659722222222224in"}

Loaded objects will appear in the data tree.

![](media\image133.png){width="2.3541666666666665in" height="1.59375in"}

OBJ objects can be added to the 3D view.

# Working With Borehole Logs

This section provides details on how to import and display your borehole
data, make edits to the data and design your own custom log templates.
It includes discussion of how to handle geotechnical and geophysical
borehole data in AGS and LAS formats.

![](media\image134.jpeg){width="6.268055555555556in"
height="4.178472222222222in"}

*Photo by Sven Mieke on Unsplash*

## Borehole Data Import

Groundhog supports a range of borehole data models and import options.
When borehole data is loaded it will appear in the object tree under
***Site / Project \> Location Layers***.

![](media\image135.PNG){width="4.1047397200349955in"
height="1.7710804899387576in"}

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

![](media\image136.PNG){width="5.2715693350831145in"
height="1.5939720034995626in"}

![](media\image137.PNG){width="6.268055555555556in"
height="1.5611111111111111in"}

In the following example the collar and geology data are split between
two separate CSV files. Note that both files have a field that contains
the name of the borehole, which will be mapped as the ID field for
matching up the geology records to the correct location. This field does
not have to be called NAME, it can be called anything as it will be
mapped on import. It can also have different names in the collar and
geology files. The file names are also not important.

![](media\image138.PNG){width="2.239896106736658in"
height="1.3439370078740158in"}

Collar.csv

![](media\image139.PNG){width="3.27128937007874in"
height="1.1043208661417323in"}

Geology.csv

![](media\image140.PNG){width="5.292404855643045in"
height="2.2503138670166227in"}

### Importing CSV

There are two routes to import boreholes from CSV.

1.  Combined collar and geology import,

2.  Individual import.

#### Combined Import

This option provides a short-cut to import the collar, geology
optionally survey data in a single step. It will work whether your data
is split into separate collar and geology data files, or merged into a
single file.

***Main Menu \> Import \> Borehole Data***

![](media\image141.PNG){width="4.3964468503937in"
height="1.2293383639545057in"}

The dialog contains a tab for the collar and a tab for the geology.
Click on the ***Choose File*** button on each tab to load up the data.

![](media\image142.png){width="1.9481889763779527in"
height="1.0209755030621173in"}

The names of the fields in the data file are listed to the left of the
panel. Ignore the UNIT and TYPE columns.

Use the drop-down options in the **ALIAS** column to tell Groundhog the
meaning of each field in the imported data file. Choose **\<\< Exclude
From Import \>\>** for any redundant fields. The required fields for the
import type are marked in red in the drop-down list of possible
**ALIAS** values.

![](media\image143.PNG){width="6.268055555555556in"
height="3.0743055555555556in"}

In this example we are working with the combined data file that contains
both the collar and geology data. Note the mappings, including the
fields that have been excluded.

![](media\image144.PNG){width="4.542300962379702in"
height="2.9379101049868765in"}

Note that the **LEVEL** field from the data file (which is the start
height or elevation of the borehole) has been mapped to **Z**. This
field is not mandatory for the import, but if there is a value available
for this you should always map it.

Next, switch to the Geology tab and bring in the CSV file containing the
geology data. Again, in this example, the data is in the same single
file as the collar data.

The fields required for the geology import are different than for the
collar data. Again, they are highlighted in red in the drop-down list.

![](media\image145.PNG){width="2.5628576115485564in"
height="1.6877351268591425in"}

![](media\image146.PNG){width="4.656899606299213in"
height="3.8130325896762907in"}

**IMPORTANT:** Make sure to use the correct field to map the **LOCATION
ID** alias, as this will be used to match the records between the collar
and geology data. GEOL and DESCRIPTION are both important fields that we
want to see in the geology log, but they do not need to be mapped to any
specific expected Groundhog field. So, they will just be imported using
the name used in the data file.

Optionally, switch to the survey tab and bring in the CSV file
containing the survey data. In this example, the data is in a separate
file from the collar data.

The fields required for the survey import are different than for the
collar and geology data. Again, they are highlighted in red in the
drop-down list. Depth is the measured depth from the top of the
borehole.

![](media\image147.png){width="2.489931102362205in"
height="1.802334864391951in"}

Click ***OK***.

If you have missed out any required fields in the **ALIAS** mappings,
you will see this message. Go back into the mappings panels and correct
these.

![](media\image148.png){width="3.84375in" height="1.21875in"}

Otherwise, the import will request a dataset name. This should be a
unique name that you wish to use to identify the dataset within
Groundhog. On selecting OK to this the import will proceed and a new
borehole dataset folder will be created in the data tree.

![](media\image149.PNG){width="4.073485345581802in"
height="4.917352362204724in"}

#### Individual Import

This option allows the borehole dataset to be assembled one data file at
a time. It also leads into the import of generic tabular data which is
described in the following section.

First, create an empty borehole dataset folder in the tree.

![](media\image150.PNG){width="3.969304461942257in"
height="1.271010498687664in"}

Enter a name for the folder.

![](media\image151.png){width="2.75in" height="1.2708333333333333in"}

When prompted, click ***Yes*** to specify a borehole layer.

![](media\image152.PNG){width="3.427561242344707in"
height="1.6773173665791776in"}

The new, empty borehole dataset folder will be created in the data tree.

Use ***Right-Click \> Import / Export \> Import \> Collar*** on the
borehole folder and select the file containing the collar data.

![](media\image153.PNG){width="5.886237970253719in"
height="2.1461329833770777in"}

![](media\image154.png){width="5.21875in" height="2.3854166666666665in"}

Use the pull-down ALIAS options to map the imported fields to the fields
expected by Groundhog and click Apply. In the case of collar data this
could be;

-   LOCATION ID

-   X

-   Y

-   Z (collar height or ground level)

![](media\image155.png){width="6.268055555555556in"
height="2.4319444444444445in"}

The imported collar entries are added to the data tree.

![](media\image156.png){width="2.65625in" height="1.75in"}

Next, import the geology data using ***Right-Click \> Import /Export \>
Import \> Geology Intervals*** on the borehole folder and select the
file containing the geology interval/log data.

![](media\image157.PNG){width="6.1779451006124235in"
height="2.5211854768153983in"}

![](media\image158.png){width="5.927083333333333in"
height="3.0520833333333335in"}

If the depth values in the log file are elevation, as opposed to
depth-down-hole, check the special option box on the right of the file
chooser dialog (**NOTE:** this function will only work if the collar has
a Z, or ground level, value).

Map the fields using the drop-down options in the **ALIAS** column of
the import screen. Required fields are highlighted in red. Click Apply.

![](media\image159.PNG){width="4.573555336832896in"
height="2.000278871391076in"}

Inspect the data tree to see the imported geology logs.

![](media\image160.PNG){width="3.698432852143482in"
height="4.688153980752406in"}

### Importing Tabular Data

Besides the collar data and geology interval logs, Groundhog can also
import any arbitrary down-hole data in tabular format. For example,
sample and test data (in-situ and laboratory), geophysical measurements,
installation and monitoring data, etc.

It is important to note that tabular data is held at the borehole
dataset folder level and not against individual boreholes.

![](media\image161.PNG){width="2.771220472440945in"
height="1.7606627296587927in"}

The rows within each table are mapped to the appropriate borehole object
using an ID field.

To import a table of data use ***Right-Click \> Import / Export \>
Import \> Tabular Data***

![](media\image162.PNG){width="5.875820209973753in"
height="2.7816382327209097in"}

Use the file chooser dialog to select the CSV file containing the data.

![](media\image163.png){width="5.489583333333333in"
height="2.7604166666666665in"}

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

![](media\image164.png){width="6.268055555555556in"
height="4.406944444444444in"}

You can also preview the data in the file using the Data tab, **but
currently you can't edit the data**.

![](media\image165.png){width="5.822916666666667in"
height="2.2291666666666665in"}

Here is an example of a CSV file viewed in Excel, containing sample
information for two boreholes with FROM and TO depth fields.

![](media\image166.PNG){width="3.667178477690289in"
height="1.5522998687664042in"}

![](media\image167.PNG){width="4.615227471566055in"
height="1.7606627296587927in"}

Once imported, the table will appear in the data tree.

![](media\image168.PNG){width="2.792055993000875in"
height="1.9690244969378827in"}

Double-click on the table entry, or use right-click, to view the table
and edit the field mappings once loaded.

![](media\image169.PNG){width="5.479931102362205in"
height="2.2503138670166227in"}

The following example shows how to import a depth-related value, such as
geophysical test data, with a single test DEPTH field.

![](media\image170.PNG){width="4.083903105861768in"
height="2.604529746281715in"}

![](media\image171.png){width="4.583333333333333in"
height="1.7291666666666667in"}

The following image below shows how the data from the tables can be used
in log templates, for example.

![](media\image172.PNG){width="4.80799978127734in"
height="5.826490594925635in"}

### 

### Importing AGS Format Data

The AGS standard is a file format for the transfer of factual site
investigation data in the UK and elsewhere. It is supported as an import
option within Groundhog and, once imported, is treated as a set of data
tables, much the same as a standard CSV import would be.

From the main menu, choose ***Import \> AGS Data Format Tables***

![](media\image173.PNG){width="4.438118985126859in"
height="1.3856102362204725in"}

Select the AGS file (v3.1 and v4 is are both supported). The imported
data will take the form of a borehole dataset folder. Expand the folder
to explore the imported geology logs (if present in the data file) and
the various test and descriptive tables.

![](media\image174.png){width="6.268055555555556in"
height="4.969444444444444in"}

![](media\image175.png){width="6.1875in" height="3.46875in"}

Sample AGS data taken from the AGS data format v4 example data file.

### Importing LAS Format Data

Groundhog supports the industry-standard Canadian Well Logging LAS data
format for geophysical wireline log data. The imported data is stored in
Groundhog data tables, similar to data imported from a tabular format
such as CSV.

From the main menu, choose ***Import \> Well Log Data (\*.las)***

![](media\image176.PNG){width="4.333938101487314in"
height="2.3649136045494314in"}

The collar data is attached to the borehole entry in the data tree as a
series of attributes.

![](media\image177.PNG){width="3.6359241032370955in"
height="5.042369860017498in"}

The test data appears as a table called Curve Data under the Data Tables
sub-folder of the borehole dataset folder (example file shown courtesy
of Kansas Geological Survey download portal -
<http://www.kgs.ku.edu/Magellan/Logs/>).

![](media\image178.PNG){width="3.021255468066492in"
height="1.7814982502187227in"}

Double-click the table, or use right-click to view and edit the table
mappings and to preview the data values (not editable).

![](media\image179.png){width="3.8079997812773403in"
height="3.1364074803149604in"}

![](media\image180.png){width="6.268055555555556in"
height="3.854861111111111in"}

The data in the table can be used in log templates, as-per any tabular
data.

![](media\image181.png){width="5.083333333333333in" height="6.25in"}

#### Deviated LAS borehole

If your LAS file is representing a deviated borehole then you will need
to perform a few extra steps.

When your file chooser opens you will need to check the box on the right
hand side.

![](media\image182.png){width="6.268055555555556in" height="1.8625in"}

If the deviation path is recorded inside the las file you have chosen
also check the new box that appears.

![](media\image183.png){width="1.5627176290463691in"
height="0.5209055118110236in"}

Otherwise, leave it unchecked and you will be asked to choose the CSV
which contains the deviation data.

The familiar mapping dialog will then be presented where you will need
to map the required fields -- LOCATION ID, DEPTH, DIP and AZIMUTH.

![](media\image184.png){width="4.542300962379702in"
height="3.0941819772528434in"}

Ensure that the units are selected for DEPTH, the default is METERS but
if measured in feet, use the abbreviation **ft**.

![](media\image185.png){width="6.105018591426072in"
height="1.5418821084864391in"}

Click **Apply** and the borehole will be de-surveyed for viewing (best
in 3D).

### BGS Borehole Records

There are two ways to view borehole records held by the BGS, (1) view
original driller's logs and (2) download AGS data.

#### Viewing Driller's Logs From BGS

BGS holds driller's logs as scanned images for many of the borehole
records. The locations of the records are available as a WMS (Web Map
Service) which can be displayed in the Groundhog map window as a layer.

![](media\image186.png){width="5.53125in" height="1.5729166666666667in"}

From the panel on the right of the layer selection dialog, select the
layer called **\[GeoIndex Boreholes theme\] Borehole records**.

![](media\image187.png){width="6.268055555555556in"
height="1.3930555555555555in"}

Zoom into an area to see the available records as a point layer.

![](media\image188.png){width="4.427206911636046in"
height="3.0260870516185476in"}

Make the WMS points layer active by clicking on it in the layer control.
When it is active it will turn orange. Now that the layer is active,
click on any dot in the map to perform an identify query. The results
will display in a panel on the right.

![](media\image189.png){width="6.268055555555556in"
height="2.598611111111111in"}

In the identify results panel, click on the borehole stick icon to
hyperlink to the BGS record (opens in default web browser).

![](media\image190.png){width="2.1145833333333335in"
height="0.8958333333333334in"}

![](media\image191.png){width="6.268055555555556in"
height="4.842361111111111in"}

#### Downloading AGS Data From BGS

The BGS' NGDC Digital Data Deposit Application can be used by industry
and the public to deposit data into the BGS archives.

<http://transfer.bgs.ac.uk/ingestion>

Any AGS format data locations that are ingested are served back at as a
WMS (Web Map Service) layer that can be displayed and queried within
Groundhog.

In a map window, open the add layers dialog.

![](media\image186.png){width="5.53125in" height="1.5729166666666667in"}

From the panel on the right of the layer selection dialog, select the
layer called **\[AGS Export\] Boreholes**.

![](media\image192.png){width="6.268055555555556in"
height="0.9763888888888889in"}

Zoom into an area to see the available records as a point layer.

![](media\image193.png){width="6.268055555555556in"
height="4.0159722222222225in"}

Make the WMS points layer active by clicking on it in the layer control.
When it is active it will turn orange. Now that the layer is active,
click on any dot in the map to perform an identify query. The results
will display in a panel on the right.

![](media\image194.png){width="2.2608694225721786in"
height="0.8913823272090988in"}

![](media\image195.png){width="6.268055555555556in"
height="2.259027777777778in"}

Click on the AGS save button in the identify results panel to attempt a
download of the corresponding AGS data from the BGS database. Not all
records have AGS data attached, but most should work.

![](media\image196.png){width="3.4166666666666665in"
height="1.3229166666666667in"}

![](media\image197.png){width="2.75in" height="1.21875in"}

The data will appear in the object tree as a new borehole dataset folder
ad can be worked with like any imported borehole dataset. The dataset
will also be automatically added to the current map window.

## 

## Displaying Boreholes

Borehole data is displayed using custom templates. These are
column-based design templates and you can create your own within
Groundhog. Once you have designed your template you can re-use it in
each session and you can also share it with other Groundhog users.

Groundhog also ships with a default set of log templates for basic
borehole display. It also includes standard templates for AGS boreholes
and trial pits.

### Creating Borehole Log Templates

The first step is to create a new, blank template in the object tree via
\<System Objects\> \<Templates\> \<right-click\> \<New Template\>

![](media\image198.png){width="3.65625in" height="1.8645833333333333in"}

Enter a name.

![](media\image199.PNG){width="3.3541666666666665in"
height="1.3380282152230971in"}

There are two different types of templates -- those held in the
workspace and those held against a specific project. Workspace templates
can be used in any project and are held within the Groundhog home folder
structure. The advantage of project templates is that they are saved
alongside the project and it is easy to package them up with the project
and share them with another user.

Next, send a borehole to the blank template using \<right-click\> \<View
Borehole Log\> either in the object tree on from a borehole position in
a map window.

![](media\image200.png){width="2.283581583552056in"
height="1.445203412073491in"}

![](media\image201.png){width="3.1716415135608047in"
height="2.384575678040245in"}

When prompted, choose the new template that you just created.

![](media\image202.png){width="2.149254155730534in"
height="0.9932163167104112in"}

Decide whether to always use this template for this borehole.

![](media\image203.png){width="3.3059700349956254in"
height="0.9187609361329834in"}

The borehole will attempt to display in the blank template, but will
most likely look incorrect/blank because at this stage the template has
no way of knowing which data fields to display. To make the template
look how you want it you will need to make some edits to the design.

![](media\image204.png){width="3.3283584864391953in"
height="1.9558628608923885in"}

### Editing Borehole Log Templates

This section assumes a new, blank template (see previous section) is the
starting point for creating a template design, but the same principles
also apply to existing templates.

Switch the template to edit mode. You can use either the edit mode
button, or you can right-click in the template itself and choose \<Edit
Template\>.

![](media\image205.PNG){width="3.7505238407699037in"
height="1.8752613735783028in"}

When the log template is in edit mode, the border lines will turn blue
and an editing label will appear in red at the top of the page. To exit
edit mode, press the \<Stop Editing Template\> button again.

![](media\image206.png){width="4.669564741907261in"
height="1.7879746281714786in"}

Groundhog arranges the log design into three areas, the header, columns
and footer.

![](media\image207.png){width="2.275738188976378in"
height="2.9478258967629047in"}

The size and width of the top-level areas can be modified by hovering
over a template line and dragging it. When a line is drag-able, as the
mouse hovers over it, it will highlight as an extended green line.

![](media\image208.png){width="6.268055555555556in"
height="1.8034722222222221in"}

#### Header

The header is a tabular component which can be used to display a
document title, data fields, free-text labels and a corporate logo. To
edit the contents of a cell, use right-click.

![](media\image209.png){width="5.008695319335083in"
height="1.1080391513560806in"}

![](media\image210.png){width="4.878261154855643in"
height="1.1563287401574802in"}

The field and title values can be free text or taken from data fields in
the borehole data itself. When you edit such a cell, you will be
presented with the field editing dialog. This dialog presents a list of
available dynamic fields, both pre-set (e.g. date/time, page number) and
data-driven (e.g. borehole attributes).

![](media\image211.png){width="4.020833333333333in"
height="6.177083333333333in"}

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

Here is an example of a field value using a field called LOCA_ID and
some free-text. LOCA_ID is a field typically found in UK AGS format
geotechnical log files and is just used here as an example of a field.
The fields available will depend on the format and nature of your own
borehole data.

![](media\image212.png){width="3.9791666666666665in"
height="2.1145833333333335in"}

And this is how the value appears in the template once applied.

![](media\image213.png){width="4.364583333333333in"
height="0.8229166666666666in"}

You can also add values from any of the data tables attached to the
borehole dataset using the Table Lookup button.

![](media\image214.png){width="3.8958333333333335in"
height="1.9270833333333333in"}

Drill down to extract the desired field. In the example below, the
project name field is being added from an AGS 4 dataset. In the case of
AGS this is the PROJ_NAME field within the attached PROJ table. The
Label field is not used in this feature.

![](media\image215.png){width="3.5in" height="1.3020833333333333in"}

If you select a field from a table that has multiple rows, the value
will be assigned according to the following policy;

1.  If the data table contains a borehole ID field, the first row with a
    matching ID will be used as the basis of the query,

2.  If the data table has no ID field, the first row in the table will
    be used as the basis of the query.

You can add/remove columns and rows to the header table using
right-click.

![](media\image216.png){width="4.730435258092738in"
height="1.7120439632545932in"}

Here is an example of a header table with a number of rows and columns
added and some field defined.

![](media\image217.png){width="6.268055555555556in"
height="0.9076388888888889in"}

To add a company logo to the top left hand corner of the template, right
click in that area and the following dialogue will allow you to choose a
logo image file.

![](media\image218.PNG){width="3.1150185914260717in"
height="1.4897911198600176in"}

Once you have chosen your logo, it will be available to all templates,
as the image file will reside in the Groundhog home on your computer.
You can change the logo, for all templates by selecting "Choose Logo"
again or you can hide
it.![](media\image219.PNG){width="2.5628576115485564in"
height="1.5210454943132108in"}

If hidden it can be un-hidden, by selecting "Show Logo"

![](media\image220.png){width="2.4375in" height="1.5in"}

#### Columns

The columns area is where the borehole log data is placed. It is
arranged as one or more data columns. Each column can have a different
graphical type and pull on different data fields within the borehole.
Each column is divided into a header and a log column.

Start by adding a new column to the blank template. Hover over the
header portion of a pre-existing log column and \<Insert Column on
\[Left or Right\]\>.

![](media\image221.png){width="5.375in" height="2.8333333333333335in"}

A prompt asks you to choose a graphical column type. Note that not all
column types will work with all types of borehole or data field. Here we
are adding a text column.

![](media\image222.png){width="3.3958333333333335in"
height="2.7083333333333335in"}

The available column types are;

-   **Borehole Installation** -- can be used to show backfill and pipe
    installation details.

-   **Curve** -- plots values at a depth in the form of a curve or a
    series of dots, for example a Gamma Log or CPT log.

-   **Depth Scale** -- a vertical depth scale in metres or feet.

-   **Interval (Geology Log)** -- used to plot geology intervals in an
    interpreted log.

-   **Marker Depths** -- plots depth boxes for intervals within the log.

-   **Samples** -- displays depths and types of samples.

-   **Test Results** -- displays any test result data as a label,
    including in-situ and laboratory test values. Can also be used to
    display water levels.

-   **Text** -- shows any text-based data down the log, for example a
    detailed stratum description.

-   **Water Strikes** -- shows strike and rest levels as symbols.

When a new column is inserted into the template typically you will be
prompted to choose the field containing the data to use for that column.
The exception is the depth scale, which is not based on a data field.
The prompt usually takes the form of a drill-down. Select the folder or
table, and then the field containing the data. Below are some examples
based on an imported AGS 4 file;

![](media\image223.png){width="3.5in" height="1.3020833333333333in"}

GEOL_LEG field from the geology log (geology intervals folder)

![](media\image224.png){width="3.5in" height="1.3020833333333333in"}

ISPT_MAIN data field in the ISPT test result table.

Some column types show more than one data field simultaneously. For
example the borehole installation column, which can show backfill and
pipe data together. In such cases the mapping dialog will contain
multiple tabs allowing the necessary field to be mapped.

![](media\image225.png){width="3.75in" height="1.9166666666666667in"}

Once the data field mapping is completed, the column will be added to
the template. You can access and edit the settings after the column is
added using \<Right-Click\> \<Edit TYPE Column\> \<Column Settings\> in
the header of each column, for example;

![](media\image226.png){width="4.635416666666667in"
height="2.6041666666666665in"}

![](media\image227.png){width="5.177083333333333in" height="2.65625in"}

The settings dialog will look slightly different, depending on the type
of the column. Often, the settings dialogs have additional settings that
are not accessible when you first add the column, so they are worth
exploring.

To remove a column from the template \<Right-Click\> on the column
header and select \<Delete Column\>

![](media\image228.png){width="4.0625in" height="2.5625in"}

Here are typical examples of each of the available column types, shown
here using an example AGS 4 format borehole data file and a LAS format
geophysical file.

**Borehole Installation Column**

![](media\image229.png){width="0.6534842519685039in"
height="3.183999343832021in"}

Example using BKFL.BKFL_LEG for the backfill mapping and PIPE.PIPE_TYPE
for the pipe installation mapping.

**Curve Column**

![](media\image230.png){width="2.0240004374453195in"
height="2.6270417760279967in"}

Example using GR field from an imported LAS Curve Data table.

**Depth Scale Log**

![](media\image231.png){width="0.9522801837270342in"
height="2.4879997812773404in"}

Showing feet and metres scales.

**Interval (Geology Log) Column**

![](media\image232.png){width="1.09375in" height="2.7708333333333335in"}

Example using GEOL.GEOL_LEG field.

**Marker Depths Column**

![](media\image233.png){width="1.4270833333333333in"
height="2.7604166666666665in"}

Example using GEOL.GEOL_LEG field, shown against a corresponding
interval column.

**Samples Column**

![](media\image234.png){width="2.3333333333333335in"
height="2.1354166666666665in"}

Example using SAMP.SAMP_TYPE field.

**Test Results Column**

![](media\image235.png){width="1.3125in" height="2.8645833333333335in"}

Example using ISPT.ISPT_REP field.

**Text Column**

![](media\image236.png){width="3.0520833333333335in"
height="2.8854166666666665in"}

Example using GEOL.GEOL_DESC field.

**Water Strikes Column**

![](media\image237.png){width="0.8958333333333334in" height="2.1875in"}

Example using dual mapping of WSTD.WSTD_DPTH and WSTD.WSTD_POST for
strike and rest level.

Here is an example with several different column types added to a
template based on AGS data.

![](media\image238.PNG){width="4.28125in" height="5.050704286964129in"}

**IMPORTANT:** As you build up your template it is a good idea to save
it regularly. Templates are held in the global workspace of Groundhog so
that they can be used across all of your projects, so they need to be
saved separately.

#### Footer

Having added some columns, let's set up the template footer.

![](media\image239.png){width="3.9304352580927384in"
height="1.734704724409449in"}

![](media\image240.png){width="2.757260498687664in"
height="3.321738845144357in"}

#### Page Setup

And finally, let's set the page size to A4, set the number of metres to
display per-page, and fit the template to the page.

![](media\image241.png){width="4.052083333333333in"
height="1.1458333333333333in"}

![](media\image238.PNG){width="3.6181813210848643in"
height="4.2660979877515315in"}

\<Right-Click\> anywhere \<Fit To Page\>

![](media\image242.png){width="3.4375in" height="1.7708333333333333in"}

![](media\image243.png){width="6.268055555555556in"
height="5.007638888888889in"}

Here is an example of a wireline log style template.

![](media\image244.png){width="3.0561417322834648in"
height="4.043478783902012in"}

Note that the design template can also be used in the cross-section
view.

![](media\image245.png){width="4.321738845144357in"
height="2.414160104986877in"}

### Viewing AGS Boreholes

If you right click on a borehole in the data tree which is an AGS
borehole and select \<Log View\>, you will have the option to open the
log view using a standard AGS template:

![](media\image246.PNG){width="6.268055555555556in"
height="1.132638888888889in"}

Selecting this option will automatically open the log view using the
standard AGS template which is compatible with the data. Four templates
are currently supplied by BGS and these reside within the Groundhog home
workspace. It is possible to edit these, but it should be noted that,
once saved this is a permanent change and using the standard AGS
template option to display AGS boreholes in the future will always use
the revised template.

### Exporting Logs as PDF

You can export individual logs to a PDF file using this button in the
log window toolbar.

![](media\image247.png){width="3.9270833333333335in"
height="1.7083333333333333in"}

If you have Groundhog Professional you can also batch-export to PDF from
the data folder in the tree.

![](media\image248.png){width="6.268055555555556in"
height="2.111111111111111in"}

You will be prompted to select export options, including choosing a
specific template. You can also have the reports exported as individual
PDFs (one per-borehole) or as a single document with all boreholes
included. You can also exclude specific boreholes from the export.

If the boreholes are from AGS files and you leave the "Use Preferred
Template" check on then the output will default to using the standard
AGS log templates that ship with Groundhog.

![](media\image249.png){width="6.268055555555556in"
height="6.402083333333334in"}

*Professional*

### Exporting Boreholes as CSV

You can export boreholes and their associated data tables to a series of
CSV files. This can be useful if you need to convert AGS data to a
common spreadsheet format, for example.

![](media\image250.png){width="6.268055555555556in"
height="2.3333333333333335in"}

You will be prompted to choose an output folder. The export will produce
one CSV per-data-table, plus one for the geology interval logs, if there
are any.

*Professional*

## Editing Borehole Data

You can enter and edit borehole data directly within Groundhog. To
demonstrate this, we will create a blank borehole dataset to work into.

From the object tree Location Layers folder \<right-click\> \<New
Layer\>.

![](media\image251.png){width="4.229166666666667in"
height="1.4479166666666667in"}

![](media\image252.png){width="2.173912948381452in"
height="1.0046117672790902in"}

![](media\image253.png){width="2.173611111111111in"
height="0.9031200787401574in"}

Or from the layers panel of a map
window.![](media\image254.png){width="4.730435258092738in"
height="1.6692257217847768in"}

![](media\image252.png){width="2.173611111111111in"
height="1.004471784776903in"}

If the new layer is not already visible in a map window, add it.

![](media\image255.png){width="3.3125in" height="1.4583333333333333in"}

![](media\image256.png){width="3.095651793525809in"
height="1.7141808836395451in"}

Make the layer active in the map by clicking on it in the layers panel
(turns orange when active).

![](media\image257.png){width="2.826087051618548in"
height="1.1321117672790901in"}

In the drawing palette, pick up the borehole placement tool (turns
orange when selected).

![](media\image258.png){width="3.0in" height="1.4742016622922134in"}

Single-click in the map to place new borehole object. Borehole collar
dialog appears. Enter a name for the new borehole, adjust X,Y as desired
to set a specific location. Also, if you have a suitable DEM/DTM loaded
and set as the surface layer in the session, click the \<Set from
Surface Layer\> button for the start height (ground level) field to set
an elevation value for the top of the borehole, or type one manually if
you have a more accurate one.

![](media\image259.png){width="4.304348206474191in"
height="1.982711067366579in"}

Borehole appears in the map. Add as many boreholes as you like and then
de-activate the borehole layer in the map.

![](media\image260.png){width="4.791666666666667in" height="2.09375in"}

Hover the mouse over a borehole location and select \<right-click\>
\<New Geology Log\>

![](media\image261.png){width="2.5217388451443568in"
height="1.672836832895888in"}

When prompted for a name for the log, just enter "1".

![](media\image262.png){width="2.208695319335083in"
height="1.0206846019247595in"}

This creates a geology interval log with 1m interval of SAND added to
initialize the data structure. The log turns blue in the map to indicate
the presence of a geology log.

![](media\image263.png){width="2.3958333333333335in"
height="1.6041666666666667in"}

In the object tree, note the options available on the interval of SAND.

![](media\image264.png){width="4.260416666666667in" height="2.15625in"}

Edit the interval using the dialog. Here we change the depth to the base
of the first interval to be 7.4m (all values are depths, not elevations)
and change its geology code to PEAT by typing it in.

![](media\image265.png){width="3.7304352580927382in"
height="2.8522287839020124in"}

Use the \<Add/Delete Attribute\> button to set new attribution on the
interval. Here we add a field for a description.

![](media\image266.png){width="2.643478783902012in"
height="1.198377077865267in"}

![](media\image267.png){width="1.915229658792651in"
height="2.5391305774278217in"}

![](media\image268.png){width="2.234782370953631in"
height="1.0327405949256343in"}

![](media\image269.png){width="2.0394805336832897in"
height="2.678261154855643in"}

Type a value for the new field into the new entry row that has appeared.

![](media\image270.png){width="3.4482141294838144in"
height="2.878261154855643in"}

Add new geology intervals in the same way using the interval editing
dialog.

![](media\image271.png){width="3.191304680664917in"
height="1.8390573053368329in"}

![](media\image272.png){width="3.678261154855643in"
height="3.042788713910761in"}

![](media\image273.png){width="3.3645833333333335in"
height="2.1770833333333335in"}

# Drawing Points, Shapes & Annotations

This section provides details on how to digitize into point and shape
layers, including borehole-type point layers. It also covers how to add
annotations such as labels, callouts, arrows and graphical icons. It
does not include how to draw into the Geology layer of a cross-section
-- for that please refer to **Drawing Cross-Sections**.

![](media\image274.jpeg){width="6.268055555555556in"
height="4.701388888888889in"}

*Photo by Plush Design Studio on Unsplash*

## Creating New Layers

You can use Groundhog to create and draw point and shape layers and to
create annotation layers containing labels, callouts, arrows and icon
graphics. You can also import GIS shapefiles as these types of layers --
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

Point layers are map layers only (they can't be drawn into
cross-sections). Create a new point layer from the object tree by
right-clicking on the Location Layers folder, or from the map layer
control panel by right-clicking in a blank whitespace area of the panel.

![](media\image275.png){width="2.4166666666666665in"
height="1.1770833333333333in"}

Or...

![](media\image276.png){width="4.886956474190726in"
height="1.6876399825021873in"}

Enter a name for the layer.

![](media\image277.png){width="2.3739129483814523in"
height="1.0970352143482065in"}

Make the layer active in the map by clicking on it in the layer control
panel. It will turn orange when active.

![](media\image278.png){width="4.478261154855643in"
height="1.5463396762904638in"}

The drawing tool for points appears as a floating drawing tools palette.
You can drag the palette around using the green bar at the top.

![](media\image279.png){width="4.669564741907261in"
height="2.2183792650918637in"}

To draw points, pick up the point drawing tool from the palette by
clicking on it. When it is active it will turn orange.

![](media\image280.png){width="2.6979166666666665in" height="1.3125in"}

Single-click in the map to place points at the desired locations. When
you are finished, de-activate the point layer in the map.

![](media\image281.png){width="4.03125in" height="2.53125in"}

![](media\image282.png){width="3.84375in" height="2.2395833333333335in"}

Set the colour of the points using the point layer settings in the layer
control panel.

![](media\image283.png){width="5.617391732283465in"
height="0.8171544181977253in"}

![](media\image284.png){width="2.6354166666666665in"
height="1.2083333333333333in"}

![](media\image285.png){width="3.7173731408573927in"
height="2.3739129483814523in"}

![](media\image286.png){width="3.4583333333333335in"
height="2.0833333333333335in"}

#### Attributing Points

You can set name-value pair attributes on any point objects. With the
layer active in the map, hover the mouse over a point and use
\<right-click\> \<Attribute Location\>.

![](media\image287.PNG){width="2.0106977252843397in"
height="1.6043908573928258in"}

Specify an attribute name and value.

![](media\image288.PNG){width="5.193532370953631in"
height="1.146920384951881in"}

The dictionary on button on the right allows you to select from a list
of commonly used attribute names.

You can then set the field as the label for the points using the layer
settings.

#### Add Dip Measurement

Presents a dialogue box requesting Dip, Azimuth, Radius and Geology.

Radius is the distance in metres that the point affects and setting this
measurement varies the size of the dip measurement

![](media\image289.PNG){width="0.5104877515310586in"
height="0.4271434820647419in"}
![](media\image290.PNG){width="2.4795122484689416in"
height="2.135715223097113in"}

Geology is optional and is available as a shortcut way of entering this
attribute.

![](media\image283.png){width="5.617391732283465in"
height="0.8171544181977253in"}

![](media\image291.png){width="2.678261154855643in"
height="1.1072670603674541in"}

![](media\image292.png){width="2.3826082677165354in"
height="1.756040026246719in"}

### Creating & Editing Shape Layers

Shape layers are map or cross-section layers (they can also be drawn
into cross-sections). Create a new shape layer from the object tree by
right-clicking on the Shape Layers folder, or from the map layer control
panel by right-clicking in a blank whitespace area of the panel.

![](media\image293.png){width="3.4791666666666665in" height="1.5in"}

Or...

![](media\image294.png){width="4.704348206474191in"
height="1.8982458442694663in"}

Enter a name for the layer.

![](media\image295.png){width="2.3739129483814523in"
height="1.0970352143482065in"}

Make the layer active in the map by clicking on it in the layer control
panel. It will turn orange when active.

![](media\image296.png){width="3.2in" height="1.3665780839895012in"}

The drawing tool for points appears as a floating drawing tools palette.
You can drag the palette around using the green bar at the top.

![](media\image297.png){width="4.947825896762905in"
height="2.3703083989501312in"}

The drawing palette contains a number of drawing tools. Hover over each
tool to see a short description.

![](media\image298.png){width="2.2916666666666665in" height="1.0in"}

The following tools are available,

-   **Polyline** -- a digitizing tool, single-click to place vertices,
    double-click to finish,

-   **Pen** -- hodl the mouse down and drag to create a free-form line

-   **Polygon** -- same as the polyline tool but snaps the two ends of
    the line to form a polygon

-   **Rectangle** -- click and drag to create a rectangle

-   **Ellipse** -- click and drag to create an ellipse

Single-click on a tool to select it. When a tool is active it will turn
orange. In the following example we are using the polyline tool to
digitize lines.

![](media\image299.png){width="2.21875in" height="0.9479166666666666in"}

![](media\image300.png){width="4.148780621172353in"
height="3.078261154855643in"}

If you want to convert a polyline to a polygon, drag the last vertex
towards the first vertex until it "snaps". Alternatively, on the line
itself, \<right-click\> \<Male Polygon\>.

When a line is active its vertices show as green dots and the line can
be edited;

-   Move vertices by dragging them,

-   Delete vertices by double-clicking on top of them,

-   Add new vertices by double clicking on a line segment.

![](media\image301.png){width="4.260869422572179in"
height="3.3132053805774277in"}

When editing a line, labels appear showing the angles (in degrees)
between adjacent segments.

![](media\image302.png){width="3.034782370953631in"
height="1.8057764654418198in"}

#### Attributing & Tagging Shapes

You can set name-value pair attributes on any shape objects. With the
layer active in the map, hover the mouse over a line and use
\<right-click\> \<Attribute Shape\>.

![](media\image303.png){width="4.191304680664917in"
height="2.6626126421697287in"}

Specify an attribute name and value. In this example we are setting a Z
value so that the line could represent a structure contour, for example.

![](media\image304.PNG){width="5.166665573053368in"
height="1.172438757655293in"}

You can then set the field as the label for the shapes using the layer
settings and also set colour and line thickness.

![](media\image305.png){width="5.364583333333333in"
height="0.7291666666666666in"}

![](media\image306.png){width="1.6458333333333333in" height="1.84375in"}

![](media\image307.png){width="2.112311898512686in"
height="2.9739129483814524in"}

You can tag shapes with a geology code automatically as you draw just by
setting an active drawing code other than "Shape".

![](media\image308.png){width="2.9826082677165355in"
height="1.1194367891513561in"}

![](media\image309.png){width="3.0260870516185476in"
height="1.2072156605424322in"}

With a geology drawing code set, draw the shape and it will be
attributed with a field called "GEOLOGY" containing the drawing code
that was active at the time.

![](media\image310.png){width="2.9270833333333335in"
height="2.6458333333333335in"}

You can also tag a shape with certain pre-set special attribute value.
These are accessible by hover on the line and using \<right-click\>

![](media\image311.png){width="4.226087051618547in"
height="3.0352307524059494in"}

![](media\image312.png){width="2.75in" height="1.2708333333333333in"}

These tags cause the objects to act in certain special ways. For
example, tagging a site boundary will style the shape as a bold, red
line.

![](media\image313.png){width="3.078261154855643in"
height="2.363109142607174in"}

#### Polygons With Holes

You can draw polygons with holes and Groundhog can automatically convert
them into coverage envelopes. First, draw a series of polygons into a
shape layer. Make sure each shape is a polygon either by dragging the
last vertex towards the first to snap together, or via \<Right-Click\>
\<Make Polygon\> on each line.

![](media\image314.png){width="6.268055555555556in"
height="4.883333333333334in"}

Next, in the data tree, use \<Right-Click\> \<Tools\> \<Build
Multi-Polygons\> on the shape layer.

![](media\image315.png){width="6.268055555555556in"
height="3.0965277777777778in"}

![](media\image316.png){width="6.268055555555556in" height="4.625in"}

Groundhog will auto-detect the holes. This function operates to any
level of nested detail. For very complex shape layers the auto-detection
may take several moments to complete.

![](media\image317.png){width="3.0240004374453195in"
height="2.0597779965004372in"}

### Creating & Editing Annotation Layers

*Professional*

Annotation layers let you add a descriptive and symbolic layer to your
projects, both in map and cross-section views. You can only create or
edit annotation layers using Groundhog Professional, but you can view
annotations in existing projects using Community.

Annotations can take the form of;

-   Labels -- styled labels with boxes,

-   Callouts -- like labels, but with a pointer,

-   Arrows -- styled arrow shapes,

-   Graphics -- icon pictures that can be placed to represent key
    components of a conceptual model or interpretation.

Use \<right-click\> \<New Annotation Layer\> in the layer control panel
of either a map window or a cross-section window. In the following
example we are working into a cross-section.

![](media\image318.png){width="5.156521216097988in"
height="1.9298392388451444in"}

Enter a name. Note that you can have as many annotation layers as you
like.

![](media\image319.png){width="2.2521741032370954in"
height="1.040777559055118in"}

Make the layer active so that we can draw into it. When active it will
display in orange.

![](media\image320.png){width="3.234782370953631in"
height="1.2479363517060367in"}

When the layer is active the floating drawing tool palette will appear
with a series of annotation-specific tools available.

![](media\image321.png){width="2.3125in" height="1.0416666666666667in"}

  ![](media\image322.png){width="0.3229166666666667in" height="0.34375in"}              Label     Place a label into the layer
  ------------------------------------------------------------------------------------- --------- -------------------------------------
  ![](media\image323.png){width="0.3333333333333333in" height="0.3020833333333333in"}   Callout   Place a callout into the layer
  ![](media\image324.png){width="0.3541666666666667in" height="0.3333333333333333in"}   Graphic   Place a graphic into the layer
  ![](media\image325.png){width="0.3645833333333333in" height="0.34375in"}              Arrow     Place an arrow shape into the layer

#### Labels

Select a tool to start drawing. In this case, the labels tool. When the
tool is active is will highlight in orange and it will stay active for
as long as you want to keep placing annotations of that type. Click the
button again to switch the tool off.

![](media\image326.png){width="2.0833333333333335in"
height="0.9895833333333334in"}

Single-click in the graphics panel (map or cross-section) to place the
annotation object. Continue clicking to add more.

![](media\image327.png){width="4.1043482064741905in"
height="1.7784295713035871in"}

With the annotations layer active, each annotation will have green
control nodes visible. Drag these to move the annotations around.

\<Right-Click\> on the green control nodes shows a context menu. In the
case of labels we can use this to edit the label text.

![](media\image328.png){width="4.302083333333333in"
height="1.7916666666666667in"}

![](media\image329.png){width="2.65625in" height="1.3854166666666667in"}

When the annotations layer is active the labels appear orange to show
they are in the active layer. De-activate the annotations layer to see
them in their standard colour.

![](media\image330.png){width="4.489583333333333in" height="1.84375in"}

#### Callouts

Activate the callout tool and place some callouts.

![](media\image331.png){width="2.3229166666666665in" height="1.0in"}

Note that callouts are like labels, but with a tail.

![](media\image332.png){width="2.4166666666666665in"
height="1.4166666666666667in"}

Move the label portion of the callout using the green control node
inside the label.

![](media\image333.png){width="3.5in" height="1.4791666666666667in"}

Move the tail by dragging the green control node at the end of the tail.

![](media\image334.png){width="4.3125in" height="1.9895833333333333in"}

Right-click on the control node at the end of the tail to access the
label editing dialog.

![](media\image335.png){width="2.741071741032371in"
height="2.034783464566929in"}

![](media\image336.png){width="3.0452187226596674in"
height="1.7913046806649169in"}

#### Arrows

Activate the arrow tool in the drawing palette and single-click in the
panel to place arrows.

![](media\image337.png){width="2.2291666666666665in"
height="0.9895833333333334in"}

![](media\image338.png){width="6.03125in" height="1.8645833333333333in"}

Drag the green nodes at either end of the arrows to size and position
them.

![](media\image339.png){width="4.114583333333333in"
height="2.3229166666666665in"}

\<Right-Click\> on the first node of the arrow to access editing and
ordering option.

![](media\image340.PNG){width="3.06292760279965in"
height="1.5418821084864391in"}

Use the dialog accessible under \<Edit Arrow Text/Settings\> option to
set the appearance and label (if one is needed) of each arrow.

![](media\image341.PNG){width="6.268055555555556in"
height="1.3465277777777778in"}

You can also set global setting for the entire layer via the settings
button of the annotations layer.

![](media\image342.png){width="5.90625in" height="1.0625in"}

![](media\image343.PNG){width="4.761805555555555in"
height="4.981735564304462in"}

#### Graphics (Pictures)

You can add graphical pictures into an annotation layer in both map and
cross-section. Groundhog comes pre-loaded with a suite of pictures that
you can use.

Select the graphic tool from the drawing palette.

![](media\image344.png){width="2.2395833333333335in"
height="1.0104166666666667in"}

Single-click in the graphics panel to place pictures. You will be
prompted to select the graphic picture to use. Click on the picture you
want and click \<OK\>.

![cid:56bf7827-d83e-41d9-a893-ba263016cf41](media\image345.jpeg){width="1.7319444444444445in"
height="2.886111111111111in"}

Use the green and white control nodes to move and re-size the picture,
respectively.

![](media\image346.png){width="1.8020833333333333in"
height="1.7395833333333333in"}

Annotation layers have two zoom modes. By default, the pictures will
re-scale as you zoom in and out (dynamic re-sizing).

![](media\image347.png){width="2.674796587926509in"
height="2.0239949693788275in"}

![](media\image348.png){width="4.9375in" height="1.4479166666666667in"}

Alternatively, you can switch to non dynamic re-sizing via the layer
settings dialog.

![](media\image349.png){width="5.0625in" height="0.90625in"}

![](media\image350.png){width="3.805049212598425in"
height="3.8211384514435696in"}

Add as many annotations as you wish. Here are some examples of the
graphics supported within Groundhog. You are free to use these in
outputs/reports, including for commercial projects.

![](media\image351.png){width="6.268055555555556in"
height="2.0027777777777778in"}

# Drawing Cross-Sections

This section provides details on how to construct and digitise
spatially-referenced geological cross-sections using Groundhog.

![](media\image352.jpeg){width="6.268055555555556in"
height="4.183333333333334in"}

*Photo by Ivars Krutainis on Unsplash*

## Creating the Cross-Section Alignment

The first step in creating a cross-section is to construct its alignment
on the map.

### Creating Cross-Sections Without an Alignment

If you do not care about the map alignment and you just want to draw a
cross-section of a specific length in isolation then you can use
\<right-click\> \<Tools\> \<Create New Cross-Section\> in the object
tree.

![](media\image353.png){width="5.1875in" height="1.4166666666666667in"}

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

![](media\image354.png){width="2.3208956692913385in"
height="0.9200688976377953in"}

In the map window, zoom in to the approximate desired location of the
cross-section, making sure that the extent of the map covers the entire
cross-section alignment.

If it isn't already there, add the default ***Cross-Sections*** layer to
the window.

![](media\image355.png){width="2.2761198600174977in"
height="1.1026181102362205in"}

![](media\image356.png){width="2.6268657042869643in"
height="1.3845308398950131in"}

You are going to be drawing into the Cross-Sections layer, so make it
active by single-clicking on it in the layer control panel. When it's
active it will highlight in orange colour.

![](media\image357.png){width="2.8358213035870516in"
height="1.2196281714785653in"}

When the layer becomes active a drawing tool palette will appear in the
map panel. There is only one tool available in cross-section layer mode,
which is polyline. Pick this tool up by single-clicking on its icon in
the palette. When it is active the tool will highlight in orange.

![](media\image358.png){width="2.8805971128608925in"
height="1.6959733158355206in"}

Start drawing the alignment. **Single-click to add positions** to the
alignment. **Double-click at the last vertex** of the alignment to
complete the operation. Cross-sections can have as many inflections as
you like, or they can be just straight by only placing two vertices into
the polyline.

![](media\image359.png){width="4.313432852143482in"
height="1.7213593613298337in"}

Enter a name for the cross-section. If you wish to abandon the line you
have drawn, simply cancel the name input dialog.

![](media\image360.png){width="2.75in" height="1.2708333333333333in"}

Continue drawing polylines to create cross-section alignments. When you
are done drawing, make sure to de-activate the polyline tool by clicking
on it so that it is no longer highlighted in orange.

![](media\image361.png){width="2.2708333333333335in" height="1.0in"}

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

![](media\image362.png){width="4.283581583552056in"
height="2.5437620297462815in"}

### Modifying the Alignment

Once a cross-section alignment has been drawn in the map you can still
modify it. First, make sure the **Cross-Sections** layer is visible and
active in the map.

![](media\image357.png){width="2.8358213035870516in"
height="1.2196281714785653in"}

#### Insert New Position

Right-click on the segment of the polyline where you wish to insert a
new map position and choose \<Insert New Position Into Cross-Section\>.

![](media\image363.png){width="6.268055555555556in"
height="2.345138888888889in"}

![](media\image364.png){width="2.7910444006999127in"
height="0.9491163604549432in"}

Click on the desired location in the map to insert it into that segment
of the line.

![](media\image365.png){width="4.54477580927384in"
height="2.110757874015748in"}

#### Extending a Cross-Section

You can extend a cross-section at either end. Right-click on the segment
at the desired end of the cross-section. If the cross-section only has
one segment (i.e. it is a straight section), make sure to right click
closer to the end of the line that you wish to extent. Choose \<Extend
Cross-Section\>. The examples below show extending the cross-sections to
the East (right).

![](media\image366.png){width="4.164178696412948in"
height="1.8389555993000875in"}

![](media\image367.png){width="4.3521128608923885in"
height="2.283581583552056in"}

![](media\image368.png){width="4.417910104986877in"
height="2.114488188976378in"}

![](media\image369.png){width="4.283581583552056in"
height="2.336369203849519in"}

#### Removing a Position From the Alignment

To remove a specific position from the alignment polyline, right click
on the desired position (one of the section ends or an inflection point)
and choose \<Remove Position From Cross-Section\>.

![](media\image370.png){width="4.111940069991251in"
height="2.2987871828521436in"}

![](media\image371.png){width="4.253731408573929in"
height="2.249397419072616in"}

**IMPORTANT:** Please note that modifying cross-section alignments may
have adverse effects on any correlated geology linework or other
geometry objects that have already been drawn into the cross-section.

## Viewing and Editing the Cross-Section

To open a cross-section in a cross-section window, (1) double-click on
it in the object tree or (2) use \<right-click\> \<View Cross-Section\>
in the tree or (3) \<right-click\> on the alignment in the map and
choose \<View Cross-Section\>. The cross-section window opens in a new
tab.

![](media\image372.png){width="4.06716426071741in"
height="1.52665135608049in"}

![](media\image373.png){width="6.097014435695538in"
height="4.334648950131234in"}

Zoom to full extent to centre the data in the panel.

### Topographic Profile

If a default surface layer (topography grid such as a DEM/DTM) is loaded
and configured in the session then a topographic profile will be
automatically generated and added as a ***Terrain Profile*** layer.

![](media\image374.png){width="6.268055555555556in"
height="1.4131944444444444in"}

If there is no grid available for this a flat profile will be generated.
To change or update the topographic profile, open the settings for the
***Terrain Profile*** layer.

![](media\image375.png){width="4.059701443569554in"
height="2.116534339457568in"}

Choose which grid layer to use for the profile generation and set a
level of detail. If you want to sample the grid at full resolution,
select "FULL" in this list.

![](media\image376.png){width="2.8958333333333335in" height="1.625in"}

Click \<Apply\> to make the changes. The profile will be updated. When
using "FULL" resolution on fine grids the update may take a few moments
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

![](media\image377.png){width="1.2686570428696413in"
height="1.2686570428696413in"}

To begin with you may find that your boreholes appear as empty boxes
with odd labels.

![](media\image378.png){width="6.268055555555556in"
height="2.254861111111111in"}

This usually happens when the active log template is unsuitable for the
data contained within the boreholes themselves. Change to a more
suitable template using either the global template settings in the main
status bar of Groundhog.

![](media\image379.png){width="4.354166666666667in" height="2.28125in"}

Or, access the settings for the Borehole layer in the section window and
choose a more appropriate template.

![](media\image380.png){width="3.5820898950131235in"
height="1.1890441819772528in"}

In the settings dialog choose a suitable template and also specify the
width (in metres) of the log sticks until the logs appear as you want
them.

![](media\image381.png){width="2.8208956692913385in"
height="2.4569094488188976in"}

![](media\image382.png){width="6.268055555555556in"
height="2.2805555555555554in"}

If you don't have a suitable log template then you can design one. For
more details please refer to the **Working With Borehole Logs** chapter.
You can design templates to show different types of borehole data such
as geotechnical test data and geophysical logs.

### Buffering Boreholes Into a Cross-Section

If you have not drawn your alignment directly through the boreholes,
with the ***Cross-Sections*** layer active in the map, you can use a
buffering operation to project them into the alignment using
\<right-click\> \<Project Nearby Boreholes Into Cross-Section\>. Enter a
buffer distance. The projection is performed orthogonal to the
alignment. To remove the buffered boreholes, use the **Borehole** -\>
**Settings** dialog within the cross section window and change **Project
Boreholes** distance to 0 (zero).

![](media\image383.png){width="6.268055555555556in"
height="2.3819444444444446in"}

### Registering Images in Cross-Section

You can add images to a cross-sections as layers. This can be useful for
showing geophysical data, for example. First, load the desired image
into the project via \<Main Menu\> \<Import\> \<Image\>.

![](media\image384.png){width="4.4375in" height="1.5208333333333333in"}

Position the cross-section panel to the approximate extent where you
want the image to display. Add the image as a layer to the cross-section
window.

![](media\image385.png){width="3.6173917322834646in"
height="1.6665277777777778in"}

Select the image you wish to add.

![](media\image386.png){width="4.4086953193350835in"
height="2.0032064741907263in"}

Image will appear, filling the visible extent of the graphics panel.

![](media\image387.png){width="6.268055555555556in"
height="2.660416666666667in"}

Click on the image layer to make it active. Note that square, blue
control handles appear in the top-left and bottom-right of the image.

![](media\image388.png){width="6.268055555555556in"
height="2.3958333333333335in"}

Use the top-left handle to move the image around and use the
bottom-right handle to re-size the image. Whenever possible, try to use
an image that has scale-bars included so that you can compare the values
to the mouse cursor position in order to fine-tune the image
registration.

![](media\image389.png){width="5.078261154855643in"
height="2.4654265091863516in"}

### Drawing Geology

Geological interpretation is drawn into the ***Geology*** layer. The
***Geology*** layer is added to cross-section windows by default, but if
you can't see it then you can re-add it.

![](media\image390.png){width="2.9328357392825897in"
height="1.4529647856517935in"}

![](media\image391.png){width="4.761194225721785in"
height="2.1205402449693787in"}

Make the Geology layer the active layer by clicking on it. It will turn
orange when it is active (to de-activate it, click on it again).

![](media\image392.png){width="2.5223884514435695in"
height="1.2199792213473315in"}

When the Geology layer is active the drawing tool palette will appear in
the graphics panel, with the polyline and pen tools available.

![](media\image393.png){width="3.186567147856518in"
height="1.7743383639545056in"}

Before you start to draw geology you need to select a drawing code. The
default drawing code is a generic code labelled "Shape". Instead, you
need to select a geology code. Click on the drawing code selector button
and pick a geology code from the list.

![](media\image394.png){width="2.6194028871391075in"
height="1.3533584864391952in"}

![](media\image395.png){width="4.388059930008749in"
height="2.656365923009624in"}

Note that the drawing code you select is then set as the active code and
the button changes to display that code. In the above example, PEAT has
been selected.

#### Polyline Tool

The polyline tool allows for accurate digitizing by placing each vertex
individually. Click the button in the drawing tools palette to activate
the polyline tool. When it is active it will turn orange.

![](media\image396.png){width="2.25in" height="1.0in"}

Single-click in the section to place vertices. Double-click to finish
the line. Switch the polyline tool off when you are done drawing by
clicking on it again in the palette.

![](media\image397.png){width="6.268055555555556in"
height="2.595833333333333in"}

#### Pen Tool

The pen tool allows for rapid, fluid drawing. Click the button in the
drawing tools palette to activate the pen tool. When it is active it
will turn orange.

![](media\image398.png){width="2.1666666666666665in"
height="0.9583333333333334in"}

Click and hold at the start of the line and drag the mouse to draw.
Release the mouse button to stop drawing the line. When you are done
drawing, switch off the pen tool by clicking on it again in the palette.

![](media\image399.png){width="6.268055555555556in"
height="2.4805555555555556in"}

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

![](media\image400.png){width="6.268055555555556in"
height="2.1104166666666666in"}

If you snap the end of a line to the terrain profile, you will be
prompted like this. Click \<No\> if you just want to keep a static
profile, or \<Yes\> to sample more accurate Z values from the terrain
grid at the snap location.

![](media\image401.png){width="3.656715879265092in"
height="1.8364840332458443in"}

A special icon will appear at any snap positions.

![](media\image402.png){width="1.2462685914260718in"
height="0.7084055118110236in"}

When both ends of a geology correlation line are snapped to something,
the polygon builder will create a filled polygon for the deposit.

![](media\image403.png){width="6.268055555555556in"
height="1.1555555555555554in"}

Click away from the active line to de-activate it. Continue drawing and
snapping to build up the cross-section. Remember to select the
appropriate drawing code before drawing each line. If you forget, make
the line active by clicking on it then use \<right-click\> \<Change
Geology Code\> and type in the new geology code.

![](media\image404.png){width="4.191304680664917in"
height="1.5614665354330708in"}

![](media\image405.png){width="6.268055555555556in" height="1.83125in"}

![](media\image406.png){width="6.268055555555556in" height="2.3375in"}

Don't worry if some existing polygons fail to render as you continue
drawing. They should resolve themselves as soon as you snap the line you
are working on. For example --

![](media\image407.png){width="6.268055555555556in"
height="2.3402777777777777in"}

![](media\image408.png){width="6.268055555555556in"
height="2.1659722222222224in"}

Moving any snapped positions will cause an edit to both correlation
lines (except at the topographic profile).

![](media\image409.png){width="3.0746270778652667in"
height="2.0790977690288712in"}

If you need to un-snap a snap location, hold the CTRL key as you drag
the node away from the snap location.

![](media\image410.png){width="3.099523184601925in"
height="1.6417902449693789in"}

Create a correlation line at a fixed elevation using \<right-click\>
\<Create Line \[DRAWING CODE\]\> anywhere in the panel.

![](media\image411.png){width="6.268055555555556in"
height="2.4409722222222223in"}

Choose the datum (O.D. or DEPTH).

![](media\image412.png){width="2.7313429571303587in"
height="0.986317804024497in"}

![](media\image413.png){width="2.2686570428696413in"
height="1.0483945756780402in"}

![](media\image414.png){width="6.268055555555556in"
height="2.352777777777778in"}

The geology that has been drawn into a cross-section can be previewed
rapidly in the map by holding the SHIFT key and hovering over the
alignment. If there is geological line-work at that location the
sequence and thicknesses will be shown in a schematic image.

![](media\image52.png){width="5.208333333333333in" height="2.65625in"}

#### Split Geology Line

A geology line can now be split into two lines by right clicking on the
line at the position where it should be split and selecting
**\<split\>**

![](media\image415.PNG){width="6.268055555555556in"
height="2.6729166666666666in"}

![](media\image416.PNG){width="6.268055555555556in"
height="2.088888888888889in"}

In order to move the new node that has been placed in the split
position, you will need to hold down the CTRL key, to prevent the two
lines from re-joining together.

# Developing Conceptual Site Models

This section provides details on how to develop a conceptual model based
around your site data within Groundhog.

*Professional*

![](media\image417.jpeg){width="6.268055555555556in"
height="4.697916666666667in"}

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

A CSM is attached to a notional project "Phase". This allows you to
develop separate models for different phases of a project, for example
desk study, remediation, monitoring. Create a Phase object to contain
the CSM using on Phases Folder.

![](media\image418.PNG){width="2.96916447944007in"
height="2.3649136045494314in"}

Enter a name.

![](media\image419.PNG){width="2.792055993000875in"
height="1.3126837270341207in"}

This initializes a CSM structure in the object tree as a series of
folders, one per component type within the CSM.

![](media\image420.PNG){width="1.9090912073490813in"
height="1.7903915135608048in"}

The available CSM component types are;

> *1. Sources*
>
> *2. Contaminants*
>
> *3. Pathways*
>
> *4. Receptors*

Create any one of these using \<Right-click\> on the appropriate folder
\<Add \[Component Type\]\> for example \<Add Source\>.

![](media\image421.PNG){width="2.489931102362205in"
height="1.718989501312336in"}

Enter a name for the component and an optional description. You can also
use the picklist key to browse a list of pre-set options.

![](media\image422.PNG){width="4.052648731408574in"
height="1.7398261154855643in"}

The component is added to the folder. In this case, expanding the new
source object reveals a series of attributes.

![](media\image423.PNG){width="2.427422353455818in"
height="1.1251574803149607in"}

The CSM_HANDLE is the unique ID attributed to the component in the
system.

Continue adding as many components as you wish to the model.

![](media\image424.PNG){width="1.8008366141732284in"
height="1.6303029308836396in"}

## Creating Pollutant Linkages 

With the desired model components in place you can now define the
pollutant linkages within the system on any model component to create a
linkage to or from that linkage.

Here we link the contaminant "Benzene" to the Source "Filling Station".

![](media\image425.PNG){width="5.302823709536308in"
height="2.7295472440944883in"}

Click \<Contaminant -\> Source\> button.

![](media\image426.PNG){width="3.6463418635170606in"
height="1.271010498687664in"}

Highlight the Source component you wish to link to the Benzene
contaminant (in this case, there is only one, "Filling Station").

![](media\image427.PNG){width="5.459095581802274in"
height="2.4586767279090114in"}

Click \<Copy to selection \>\>\> to add "Filling Station" to the panel
on the right and click \<Apply\> to create the linkage in the data
model.

![](media\image428.PNG){width="5.427841207349081in"
height="2.4690944881889765in"}

Continue in this way, creating all of the conceptual linkages within the
model. You can create the following types of linkage;

¬ Contaminant ◊ Source -- a linkage between a particular source
component and its potential contaminants.

-   **Contaminant -\> Pathway** -- linkages which describe how
    particular contaminants are able physically to migrate.

-   **Source -\> Pathway** -- linkages which show how particular sources
    are connected to particular migration pathways.

-   **Pathway -\> Receptor** -- linkages which show how particular
    pathways are connected to particular receptors.

Note that the linkage dialog will only present the currently available
options for creating new links. If no further linking is possible a
warning message will be displayed.

The linkages are displayed in the Pollutant Linkages folder.

![](media\image429.PNG){width="3.8963768591426073in"
height="1.7710804899387576in"}

\<Right-Click\> on a linkage to delete it. You can also "break" the
linkage, which allows you to record information about how the linkage
has been broken within the conceptual model.

![](media\image430.PNG){width="3.979722222222222in"
height="1.8752613735783028in"}

When a linkage is broken it shows that it has been addressed and will
display with a green tick mark. Hovering over the linkage will display
the description of the break. The break can be removed using

\<Right-Click\>\<Un-break Linkage\>.

![](media\image431.PNG){width="2.802474846894138in"
height="1.3335192475940507in"}

![](media\image432.PNG){width="3.875541338582677in"
height="1.177247375328084in"}

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

![](media\image433.PNG){width="5.646621828521435in"
height="2.427422353455818in"}

There are three types of diagram to choose from.

![](media\image434.PNG){width="2.7502712160979876in"
height="1.2394225721784777in"}

1.  S-P-R -- Source-Pathway-Receptor

2.  C-P-R -- Contaminant-Pathway-Receptor

3.  S-C-P-R -- Source-Contaminant-Pathway-Receptor

Here we show an S-C-P-R diagram.

![](media\image435.png){width="6.268055555555556in"
height="1.7090277777777778in"}

Drag the component boxes and the labels around as desired.

![](media\image436.PNG){width="6.268055555555556in"
height="2.0756944444444443in"}

Use the handles in the bottom-right of each box to re-size.

![](media\image437.PNG){width="2.708799212598425in"
height="1.2727274715660541in"}

\<Right-Click\> in a CSM model component box to edit settings like
colour and to create new linkages.

![](media\image438.PNG){width="3.17752624671916in"
height="1.791917104111986in"}

\<Right-Click\> \<Add Label\> in any whitespace region of the panel to
create new text labels.

![](media\image439.PNG){width="2.5107666229221346in"
height="1.166829615048119in"}

\<Right-Click\> on individual labels to edit the text or delete the
label.

![](media\image440.PNG){width="2.333659230096238in"
height="1.0939031058617672in"}

\<Right-Click\> \<Add Arrow Label\> in any whitespace region of the
panel to create new labels which will be attached to a line, which can
be used to point to the required linkage arrow.

![](media\image441.PNG){width="2.4170034995625547in"
height="1.2293383639545057in"}

![](media\image442.PNG){width="3.27128937007874in"
height="1.2814293525809275in"}

\<Right-Click\> on the label to edit it

![](media\image443.PNG){width="3.3129625984251967in"
height="1.5731364829396326in"}

Click and drag the blue box at the end of the line to move it

![](media\image444.PNG){width="2.531603237095363in"
height="1.083484251968504in"}

Note the **Add Image** option does not currently work.

\<Right-Click\> near to the end of a linkage, close to where it enters
the next component box and select \<Break Linkage\> to break the linkage
in the system.

![](media\image445.PNG){width="3.9276312335958004in"
height="1.791917104111986in"}

Broken linkages display as partial grey lines with a red cross on them.

![](media\image446.PNG){width="3.2817082239720037in"
height="2.0523698600174978in"}

You can un-break a linkage using \<Right-Click\> \<Un-break Linkage\>.
The reason for the linkage has been broken is shown just above the red
linkage broken cross.

The network diagram is automatically saved and if you re-open it, the
changes that have been made to it will be there. When the project is
saved, all network diagrams will also be saved. The saved diagram is
given a unique name by Groundhog, but it can be renamed by right
clicking on it in the data tree and selecting **Rename**.

The following buttons are available in the network diagram toolbar.

  ![](media\image447.png){width="0.2604166666666667in" height="0.2916666666666667in"}    Export Image      Save a copy of the diagram to JPEG or PNG format image.
  -------------------------------------------------------------------------------------- ----------------- --------------------------------------------------------------------------------------------------------------------------------
  ![](media\image448.png){width="0.21875in" height="0.2604166666666667in"}               Refresh           Re-builds the diagram, picking up any new CSM model components that have been added and removing those that have been deleted.
  ![](media\image449.png){width="0.2916666666666667in" height="0.2708333333333333in"}    Hide components   Hides any non-linked CSM model components from the diagram.
  ![](media\image450.png){width="0.25in" height="0.22916666666666666in"}                 New colours       Allocates new, random, colours to the linkages. Useful if the default colour scheme is undesirable.
  ![](media\image451.png){width="0.2604166666666667in" height="0.22916666666666666in"}   Print             Send the diagram to a printer.

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

![](media\image452.PNG){width="5.459095581802274in"
height="1.9273523622047244in"}

Once active, the drawing tools will appear allowing you to draw into the
Phase layer. Draw a shape into the layer. When you double-click to
finish the shape you will be prompted to tag it as a CSM model
component. All shapes drawn into Phase layers MUST be tagged with a CSM
model component.

![](media\image453.PNG){width="4.052648731408574in"
height="1.5418821084864391in"}

If you have drawn a polyline, you can make the line active and then snap
the two ends together to form a polygon.

The shape will adopt the default colour for the component type (in this
case receptor colour) and a label with the name of the component will
appear. The example below show a polygon drawn to indicate the extent of
a proposed residential development.

![](media\image454.PNG){width="2.6253663604549433in"
height="1.989861111111111in"}

### Annotations

You can also tag picture objects and arrows in annotation layers as CSM
model component objects.

**Pictures**

When a picture is added, if a Phase exists within the session, you will
be prompted to tag the picture with a CSM component. Pressing \<Cancel\>
on this prompt results in the picture being added with no tag.

![](media\image455.png){width="4.019116360454943in"
height="1.4902777777777778in"}

![](media\image456.PNG){width="1.8752613735783028in"
height="1.7294083552055992in"}

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

![](media\image457.PNG){width="2.0106977252843397in"
height="0.9063768591426071in"}

### Drawing Water Levels and Defining Aquifers

Special tools have been added to allow the definition of aquifer layers
in drawn cross-sections and a water level can also be superimposed to
define the saturated zone.

First, draw the geology into the cross-section.

![](media\image458.PNG){width="6.268055555555556in"
height="1.382166447944007in"}

To draw the water level, create a new shape layer in the cross-section
using \<Right-Click\> \<New Shape Layer\> in the layer control panel.

![](media\image459.PNG){width="2.8545647419072617in"
height="2.0106977252843397in"}

Enter a name (the name is not important).

![](media\image460.PNG){width="2.737814960629921in"
height="1.2566469816272965in"}

The layer will be added and will become active automatically so that you
can draw into it. Pick up a drawing tool and draw the water level.

![](media\image461.PNG){width="6.268055555555556in"
height="2.332638888888889in"}

Switch off the drawing tool and click on the line to make it active.
When it is active the line vertices will turn green.

![](media\image462.PNG){width="4.875680227471566in"
height="1.2397561242344708in"}

\<Right-Click\> on the line and select \<Tag Shape As...\>

![](media\image463.PNG){width="5.354913604549432in"
height="2.59411198600175in"}

In the options that appear, select "WATER LEVEL".

![](media\image464.PNG){width="2.746201881014873in"
height="1.2638888888888888in"}

De-activate the shape layer in the layer control. The water level line
will appear styled in a particular way to denote water level.

![](media\image465.PNG){width="6.268055555555556in"
height="1.2548611111111112in"}

Next, you need to tell Groundhog which geological unit is the aquifer
unit. This is linked to the CSM, so you will need to make sure you have
an aquifer model component defined (i.e. as a receptor component) within
the model.

![](media\image466.PNG){width="2.1252963692038493in"
height="2.000278871391076in"}

Make the Geology layer active in the layer control. \<Right-Click\> in
the cross-section on the geological unit that corresponds to the aquifer
and select \<Site Investigation\> \<Tag as Aquifer?\>.

![](media\image467.PNG){width="6.268055555555556in"
height="2.0909722222222222in"}

Select the Phase.

![](media\image468.PNG){width="2.754851268591426in"
height="1.2652777777777777in"}

Select the aquifer from the list of receptors.

![](media\image469.PNG){width="4.018950131233596in"
height="1.4791666666666667in"}

Click \<Yes\>

![](media\image470.PNG){width="2.7430555555555554in"
height="1.2246697287839021in"}

The aquifer unit will be outlined in blue and the saturated zone shaded
in blue. Use the transparency of the Geology layer and in the water
level shape layer to get the best image.

![](media\image471.PNG){width="6.268055555555556in"
height="1.3888888888888888in"}

## Accessing Historic Maps

Historic maps are important in contaminated land and brownfield site
studies because they provide insight into the historic land use. To help
with this, Groundhog has a hyperlink functionality that will take you to
the website of the National Library of Scotland, which has an archive of
high-resolution scanned historic maps for the UK.

<https://maps.nls.uk/>

This feature is provided as a convenient 3^rd^ party web link and in no
way implies that the NLS has any connection to, or endorsement of, the
Groundhog software.

\<Right-Click\> at the desired location in the map and select \<Site
Investigation\> \<Browse Historic Maps\>.

![](media\image472.PNG){width="6.136272965879265in"
height="2.8337292213473315in"}

You will be shown this message:

![](media\image473.PNG){width="4.540469160104987in"
height="1.2069444444444444in"}

The NLS website should open in your default web browser. Typically, when
the website first opens, an info box obscures the map view. Click the
cross in the top right corner to close this.

![](media\image474.png){width="6.268055555555556in"
height="3.1958333333333333in"}

You should now see the historic map view zoomed to approximately the
same scale and location as your Groundhog map view.

![](media\image475.png){width="6.268055555555556in"
height="2.8958333333333335in"}

Single-click anywhere in the map. A panel should appear on the right
showing a list view of the vintages of historic map available for that
location.

![](media\image476.PNG){width="4.406864610673666in"
height="4.886099081364829in"}

Click on the hyperlinks in this list panel to open the map you want to
view. The interactive map view will load. Zoom and pan in the historic
map to see the area you are interested in.

![](media\image477.PNG){width="6.268055555555556in"
height="3.8402777777777777in"}

*NLS Website Image*

# Building Geological Models

This section provides details on how to construct 2.5D and 3D property
and structural framework models of measurements and geology within
Groundhog.

*Professional*

![](media\image478.jpeg){width="6.268055555555556in"
height="6.268055555555556in"}

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

-   Fixed thickness, depth or elevation,

-   Borehole picks,

-   Control points,

-   Drawn-cross-sections,

-   Structure contours,

-   Map linework,

-   Dip and azimuth values,

-   Variable thickness rules.

Models are based on a simple grid data structure, but can be clipped out
to project boundaries or other irregular polygonal shapes.

*Professional*

## Defining the Model Grid

In the object tree, navigate to *Models \> Layer Models* and select
*Right-Click \> New Model*.

![](media\image479.png){width="2.5454549431321083in" height="1.92in"}

The model editing dialog appears. Enter the necessary information to set
the name of the model (free-text), choose which elevation model from the
workspace to use as the topographic top of the model, and then enter the
bounding box of the model area and an initial cellsize to use. Set a
coarse resolution for the moment, you can refine it later. If you have a
map window open and zoomed to the model area, you can use the *Extent
From Map* button to populate the bounding box fields automatically.

![](media\image480.png){width="4.662338145231846in"
height="2.623533464566929in"}

Review the input dialog an make sure you have set the following;

1.  Min/max X and Y,

2.  Cellsize (set this to a large value, i.e. low resolution, to begin
    with -- you can change it later)

3.  Name

4.  Clipping Layer -- select a grid, e.g. a DEM, from the workspace.

Click *Apply*. The model definition will be added to the object tree.

![](media\image481.png){width="1.875in" height="0.6875in"}

Add the model to a map window.

![](media\image482.png){width="3.461038932633421in"
height="1.2773611111111112in"}

![](media\image483.png){width="3.4155839895013123in"
height="2.0609853455818024in"}

Open the settings for the model in the map window.

![](media\image484.png){width="3.21875in" height="1.1145833333333333in"}

Check-on Model Outline and Model Grid.

![](media\image485.png){width="4.110389326334208in"
height="1.4832819335083114in"}

Model outline and grid are now visible in the map.

![](media\image486.png){width="4.772727471566054in"
height="3.727338145231846in"}

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

To get started, let's define some outcrop positions. Right-click to
create a new point layer in the map.

![](media\image487.png){width="3.110389326334208in"
height="1.6089523184601924in"}

![](media\image488.png){width="2.0844160104986877in"
height="0.9632524059492563in"}

Make the new layer editable and place some points. Here we are using the
BGS 50k Bedrock Web Map Service as a guide to positioning these points
at the BASE of a mapped unit. When the points have been placed,
de-activate the point layer.

![](media\image489.png){width="6.268055555555556in"
height="2.8854166666666665in"}

In the object tree, *right-click on the model object \> Edit Model*

![](media\image490.png){width="3.0416666666666665in"
height="1.8958333333333333in"}

Click the Create Layer button in the model editing dialog.

![](media\image491.png){width="4.3051946631671045in"
height="2.4282895888014in"}

If the model is new and the project has not been saved, you will see
this.

![](media\image492.png){width="2.4805194663167103in"
height="1.0756944444444445in"}

As models are calculated, their outputs are saved to the project folder.
For this, Groundhog needs to know where the folder lives, so save the
project somewhere and then repeat the Create Layer action again.

In the create layer dialog, enter a name for the layer and click the Add
Inputs button.

![](media\image493.png){width="3.9220778652668415in"
height="1.9182524059492563in"}

This is where we can select which data or parameters to use as input to
the layer. Select the point layer we created as the input and click OK.

![](media\image494.png){width="2.194805336832896in"
height="1.0142661854768154in"}

The points are now added as an input to the layer. Click *Apply*.

![](media\image495.png){width="4.1038965441819775in"
height="2.197899168853893in"}

In the model editing dialog, click *Apply and Build*. If the model
editing dialog is not open, right-click on the model in the object tree
and select *Build*. The model will calculate, and the progress will be
shown in the main progress bar.

![](media\image496.png){width="3.279220253718285in"
height="2.277047244094488in"}

Or...

![](media\image497.png){width="2.4155839895013123in"
height="1.2339665354330709in"}

Go back to the settings dialog for the model layer in the map window and
tick-on the new layer. Also, switch to map coverage view.

![](media\image498.png){width="3.305194663167104in"
height="1.1701279527559054in"}

![](media\image499.png){width="3.6108694225721787in"
height="1.6363637357830272in"}

The calculated extent of the layer will be shown in the map. If it is
unclear on top of the other layers, decrease the layer transparency
using the slider bar in the layer control.

![](media\image500.png){width="3.2212860892388453in"
height="3.6168832020997375in"}

Next we will add some geological map linework. This could be imported
from a shapefile, but for this example we will draw it by hand. Create a
new shape layer in the map window and make it editable.

![](media\image501.png){width="4.110389326334208in"
height="2.8284547244094487in"}

![](media\image502.png){width="4.246753062117235in"
height="2.624932195975503in"}

In the model editing dialog, open the settings for Layer A.

![](media\image503.png){width="4.0389610673665794in"
height="2.2548556430446194in"}

Add the new linework to the layer input list.

![](media\image504.png){width="2.4480522747156606in"
height="1.1312970253718284in"}

![](media\image505.png){width="3.9025973315835523in"
height="2.2689523184601925in"}

Apply and then re-build the model.

![](media\image506.png){width="3.4266447944007in"
height="3.9935061242344707in"}

Note that there is a portion of Layer A in the south-west that does not
match the geological map. Draw a cross-section through the model to
inspect it at this location.

![](media\image507.png){width="4.058441601049869in"
height="2.3838779527559053in"}

View the cross-section and add the model to the view as a layer.

![](media\image508.png){width="6.268055555555556in" height="2.9375in"}

Let's add a component of dip to the layer using a structure contour.
Draw a new line into the Layer A map.

![](media\image509.png){width="6.268055555555556in"
height="3.120833333333333in"}

Switch the drawing tool off and right-click on the new line \>
*Attribute Shape*.

![](media\image510.png){width="2.974025590551181in"
height="2.3565069991251093in"}

Set an attribute called "Z" with a value of "10". This attributes an
elevation value of ten metres to the line, thereby making it a structure
contour.

![](media\image511.png){width="3.2857141294838144in"
height="0.9235958005249344in"}

This adds some additional dip to the layer, but still has not resolved
the unwanted outlier in the south west.

![](media\image512.png){width="6.268055555555556in"
height="1.5645833333333334in"}

Draw another structure contour in the West, setting a Z value of 60m.
This is effectively a structure contour in the air which can be used to
pull the calculated surface up out of the ground.

![](media\image513.png){width="4.344155730533683in"
height="2.6581846019247592in"}

Re-build the model. The layer is now correctly resolved relative to the
outcrop pattern.

![](media\image514.png){width="4.577922134733158in"
height="3.7932950568678914in"}

In the model editing dialog, increase the resolution of the model (e.g.
to 10m cellsize from 100m) and re-build it.

![](media\image515.png){width="3.9652580927384076in"
height="2.2532469378827646in"}

![](media\image516.png){width="4.293449256342957in"
height="3.4805194663167103in"}

Next we will add another bedrock layer with a fixed elevation. Add a new
layer to the model using the model editing dialog.

![](media\image517.png){width="3.201299212598425in"
height="1.7248086176727908in"}

Make the input to this layer a Fixed Elevation parameter.

![](media\image518.png){width="4.337661854768154in"
height="2.289455380577428in"}

Here we set the elevation at 30m, for example.

![](media\image519.png){width="2.0909087926509184in"
height="0.966253280839895in"}

There are now two layers in the model. Re-build the model.

![](media\image520.png){width="3.0844160104986877in"
height="1.6048359580052494in"}

Go to the settings for the model layer in the map window and check-on
the visibility of the new layer.

![](media\image521.png){width="3.694805336832896in"
height="1.3793110236220472in"}

![](media\image522.png){width="4.457602799650044in"
height="3.675324803149606in"}

Note that the outcrop pattern of the new layer has been generated
automatically, based on the intersection with the topography, and also
that the sub-crop position caused by the erosional contact against the
base of the layer above has also been detected automatically. Setting
the model as semi-transparent in the map window shows the sub-crop map
of Layer B beneath Layer A.

![](media\image523.png){width="2.804951881014873in"
height="3.220779746281715in"}

Next we will create a Quaternary-style layer based on map linework and a
thickness value. Create a new shape layer in the map to draw into.

![](media\image524.png){width="2.0in" height="0.9242421259842519in"}

![](media\image525.png){width="4.233766404199475in"
height="3.2768766404199474in"}

Make the new line active and snap the two ends together to form a
polygon or right-click on the line and select *Make Polygon*.

![](media\image526.png){width="4.064935476815398in"
height="2.1351498250218723in"}

Create a new layer using the model editing dialog. Add the Quaternary
map layer as the input and make sure to select a layer type of
"Patches".

![](media\image527.png){width="4.259739720034996in"
height="2.2714523184601925in"}

Switch to the Algorithm tab of the dialog and set the thickness value to
8 (m).

![](media\image528.png){width="4.077922134733158in"
height="1.7377504374453194in"}

In the model editing dialog, note that the layer is at the bottom of the
list. This list is used as the stratigraphic scheme and we need the
Quaternary layer on top of the stack, so drag it to reposition at the
top of the list.

![](media\image529.png){width="3.9935061242344707in"
height="2.2635476815398077in"}

![](media\image530.png){width="4.0in" height="2.2255708661417324in"}

Re-build the model and make the new layer visible in the map. Note that
the "patches" type layer honours the drawn map exactly, unlike the
bedrock model layers which predict the outcrop pattern automatically.

![](media\image531.png){width="3.3842377515310584in"
height="4.058441601049869in"}

In profile, see how the layer thins out towards the edges of the mapped
polygon.

![](media\image532.png){width="4.235819116360455in"
height="4.6168832020997375in"}

Toggle the map view to isopach (thickness) view to get an impression of
how the thickness setting has been graduated within the mapped polygon.

![](media\image533.png){width="4.025974409448819in"
height="2.054068241469816in"}

![](media\image534.png){width="2.9733595800524935in"
height="3.6038965441819775in"}

Edit the map layer and add some windows into the layer.

![](media\image535.png){width="2.878011811023622in"
height="3.629869860017498in"}

Re-build the model. Note how the hierarchy of windows and islands within
the deposit is resolved automatically. This can be taken to any level or
nesting required.

![](media\image536.png){width="3.064935476815398in"
height="3.4802537182852142in"}

By default, model extents are rectangular. To define a polygonal
boundary, create a shape layer and draw the boundary. Make sure to
convert the shape to a polygon.

![](media\image537.png){width="4.4610389326334206in"
height="3.0835826771653543in"}

In the model editing dialog, click the *Extent From Shape* button and
select the model boundary shape layer as the input.

![](media\image538.png){width="4.097402668416448in"
height="2.3056397637795274in"}

![](media\image539.png){width="2.2142858705161856in"
height="1.0232688101487315in"}

Re-build the model.

![](media\image540.png){width="2.8621423884514434in"
height="3.3831167979002625in"}

Draw into the cross-section to use as an input to bedrock layers. Choose
a drawing code for the layer. Here we use GRAVEL, but the code can be
whatever you like. To draw geology, make the Geology layer active in the
section window.

![](media\image541.png){width="3.669899387576553in" height="3.1in"}

![](media\image542.png){width="4.825in" height="1.8838134295713036in"}

Add the cross-section information as an input to Layer A. Go to the
settings for Layer A and choose Cross-Sections as a new input to the
layer. When prompted, choose the drawing code "GRAVEL" as the filter for
the input. This will use all instances of "Gravel" from all
cross-sections as input to the layer calculation.

![](media\image543.png){width="5.105846456692913in" height="2.7in"}

![](media\image544.png){width="2.75in" height="1.2708333333333333in"}

![](media\image545.png){width="5.008333333333334in"
height="2.6856124234470693in"}

Re-build the model. Note that the correlation linework in the
cross-section has been used to control the Layer A surface.

![](media\image546.png){width="4.316666666666666in"
height="3.1315682414698163in"}

You can add models as a layer to the 3D view to visualise them. For more
details, refer to the next chapter on using the 3D graphics window.

![](media\image547.png){width="6.268055555555556in"
height="4.092361111111111in"}

### Additional Tools

The above section provides a general introduction to building layer
models using Groundhog. Here we detail a few extra, specific tools that
are of use during the modelling process.

#### Dip and Azimuth Inputs

Dip and azimuth (structural) inputs are treated as points. To convert a
point object to a structural point that can be used in the modelling,
first make the point layer active. ***\<Right-click\>*** on the desired
point and choose ***\<Add Dip Measurement\>***

![](media\image548.png){width="5.104166666666667in"
height="3.4895833333333335in"}

Use the input dialog to set the DIP, AZIMUTH and RADIUS values. RADIUS
controls the zone of influence of the data point. You can also set a
GEOLOGY code if you wish to have a single point layer containing
structural points from different model layers.

![](media\image549.png){width="4.677083333333333in" height="1.28125in"}

The point becomes an arrow showing the AZIMUTH. The length of the arrow
shows the RADIUS of influence the point will have if used in a
calculation.

![](media\image550.png){width="6.268055555555556in"
height="3.3826388888888888in"}

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

![](media\image551.png){width="3.4479166666666665in" height="2.8125in"}

Here is an example if a coverage polygon drawn for a layer.

![](media\image552.png){width="6.268055555555556in"
height="3.4368055555555554in"}

Note that a coverage can be composed of multiple polygons, including
polygons-with-holes (nested to any level of detail.

Next, add the shape layer to the desired model layer as an input.

![](media\image553.png){width="6.268055555555556in"
height="3.0569444444444445in"}

When prompted to set the shape input as a COVERAGE layer, click
***\<Yes\>***

![](media\image554.png){width="4.479166666666667in" height="2.53125in"}

Note that shape layers which are acting as coverage layers are labelled
thus in the input list.

![](media\image555.png){width="4.0in" height="1.4791666666666667in"}

If you need to change the status of the layer you should delete it from
the inputs list and then re-add it.

Calculate the model. Note that the calculation of the layer stays within
the shapes of the coverage layer.

![](media\image556.png){width="6.268055555555556in"
height="4.360416666666667in"}

Working at a higher resolution shows the effect of this more clearly,
especially if the coverage map is very detailed with lots of small holes
and islands.

![](media\image557.png){width="6.268055555555556in"
height="4.490972222222222in"}

#### Control Points

Points from point layers can be used as control points. Control points
act to remove an area of modelling and are a quick way to clean up
models. Below is an example of a model layer with an area that needs to
be cleaned up (highlighted by the arrows).

![](media\image558.png){width="6.268055555555556in" height="5.23125in"}

To set a point as a control point, place the point in the desired
location and then use ***\<Right-Click\> \<Modelling Tools\> \<Clean
Up\>***

![](media\image559.png){width="6.072916666666667in" height="4.25in"}

The point is displayed as a cross icon.

![](media\image560.png){width="2.9479166666666665in" height="2.09375in"}

Re-build the model.

![](media\image561.png){width="6.268055555555556in"
height="5.579861111111111in"}

### Model Outputs

When a model is built (calculated) a series of useful outputs is
generated into the project folder. Within the folder is a sub-folder
called MODELS and with there a folder for each model in the project.
Within these sub-folders you can find ESRI ASCII grids for base
elevation and thickness and a series of geo-registered images as well as
CSV files of the input points used in the modelling.

![](media\image562.png){width="6.268055555555556in"
height="4.829166666666667in"}

# 3D Graphics

This section provides details on how to operate the 3D graphics
component within Groundhog.

![](media\image563.jpeg){width="6.268055555555556in"
height="3.5256944444444445in"}

*Photo by Nathan Duck on Unsplash*

##  About

The 3D window in groundhog has been developed in order to visualize the
data that you import and create in 2D. All of the features of the 3D
window are available in community edition. From viewing boreholes and
cross sections, as you can in the map and section views, as solid,
spatially referenced objects to elevation grids as surfaces and block
geology models.

## First Use

To open the 3D window, click the
![](media\image564.png){width="0.34379811898512685in"
height="0.35421587926509185in"}3D window button and you will be
presented with the user interface.

## User Interface

![](media\image565.png){width="6.268055555555556in"
height="3.484722222222222in"}

The window has three main areas of control:

### The control panel

![](media\image566.png){width="1.5520002187226596in"
height="6.1332939632545935in"}

The control panel is where you will manipulate what data you are viewing
and how you will view it in 3D. The controls are split into tabs for
easy navigation and there are three controlling buttons at the top:

1.  ![](media\image567.png){width="0.44797900262467194in"
    height="0.4896511373578303in"} Move: This will allow you to rotate,
    pan and zoom in the 3D scene.

2.  ![](media\image568.png){width="0.4271434820647419in"
    height="0.35421587926509185in"} Pick: This button is currently in
    beta but when the window is in this mode, you can no longer move
    around but instead select objects by clicking them. When an object
    is selected (clicked on) it will open in the object explorer tab
    which we will visit later. (As his is in beta only some data types
    are supported)

3.  ![](media\image569.png){width="0.44797900262467194in"
    height="0.40630686789151355in"}Save: Self-explanatory but with many
    functions, the save button will allow you to save a variety of items
    from the configuration of the window (camera position and layers) to
    mp4 videos you record to .OBJ exports of supported layers in the
    window.

### Layer Control

![](media\image570.png){width="2.156550743657043in"
height="1.2814293525809275in"}The first of the tabs in the control panel
is the **layer control** with which you will be familiar from the map
and section window. Along the top, left to right, there is:

1.  The add layer button, opening the usual dialogue

2.  The global setting button which opens this dialogue:
    ![](media\image571.png){width="4.021394356955381in"
    height="1.4897911198600176in"}

> Here you can set the vertical scale of the window, the maximum
> vertical scale for the slider and turn on and off the axes in the
> window.

3.  The background colour button, which changes the background colour of
    the 3D window

4.  The clear layers button which will remove all of the layers from the
    window.

Note: when adding the current map window, you will be presented with the
following option dialog box

![](media\image572.png){width="3.537736220472441in"
height="1.7688681102362205in"}

Here you can either choose to view the map as a flat surface at a fixed
elevation (e.g. for points) or as grid elevation which will create a
surface from a sampling the elevations on a chosen grid

The next item is the representation of a layer.

![](media\image573.png){width="2.614948600174978in"
height="0.6667596237970254in"}

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

### ![](media\image574.png){width="3.979722222222222in" height="2.8233103674540683in"}Object Explorer

The next tab is the **object explorer** which allows a particular layer
to be interrogated. By opening the above borehole layer in the object
explorer, we can see the two boreholes that are in the dataset are shown
in the panel. Each borehole can then be turned on and off with the
checkbox and its transparency changed with the slider. Right click on a
borehole or any object in the explorer, that item will become the
**pivot** of the window. There may also be settings for an object which
can be accessed through the settings button.

If you double click an object in the explorer, that object will be
"opened".

![](media\image575.png){width="2.062787620297463in"
height="2.177387357830271in"}Here, the object BH502 has been opened and
you can now see all of the logs and manipulate them as with any other
object.

The arrow buttons can be used to move backwards and forwards in and out
of objects.

### Clipping Controls

![](media\image576.png){width="2.284736439195101in"
height="1.616000656167979in"}After the object explorer, you will find
the **clipping controls** tab. The add button will give you two options:

1.  Add new clipping Plane: this will add a new clipping plane to the
    scene, allowing you to slice and interrogate your data at whatever
    angle you wish wherever.

This is particularly useful for viewing 3D geological models produced in
Groundhog Professional.

![](media\image577.png){width="2.9040004374453194in"
height="1.6959995625546807in"}![](media\image578.png){width="2.9034722222222222in"
height="1.6878488626421697in"}

When you create a clipping plane, you will be greeted with a control
that looks like this:

![](media\image579.png){width="2.073206474190726in"
height="1.510627734033246in"}To rotate the plane, drag the circle at the
end of the line, and to move the center point of the plane, drag the
center circle in that direction.

If you are struggling with this control, by clicking the settings
button, you can also incrementally change the positions.

![](media\image580.png){width="1.989861111111111in"
height="1.5627176290463691in"}A is for azimuth as an angle in degrees.

If you choose a **clipping slice** the controls are much the same, with
the addition of a thickness. On the graphical control:
![](media\image581.png){width="1.222800743657043in"
height="0.9693700787401575in"}and by buttons is represented by T:
![](media\image582.png){width="1.1714665354330709in" height="0.92in"}

The difference with a clipping slice over a clipping plane is that there
is somewhat a slice of cake taken out of a model :

![](media\image583.png){width="4.733109142607174in" height="4.72in"}

### Configurations

**Configurations** is the final tab in the control panel and its purpose
is to provide shortcuts to nice "views" of your data.

If you like an angle of looking at your data or particular clip, you can
press the save button
![](media\image569.png){width="0.44797900262467194in"
height="0.40630686789151355in"}and all the information will be saved, a
link to it being shown then in the configurations tab.

![](media\image584.png){width="2.0836242344706912in"
height="2.3128226159230096in"}Select the saved configuration you would
like to see and you will be taken there.

While a configuration is selected, selecting this button will allow you
to rename the configuration

The bin will remove all configurations.

### The Hot Bar

![](media\image585.png){width="6.268055555555556in"
height="0.45902777777777776in"}

The hot bar is the area at the bottom of the groundhog 3D window which
looks like the screenshot above. Here you can find useful information
and some quick access tools.

The first item is the loading bar.
![](media\image586.png){width="2.1461329833770777in"
height="0.40630686789151355in"} This will give you information on the
progress of any actions such as loading and saving.

Next is the vertical exaggeration slider.
![](media\image587.png){width="2.531603237095363in"
height="0.22919838145231847in"}By moving this slider, you will increase
or decrease the vertical exaggeration on the window.

The following tools you will find are the recording and playback tools.
![](media\image588.png){width="1.2605927384076991in"
height="0.34379811898512685in"} In order to create a playback, click the
record button, maneuver around the scene in the order you wish to
re-watch and, finally, click the stop button that will have replaced the
record button.![](media\image589.png){width="1.3960279965004374in"
height="0.4271434820647419in"}

In order to watch your playback, simply click the play button.

When the play button becomes available, you will be able to save a
playback as an MP4 by clicking the save button
![](media\image569.png){width="0.44797900262467194in"
height="0.40630686789151355in"} and selecting the playback option from
the dropdown.

Finally, on the hot bar, there is the message area.
![](media\image590.png){width="3.1150185914260717in"
height="0.3021259842519685in"} Useful tips will be displayed here.

### The Scene

This is the final area of the 3D window and is where all of the data
appears.

![](media\image591.png){width="6.268055555555556in"
height="3.734722222222222in"}

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

> ![](media\image592.png){width="4.333938101487314in"
> height="6.230036089238845in"}

## Saving

The save button ![](media\image569.png){width="0.44797900262467194in"
height="0.40630686789151355in"} is a multi-functional save tool which
will allow the saving of any savable layers or items that are currently
existent within your current session. These could include 3D objects,
videos and the configuration of your window.

When the save button is pressed, the following dropdown box will appear.

![](media\image593.png){width="3.3913046806649167in"
height="1.9616371391076115in"}

All of the options in the dropdown can be saved to their stated format
and the possible options are as follows.

### Cross Sections

Cross sections can be saved from the 3D window to the .OBJ format which
can then be imported into GeoVisionary and many other CAD platforms.
There will be a selection of files exported which will be one for each
unit and one which will represent all of the sections. All will be
placed in a single folder in your chosen location called "Cross
Sections".

### Models

Geological models can also be saved to the .OBJ format and there will be
a file created for each stratigraphic layer of your model. These will
all be saved to the folder of your choosing.

### Surfaces

Keeping consistent with the other layers, surfaces too will be export as
.OBJ files. There will be three files output.

![](media\image594.png){width="6.268055555555556in" height="0.65625in"}

These three should be kept together; there is one for the shapes, one
for the colours and optionally one which will be the image used for the
surface.

### Videos

If the playback function has been used then there will be the option to
save this to an mp4 video. During the saving of the video, the window
will be temporarily out of action and appear to move by itself, this is
so that the information can be collected. Please do not interrupt this.

### Configurations

![](media\image584.png){width="2.0836242344706912in"
height="2.3128226159230096in"}The final option is the current map window
configuration and as previously mentioned will save the view on the
screen as a waypoint which you will be able to click and return to at a
later date. Once you have provided a memorable name, it will appear in
the configurations tab like this:

# Appendix -- Configuring the Groundhog Home Area

## Groundhog New User

If you have never installed Groundhog before, the first time you run
Groundhog after installation you will see:

![](media\image595.PNG){width="6.268055555555556in"
height="3.1979166666666665in"}

It is **very important** that you read the instructions on this window,
before choosing the location for your Groundhog home folder. If you do
choose a folder that already exists and contains files, you will see
this warning message:

![](media\image596.PNG){width="3.3992672790901137in"
height="2.941391076115486in"}

Click **No** if you are not 100% confident about using this folder.
Clicking **No** will close Groundhog and you will need to restart in
order to select a different home folder.

Once a home folder has been successfully chosen, Groundhog will start.

## Upgrading from a previous version of Groundhog to version 2.2

If you have previously been using Groundhog and this is the first time
you open Groundhog 2.2 the following message will appear as you start
Groundhog:

![](media\image597.PNG){width="6.268055555555556in"
height="4.236805555555556in"}

Once you have clicked **OK** to this, you will be asked to choose the
location of your new Groundhog home. It is **very important** that you
follow the instructions very closely:

![](media\image598.PNG){width="6.215007655293088in"
height="3.1674004811898513in"}

Groundhog will not allow you to select the same Groundhog home area that
you used in a previous version of Groundhog

![](media\image599.PNG){width="3.5642858705161853in"
height="1.9603849518810148in"}

Groundhog will close when you press **OK** to this message and you will
need to restart in order to select a new 2.2 Groundhog home.

Once you have done this, Groundhog will start. If you previously had a
professional license, this will be carried across to version 2.2. Any
user-supplied templates and ornaments that existed in the 2.1 workspace
will be automatically taken across to the new 2.2 workspace.

## Other Groundhog Home Functions

### Open Home Folder

You can easily check at any time where your Groundhog home folder
structure resides and what is held there. Select the SessionHomeOpen
option from the main menu:

![](media\image600.PNG){width="5.521604330708661in"
height="3.6880150918635173in"}

This gives the option to choose which folder you would like to view. The
chosen folder will open in a windows explorer window.

### Create New

Selecting SessionHomeCreate New allows you to choose a new Groundhog
Home area and restore it to factory settings.

![](media\image601.PNG){width="6.268055555555556in"
height="3.1055555555555556in"}

Follow the instructions here and press save. Once the new Groundhog home
area has been configured, you will be asked to restart Groundhog:

![](media\image602.PNG){width="2.812892607174103in"
height="1.2814293525809275in"}

Please note -- if you have a professional license or extra files within
your old Groundhog home area, these will be wiped out by using this
function. Please contact the Groundhog help team for advice if you have
lost something you require (<groundhog@bgs.ac.uk>).

### Report

This option will report the location of the Groundhog home folder.

![](media\image603.PNG){width="6.268055555555556in"
height="2.915277777777778in"}

![](media\image604.PNG){width="4.344355861767279in"
height="1.4481189851268592in"}

### Clean Up

Not all user setups are the same and in order to accommodate as many
user configurations as possible, groundhog stores the location of
Groundhog home in two places. These should match. If they do not and you
are experiencing problems, please try running the cleanup option --
SessionHomeClean Up. Upon completion, this option will confirm that the
clean up has taken place.

# 
