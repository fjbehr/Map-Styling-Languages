# Map-Styling-Languages
---

An overview about Map Styling Languages.



---

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [GitLab CI](#gitlab-ci)
- [GitLab User or Group Pages](#gitlab-user-or-group-pages)
- [Did you fork this project?](#did-you-fork-this-project)
- [Troubleshooting](#troubleshooting)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->
# An overview about Map Styling Languages

# SLD

### Examples

1. SLD with filter and styling

http://gis.ibbeck.de/include/mapserver/mapserv.exe?map=/daten/mapfiles/world/World.map&LAYERS=COUNTRY&FORMAT=image%2Fpng&VERSION=1.1.1&TRANSPARENT=TRUE&SLD_BODY=%3C%3Fxml%20version%3D%221.0%22%20encoding%3D%22utf-8%22%3F%3E%3CStyledLayerDescriptor%20version%3D%221.0.0%22%20xmlns%3D%22http%3A%2F%2Fwww.opengis.net%2Fsld%22%20xmlns%3Agml%3D%22http%3A%2F%2Fwww.opengis.net%2Fgml%22%20xmlns%3Aogc%3D%22http%3A%2F%2Fwww.opengis.net%2Fogc%22%20xmlns%3Axlink%3D%22http%3A%2F%2Fwww.w3.org%2F1999%2Fxlink%22%20xmlns%3Axsi%3D%22http%3A%2F%2Fwww.w3.org%2F2001%2FXMLSchema-instance%22%20xsi%3AschemaLocation%3D%22http%3A%2F%2Fwww.opengis.net%2Fsld%20http%3A%2F%2Fschemas.opengeospatial.net%2Fsld%2F1.0.0%2FStyledLayerDescriptor.xsd%22%3E%3CNamedLayer%3E%3CName%3ECOUNTRY%3C%2FName%3E%3CUserStyle%3E%3CFeatureTypeStyle%3E%3CRule%3E%3Cogc%3AFilter%3E%3Cogc%3APropertyIsLike%20wildCard%3D%22*%22%20singleChar%3D%22%23%22%20escape%3D%22!%22%3E%3Cogc%3APropertyName%3EContinent%3C%2Fogc%3APropertyName%3E%3Cogc%3ALiteral%3EAfrica%3C%2Fogc%3ALiteral%3E%3C%2Fogc%3APropertyIsLike%3E%3C%2Fogc%3AFilter%3E%3CPolygonSymbolizer%3E%3CFill%3E%3CCssParameter%20name%3D%22fill%22%3E%235599DD%3C%2FCssParameter%3E%3C%2FFill%3E%3CStroke%3E%3CCssParameter%20name%3D%22stroke%22%3E%23000000%3C%2FCssParameter%3E%3C%2FStroke%3E%3C%2FPolygonSymbolizer%3E%3C%2FRule%3E%3C%2FFeatureTypeStyle%3E%3C%2FUserStyle%3E%3C%2FNamedLayer%3E%3C%2FStyledLayerDescriptor%3E&SERVICE=WMS&REQUEST=GetMap&STYLES=&EXCEPTIONS=application%2Fvnd.ogc.se_inimage&SRS=EPSG%3A4326&BBOX=-52,-90,76,38&WIDTH=256&HEIGHT=256</a>

Open the example above in a new tab: <a href="http://gis.ibbeck.de/include/mapserver/mapserv.exe?map=/daten/mapfiles/world/World.map&LAYERS=COUNTRY&FORMAT=image%2Fpng&VERSION=1.1.1&TRANSPARENT=TRUE&SLD_BODY=%3C%3Fxml%20version%3D%221.0%22%20encoding%3D%22utf-8%22%3F%3E%3CStyledLayerDescriptor%20version%3D%221.0.0%22%20xmlns%3D%22http%3A%2F%2Fwww.opengis.net%2Fsld%22%20xmlns%3Agml%3D%22http%3A%2F%2Fwww.opengis.net%2Fgml%22%20xmlns%3Aogc%3D%22http%3A%2F%2Fwww.opengis.net%2Fogc%22%20xmlns%3Axlink%3D%22http%3A%2F%2Fwww.w3.org%2F1999%2Fxlink%22%20xmlns%3Axsi%3D%22http%3A%2F%2Fwww.w3.org%2F2001%2FXMLSchema-instance%22%20xsi%3AschemaLocation%3D%22http%3A%2F%2Fwww.opengis.net%2Fsld%20http%3A%2F%2Fschemas.opengeospatial.net%2Fsld%2F1.0.0%2FStyledLayerDescriptor.xsd%22%3E%3CNamedLayer%3E%3CName%3ECOUNTRY%3C%2FName%3E%3CUserStyle%3E%3CFeatureTypeStyle%3E%3CRule%3E%3Cogc%3AFilter%3E%3Cogc%3APropertyIsLike%20wildCard%3D%22*%22%20singleChar%3D%22%23%22%20escape%3D%22!%22%3E%3Cogc%3APropertyName%3EContinent%3C%2Fogc%3APropertyName%3E%3Cogc%3ALiteral%3EAfrica%3C%2Fogc%3ALiteral%3E%3C%2Fogc%3APropertyIsLike%3E%3C%2Fogc%3AFilter%3E%3CPolygonSymbolizer%3E%3CFill%3E%3CCssParameter%20name%3D%22fill%22%3E%235599DD%3C%2FCssParameter%3E%3C%2FFill%3E%3CStroke%3E%3CCssParameter%20name%3D%22stroke%22%3E%23000000%3C%2FCssParameter%3E%3C%2FStroke%3E%3C%2FPolygonSymbolizer%3E%3C%2FRule%3E%3C%2FFeatureTypeStyle%3E%3C%2FUserStyle%3E%3C%2FNamedLayer%3E%3C%2FStyledLayerDescriptor%3E&SERVICE=WMS&REQUEST=GetMap&STYLES=&EXCEPTIONS=application%2Fvnd.ogc.se_inimage&SRS=EPSG%3A4326&BBOX=-52,-90,76,38&WIDTH=256&HEIGHT=256" target="_blank">Example</a>

Decoded it is:

`http://gis.ibbeck.de/include/mapserver/mapserv.exe?map=/daten/mapfiles/world/World.map&LAYERS=COUNTRY&FORMAT=image/png&VERSION=1.1.1&TRANSPARENT=TRUE&SLD_BODY=<?xml version="1.0" encoding="utf-8"?><StyledLayerDescriptor version="1.0.0" xmlns="http://www.opengis.net/sld" xmlns:gml="http://www.opengis.net/gml" xmlns:ogc="http://www.opengis.net/ogc" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:schemaLocation="http://www.opengis.net/sld http://schemas.opengeospatial.net/sld/1.0.0/StyledLayerDescriptor.xsd"><NamedLayer><Name>COUNTRY</Name><UserStyle><FeatureTypeStyle><Rule><ogc:Filter><ogc:PropertyIsLike wildCard="*" singleChar="#" escape="!"><ogc:PropertyName>Continent</ogc:PropertyName><ogc:Literal>Africa</ogc:Literal></ogc:PropertyIsLike></ogc:Filter><PolygonSymbolizer><Fill><CssParameter name="fill">#5599DD</CssParameter></Fill><Stroke><CssParameter name="stroke">#000000</CssParameter></Stroke></PolygonSymbolizer></Rule></FeatureTypeStyle></UserStyle></NamedLayer></StyledLayerDescriptor>&SERVICE=WMS&REQUEST=GetMap&STYLES=&EXCEPTIONS=application/vnd.ogc.se_inimage&SRS=EPSG:4326&BBOX=-52,-90,76,38&WIDTH=256&HEIGHT=256`

2. SLD with server-side Styling

http://gis.ibbeck.de/ginfo/apps/OLExamples/OL210/MapServer_SLD_World/world_gis_6beta.asp?LAYERS=country&FORMAT=image%2Fpng&VERSION=1.1.1&TRANSPARENT=true&SERVICE=WMS&REQUEST=GetMap&STYLES=continents&EXCEPTIONS=application%2Fvnd.ogc.se_inimage&SRS=EPSG%3A4326&BBOX=0,-90,180,90&WIDTH=256&HEIGHT=256

### Suggested improvements

- NEUBAUER, S., ZIPF, A. (2007): Suggestions for Extending the OGC Styled Layer Descriptor (SLD) Specification into 3D – Towards Visualization Rules for 3D City Models. Proc. Of. Urban Data Management Symposium. UDMS 2007. Stuttgart. Germany, https://www.geog.uni-heidelberg.de/md/chemgeo/geog/gis/3d_sld.udms2007.sn.az.pdf
- RITA, EMANUEL, JOSÉ BORBINHA & BRUNO MARTINS (2010): Extending SLD and SE for Cartograms. https://www.academia.edu/2672094/Extending_SLD_and_SE_for_Cartograms?email_work_card=title [2021-12-10] 
- SAE-TANG, ABSON, ERTZ, OLIVIER (2007). Towards Web Services Dedicated to Thematic Mapping. OSGeo Journal, 3/2007, http://journal.osgeo.org/index.php/journal/article/download/140/106 [2021-12-13] 

# OpenStreetMap Styles

Intro: https://wiki.openstreetmap.org/wiki/MapCSS

Example: https://github.com/gravitystorm/openstreetmap-carto

# Mapnik Style

Explore: https://github.com/mapnik/mapnik/wiki/XMLConfigReference


# Esri's style options


# Carto's CartoCSS

> CartoCSS (short: Carto) is a language for map design. It is similar in syntax to CSS, but builds upon it with specific abilities to filter map data and by providing things like variables. It targets the Mapnik renderer and is able to generate Mapnik XML or a JSON variant of Mapnik XML. It can run from the command line or in the browser by using a bundler like Browserify. (Source: https://cartocss.readthedocs.io/en/latest/)

Explore: https://carto.com/developers/styling/cartocss/


# MapBox Styles

Style specification: https://docs.mapbox.com/mapbox-gl-js/style-spec/

Example (for evaluation, use your browser's built-in developer functionalities): https://api.mapbox.com/styles/v1/mapbox/streets-v11.html?title=true&access_token=pk.eyJ1IjoibWFwYm94IiwiYSI6ImNpejY4M29iazA2Z2gycXA4N2pmbDZmangifQ.-g_vE53SD2WrJ6tFX7QHmA#2.79/2.49/-9.49

# OGC Styles API

The OGC API family of standards, aims to define modular API building blocks to homogenize the integration of location information into any type of application. Furthermore, it is designed to make geospatial data and services FAIR - Findable, Accessible, Interoperable, and Reusable. This is also relevant in the context of styles. As a potential result, the API enables the extensive discovery and querying of datasets and enhances their potential application and impact.

Current draft of the standard: http://docs.opengeospatial.org/DRAFTS/20-009.html


### Examples

Landing Page: https://ogc-api.nrw.de/inspire-us-krankenhaus/v1

Styles Landing Page: https://ogc-api.nrw.de/inspire-us-krankenhaus/v1/styles

Styles Metadata: https://ogc-api.nrw.de/inspire-us-krankenhaus/v1/styles/default/metadata

Style in Mapbox Format (JSON): https://ogc-api.nrw.de/inspire-us-krankenhaus/v1/styles/default?f=mbs

The styled map: https://ogc-api.nrw.de/inspire-us-krankenhaus/v1/styles/default?f=html#8/51.5/7.5

`
{
  "version" : 8,
  "name" : "default",
  "center" : [ 7.5, 51.5 ],  "zoom" : 8.0,   "bearing" : 0.0,  "pitch" : 0.0,
  "sources" : {
    "basemap" : {
      "type" : "raster",
      "tiles" : [ "https://sg.geodatenzentrum.de/wmts_topplus_open/tile/1.0.0/web_grau/default/WEBMERCATOR/{z}/{y}/{x}.png" ],
      "scheme" : "xyz",
      "attribution" : "&copy; <a href=\"http://www.bkg.bund.de\" class=\"link0\" target=\"_new\">Bundesamt f&uuml;r Kartographie und Geod&auml;sie</a> 2017, <a href=\"http://sg.geodatenzentrum.de/web_public/Datenquellen_TopPlus_Open.pdf\" class=\"link0\" target=\"_new\">Datenquellen</a>"
    },
    "krankenhaus" : {
      "type" : "vector",
      "tiles" : [ "https://ogc-api.nrw.de/inspire-us-krankenhaus/v1/collections/governmentalservice/tiles/WebMercatorQuad/{z}/{y}/{x}?f=mvt" ],
      "scheme" : "xyz",      "maxzoom" : 16
    }
  },
  "sprite" : "https://dev.adv-smart.de/sprites/sprite", "glyphs" : "https://dev.adv-smart.de/fonts/{fontstack}/{range}.pbf",
  "layers" : [ {
    "id" : "background",    "type" : "raster",    "source" : "basemap"
  }, {
    "id" : "krankenhaus",   "type" : "symbol", "source" : "krankenhaus",
    "source-layer" : "governmentalservice",
    "layout" : {
      "icon-image" : "Krankenhaus_neu",
      "icon-size" : {
        "stops" : [ [ 11, 1.5 ], [ 14, 2 ], [ 16, 3 ] ]
      },
      "icon-ignore-placement" : true,  "icon-allow-overlap" : false
    },
    "paint" : {
      "icon-halo-width" : 0,      "icon-opacity" : 0.75
    }
  } ]
}
`

# References

- DE LA BEAUJARDIERE J. (2006): OpenGIS Web Map Service (WMS) Implementation Specification. http://portal.opengeospatial.org/files/?artifact_id=14416 [2012-11-21] 
- ANDRAE, C., GRAUL, C., OVER, M. & ZIPF, A. (2011): Web Portrayal Services: OpenGIS Web Map Service, Styled Layer Descriptor, Symbology Encoding und ISO 19117 Portrayal vorgestellt und erläutert. Wichmann Verlag, Berlin/Offenbach
- LUPP, MARKUS (2007): Styled Layer Descriptor profile of the Web Map Service Implementation Specification. http://portal.opengeospatial.org/files/?artifact_id=22364 [2021-12-11]
- MÜLLER, MARKUS (2006): Symbology Encoding Implementation Specification. https://portal.ogc.org/files/?artifact_id=16700 [2021-12-11] 
- PERCIVALL, GEORGE, HOLMES, CHRIS, CHRISTL, ARNULF, GALE, GARY, REED, CARL, LIEBERMAN, JOSH, WESLOH, DAVE, HEAZEL, CHUCK, HERRING, JOHN, SIMONS, SCOTT, DESRUISSEAUX, MARTIN & LATHOWER, BART (2017). OGC® Open Geospatial APIs - White Paper (George Percivall Ed). 10.13140/RG.2.2.25864.42249. http://dx.doi.org/10.13140/RG.2.2.25864.42249
- RITA, EMANUEL, JOSÉ BORBINHA & BRUNO MARTINS (2010): Extending SLD and SE for Cartograms. https://www.academia.edu/2672094/Extending_SLD_and_SE_for_Cartograms?email_work_card=title [2021-12-10] 
- SAE-TANG, ABSON, ERTZ, OLIVIER (2007). Towards Web Services Dedicated to Thematic Mapping. OSGeo Journal, 3/2007, http://journal.osgeo.org/index.php/journal/article/download/140/106 [2021-12-13]
- TZOTSOS, ANGELOS (2021): OGC API Records: Overview and early implementations. https://inspire.ec.europa.eu/sites/default/files/05_angelostzotsos_ogc_api_-_records_-_inspire_2021.pdf
- VRETANOS, P. A. (ed.) (2010a): OpenGIS Web Feature Service 2.0 Interface Standard (also ISO 19142). http://portal.opengeospatial.org/files/?artifact_id=39967 [2012-12-04] 
- VRETANOS, P. A. (2010b): OpenGIS Filter Encoding 2.0 Encoding Standard. http://portal.opengeospatial.org/files/?artifact_id=39968 [2013-01-08] 


