# OS MasterMap Integrated Transport Network Layer

These are SLD files for OS MasterMap Integrated Transport Network in GML format for use in GeoServer.

*They have been designed to work with the data loaded into a database, e.g. PostGIS, with fieldnames in full and in lowercase.*

## Quick start guide

**1.**  Fork or [download](https://github.com/OrdnanceSurvey/OS-MasterMap-Integrated-Transport-Network-stylesheets/archive/master.zip) the contents of this repository

**2.**  Copy the folder ‘ordnance_survey_ITN’ into your GeoServer SVG directory

**3.**  Load your Integrated Transport Network GML data into GeoServer

**4.**  Add the styles. If using the GUI then navigate to Styles > Add a new style > Browse and select to add each file in turn

**5.**  Publish these styles with the data. If using the GUI then navigate to Layers > Add a new resource and choose them from the relevant database to add each file in turn. Click on publish, configure settings and then choose the matching style before saving

**6.**  To create Strategi in GeoServer you will need to create a Layer Group. If using the GUI then navigate to Layer Groups > Add new layer group > Add Layer and choose each layer in turn to create the following layer order:

  ![Screenshot](https://github.com/OrdnanceSurvey/OS-MasterMap-Integrated-Transport-Network-stylesheets/raw/master/GML%20stylesheets/GeoServer%20stylesheets%20(SLD)/images/OS_MasterMap_Integrated_Transport_Network_layer_order.png )

The name of this Layer Group is the ‘layer’ your web map service (WMS) will need to call.

The scale denominators have been set to allow viewing between **1:250** and **1:20 000**, although this will vary slightly by resolution.

Your data should now look similar to this: 

  ![Screenshot](https://github.com/OrdnanceSurvey/OS-MasterMap-Integrated-Transport-Network-stylesheets/raw/master/GML%20stylesheets/GeoServer%20stylesheets%20(SLD)/images/OS_MasterMap_Integrated_Transport_Network_screenshot.png "Screenshot of OS MasterMap Integrated Transport Network Layer")

## Additional information

[More information about how to download, apply and customise our stylesheets including a Stylesheet User Guide](http://www.ordnancesurvey.co.uk/resources/carto-design/cartographic-stylesheets.html)

[More information about OS MasterMap Integrated Transport Network Layer](https://www.ordnancesurvey.co.uk/business-and-government/products/itn-layer.html)

[More information about cartographic design at Ordnance Survey](https://www.ordnancesurvey.co.uk/resources/carto-design/)

## Licence

By using these stylesheets you are accepting the terms of the [Open Government Licence](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)