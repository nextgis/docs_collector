.. _ngcollector_auth:

Authorization
==============

Via cloud server (my.nextgis.com)
-----------------------------------

For subscribed users, authorization in the NextGIS Collector application is carried out via https://my.nextgis.com/ server by default.
The email and password from the cloud NextGIS ID are used as a login and password for app.


.. figure:: _static/ngc_login_en.png
   :name: ngc_login_pic
   :align: center
   :width: 10cm

   Login screen


Via on-premise (NGIDOP)
-----------------------

For authorization in NextGIS Collector via on-premise server, you must specify the appropriate Endpoint in the authorization settings (см. :numref:`ngidop_collector`).  If you're already logged in with my.nextgis.com - log out first.

.. figure:: _static/ngm_ngidop_en_3.png
   :name: ngidop_collector
   :align: center
   :width: 10cm
   
   Adding your own authorization server in NextGIS Collector

Change user
------------

To view the information of the user currently signed in the app, go to the Settings page. 

.. figure:: _static/ngc_ngid_view_en.png
   :name: ngc_ngid_view_pic
   :align: center
   :width: 10cm

   User info in the app settings

To change the user, press "Sign out from NextGIS" and log in as described above.
