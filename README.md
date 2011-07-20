Jenkins Keyhole
===============

[Jenkins](http:jenkins-ci.org) is the leading open-source continuous integration
server.

[Keyhole Markup Language](http://en.wikipedia.org/wiki/Keyhole_Markup_Language)
(KML) is an XML notation for expressing geographic annotation and visualization
within Internet-based, two-dimensional maps and three-dimensional Earth browsers.


Additions
---------

 * Locate your latitude and longitude, e.g. via
   [Google Maps](http://maps.google.com)
 * Add a new Placemark XML segment for your name
   and location
 * Commit and push the updated KML document
 * Refresh the map (updates may not be immediately
   visible due to Google Maps caching)


Example Placemark
-----------------

```xml
<Placemark>
  <name>Jane Smith</name>
  <Point>
    <extrude>1</extrude>
    <altitudeMode>relativeToGround</altitudeMode>
    <coordinates>longitude,latitude</coordinates>
  </Point>
</Placemark>
```
