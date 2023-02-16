# Operational-transformation-gis
A simple implementation of operational transformation function coupled with web gis editor. It reuses Mozilla's [TogetherJS's](https://togetherjs.com/docs/) OT function [TextReplace] (https://github.com/jsfiddle/togetherjs/blob/develop/togetherjs/ot.js), modified to handle a set of coordinates instead of a set of characters. The modified function is named CoordsReplace.

The editor uses [OpenLayers](https://openlayers.org/) for the visualization of the map and for required map controls such as zoom in/out, pan, modifying geometry, loading vector geometry.

For the sake of simplicity everything is packed within a single HTML file.

Some basic instructions on how it works are provided within the GUI when started.
Will work started from users local hdd, only OpenLayers is referenced from the web.
