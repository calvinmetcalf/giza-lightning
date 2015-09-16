[//]: # (title page)
Writing a *WMS/WMTS* server at *AppGeo* by *Calvin W. Metcalf B.S.*

[//]: # (slide 1)
Goal: *XYZ* tile pyramid, viewable in *ArcMap*.

[//]: # (slide 2)
Via *WMTS*

[//]: # (slide 3)
but need *WMS* too

[//]: # (slide 4)
WMTS *seems* slow

[//]: # (slide 5)
WMS *is* slow

[//]: # (slide 6)
spec is *extremely* detailed about certain things (error messages)

[//]: # (slide 7)
and *strangely silent* on others (non rectangular caches, mixed file types)

[//]: # (slide 8)
*all* implementations are really weird

[//]: # (slide 9)
versions of *ArcMap* won't zoom past 19 in WMTS

[//]: # (slide 10)
certain versions of *QGIS* will download *Gigabytes* of tiles if only the default bounding box is set

[//]: # (slide 11)
ArcMap shifts WMTS by *15 feet* to the left

[//]: # (slide 12)
Auth: on the plus side *ArcGIS* doesn't save them in plain text like *QGIS*

[//]: # (slide 13)
Transparent photograph issue (issue with *OGC* spec)

[//]: # (slide 14)
Many clients have issues with *on the fly projections* (you have one job *GIS* software)

[//]: # (slide 15)
Succeeded in building a library for this in *node.js*

[//]: # (after)
- me: *Calvin Metcalf*
- my *company: AppGeo*
- this presentation: *https://calvinmetcalf.github.io/wms-lightning*
- the library: *https://github.com/calvinmetcalf/WMS*
