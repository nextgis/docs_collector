.. sectionauthor:: Roman Gainullov <roman.gainullov@nextgis.com>

.. _ngcol_tools:

Basic operations
==================

This section contains a list of the main functions available to the data collector in the NextGIS Collector mobile application.
At this stage, the user has already passed auth in the application and selected a project configured by administrator for data collection.


.. _ngcol_create_point:

Add a point
-----------

There are two ways to add a point in the application:

1. Mark it on the map (using a basemap, raster image, etc.)
2. Using the device's GPS coordinates

.. figure:: _static/ngcol_add_point_en.png
   :name: ngcol_add_point
   :align: center
   :width: 10cm
 
   Add item icon
  

.. figure:: _static/ngcol_map_gps.png
   :name: ngcol_map_gps
   :align: center
   :width: 10cm
 
   Ways to add a point

To add a point **using the map** you need to indicate its location with the cursor. You can move the cursor automatically to the center of the screen (red cross) or your current location (blue circle) using the buttons in the bottom panel.
After marking the point press the floppy disk icon in the top right corner to save.

.. figure:: _static/ngcol_save_location_en.png
   :name: ngcol_save_location
   :align: center
   :width: 10cm
 
   Floppy disk icon - save the location of the point

On the next screen you need to set attributive info and, if necessary, attach photos.
Then confirm adding a point by clicking on the checkmark on the top panel.

.. figure:: _static/ngcol_add_photo.png
   :name: ngcol_add_photo
   :align: center
   :width: 10cm
 
   Attaching a photo. You can select from the device memory or make a new one in the application

.. figure:: _static/ngcol_point_attr_en.png
   :name: ngcol_point_attr_pic
   :align: center
   :width: 10cm
   
   Entering attributes and completing the creation

If you choose to add a point **by GPS**, you will be redirected straight to the attribute screen. Add attribute information and tap the tick in the top panel to save the new point.

.. figure:: _static/ngcol_attr_gps.png
   :name: ngcol_attr_gps
   :align: center
   :width: 10cm
 
   Adding a point by GPS
   
   
.. _ngcol_modify_point:

Edit a point on the map
------------------------

The app allows changing:

1. Point locations
2. Point's attributes / attachments

To edit a point:

1. Select a point by clicking on the map. The toolbar will open on the right side of the screen.

* Upper - change location, 
* lower - change attributes.

.. figure:: _static/ngcol_edit_point_en.png
   :name: ngcol_edit_pont
   :align: center
   :width: 10cm
 
   Point location and Attribute editing tools


2. Change the location of the point as needed. There are 3 ways to do this:

- Move the cursor on the map;
- Use the panel at the bottom of the screen - automatically position the cursor either in the center of the map, or your current location.

.. figure:: _static/ngcol_edit_location_en.png
   :name: ngcol_edit_location
   :align: center
   :width: 10cm
 
   Center map and current location tools

3. Edit attribute information and attachments as needed.
4. Press floppy disc icon to save changes.

.. _ngcol_create_point:

Add a polygon
----------------

To add a polygon to one of the layers, first open the map and tap the plus icon. Then select a layer containing polygons.

.. figure:: _static/ngcoll_add_polygon_en.png
   :name: ngcoll_add_polygon_pic
   :align: center
   :width: 10cm
 
   "Add item" icon

Select the layer to add a polygon to and the way to use for its creation - using map or GPS.

.. figure:: _static/ngcol_map_gps_polygon_en.png
   :name: ngcol_map_gps_polygon_pic
   :align: center
   :width: 10cm
   
   Selecting layer and way of adding a polygon

You will be redirected to the map again. A triangle will appear with a cursor at its top left corner. 

.. figure:: _static/ngcol_new_polygon_en.png
   :name: ngcol_new_polygon_pic
   :align: center
   :width: 10cm
   
   Polygon template

To modify the shape of the polygon select one apex at a time with the cursor and drag it to the desired location.

.. figure:: _static/ngcol_polygon_edit_en.png
   :name: ngcol_polygon_edit_pic
   :align: center
   :width: 10cm
   
   Modifying the shape of the polygon

To safe the new polygon, press the floppy disk icon in the top right corner.

.. figure:: _static/ngcol_polygon_save_en.png
   :name: ngcol_polygon_save_pic
   :align: center
   :width: 10cm
   
   "Save" icon

In the next screen enter the necessary attributes and tap the tick in the top panel to complete creating the polygon.

.. figure:: _static/ngcol_polygon_ref_en.png
   :name: ngcol_polygon_ref_pic
   :align: center
   :width: 10cm
   
   Completing the creation

Newly created polygon will be visible in the app and on a Web Map in the Web GIS that has this layer added.

.. figure:: _static/ngcol_polygon_complete_en.png
   :name: ngcol_polygon_complete_pic
   :align: center
   :width: 10cm
   
   Newly created polygon on the map in the NextGIS Collector app
   
.. figure:: _static/ngcol_polygon_on_webmap_en.png
   :name: ngcol_polygon_on_webmap_pic
   :align: center
   :width: 20cm
   
   Newly created polygon on a map in Web GIS

..:note:

   Make sure the basemap is below the polygon layer and does not obscure it.


.. _ngcol_modify_polygon:

Editing polygons
-----------------------

To modify a polygon, tap it. It will be outlined in blue and two icons will appear to the right. 

* Upper one - editing the shape of the polygon (select an apex with the cursor and drag it).
* Lower one - editing the attributes.

.. figure:: _static/ngcol_polygon_editing_tools_en.png
   :name: ngcol_polygon_editing_tools_pic
   :align: center
   :width: 10cm
   
   Editing a polygon




.. _ngcol_scale:

Zoom and current location
--------------------------

The data collector has the ability to control the current scale of the map.
To do this, on the left side of the map there are items for zooming in and out (+/-).
In the same block, you can set the map extent by the current location of the device.

.. figure:: _static/ngcol_scale_en.png
   :name: ngcol_scale
   :align: center
   :height: 20cm
 
   Zoom and current location controls


.. _ngcol_tracks:

Tracks
------

NextGIS Collector allows you to record tracks. The track control icon is on the top panel.

.. figure:: _static/ngcol_track_icon.png
   :name: ngcol_track_icon
   :align: center
   :height: 5cm
 
   Tracks icon


.. figure:: _static/ngcol_start_track.png
   :name: ngcol_start_track
   :align: center
   :height: 10cm
 
   Starting track recording/track list


To do this, the app must be given permission to write data in the background in the device settings.

.. figure:: _static/ngcol_permissions1.png
   :name: ngcol_permissions1
   :align: center
   :height: 10cm
 
   Background geolocation request


.. figure:: _static/ngcol_permissons2.png
   :name: ngcol_permissons2
   :align: center
   :height: 10cm
   
   Allow location to be used in any (including background) mode


User-recorded tracks can be shown / hidden, changed digital palette, exported or deleted.

.. figure:: _static/ngcol_track_list.png
   :name: ngcol_track_list
   :align: center
   :height: 5cm
 
   Recorded track list
   
   
.. _ngcol_sync:

Synchronization
----------------

To force synchronization of data with Web GIS, you can use the icon on the top panel.

.. figure:: _static/ngcol_sync.png
   :name: ngcol_sync
   :align: center
   :height: 5cm
 
   Synchronization
