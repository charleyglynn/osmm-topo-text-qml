# OS MasterMap Topography Layer
##Cartographic Text QML for use in QGIS
A simple QML file for use in QGIS which sorts out the label placement for [OS MasterMap Topography Layer](https://www.ordnancesurvey.co.uk/business-and-government/products/topography-layer.html) GML.

I have used the data-defined label options and created custom expressions that convert the 'anchorposition' numeric values into the strings that QGIS requires.

It is a very simple QML and other than sizing, orientation and position I haven't styled the text in any way. This could be done using the 'featurecode' or a combination of the other attributes.

This is an alternative to the [official Ordnance Survey stylesheets](https://github.com/OrdnanceSurvey/OSMM-Topography-Layer-stylesheets).
