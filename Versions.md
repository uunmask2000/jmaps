#This page contains information about versions starting with [r59](https://code.google.com/p/jmaps/source/detail?r=59)

## [r75](https://code.google.com/p/jmaps/source/detail?r=75) ##
  * Added the AddCopyright function to support the creation of new map types
  * Added the SetMapType function to accept map type constants

## [r74](https://code.google.com/p/jmaps/source/detail?r=74) ##
  * Removed GetMapType function for initialisation, and instead require the constant of the maptype.  Allows support for custom map types.

## [r72](https://code.google.com/p/jmaps/source/detail?r=72) ##
  * Added MarkerManager support for the open source marker manager (see docs)

## [r69](https://code.google.com/p/jmaps/source/detail?r=69) ##
  * Added the CheckResize function and demo, allows for more dynamic maps (thanks to Cyrille Heulland for the suggestion)

## [r64](https://code.google.com/p/jmaps/source/detail?r=64) ##
  * Added the 'centerMoveMethod' to the Mapifies.AddMarker method.
  * Updated the 'init' callback to now include the map.  The order is 'thisMap', 'element', 'options'
  * Added an example to show using GEvent within jMaps code.

## [r61](https://code.google.com/p/jmaps/source/detail?r=61) ##
  * Put helper functions into Mapifies namespace.  This now means you call these functions like this:
```
var valid = Mapifies.SearchCode(result.getStatus());
```
  * Updated demos and documentation

## [r59](https://code.google.com/p/jmaps/source/detail?r=59) ##

  * Release of new API version with full API docs at http://map.ifies.org