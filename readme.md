


# lib_Leaflet

This is the Leaflet Interactive maps for OpenStreatMap for Convertigo



For more technical informations : [documentation](./project.md)

- [Installation](#installation)
- [Mobile Library](#mobile-library)
    - [Shared Components](#shared-components)
        - [LeafletMap](#leafletmap)


## Installation

1. In your Convertigo Studio click on ![](https://github.com/convertigo/convertigo/blob/develop/eclipse-plugin-studio/icons/studio/project_import.gif?raw=true "Import a project in treeview") to import a project in the treeview
2. In the import wizard

   ![](https://github.com/convertigo/convertigo/blob/develop/eclipse-plugin-studio/tomcat/webapps/convertigo/templates/ftl/project_import_wzd.png?raw=true "Import Project")
   
   paste the text below into the `Project remote URL` field:
   <table>
     <tr><td>Usage</td><td>Click the copy button at the end of the line</td></tr>
     <tr><td>To contribute</td><td>

     ```
     lib_Leaflet=https://github.com/convertigo/c8oprj-lib-leaflet.git:branch=8.4.0.0
     ```
     </td></tr>
     <tr><td>To simply use</td><td>

     ```
     lib_Leaflet=https://github.com/convertigo/c8oprj-lib-leaflet/archive/8.4.0.0.zip
     ```
     </td></tr>
    </table>
3. Click the `Finish` button. This will automatically import the __lib_Leaflet__ project


## Mobile Library

Describes the mobile application global properties

### Shared Components

#### LeafletMap

The Leaflet Shared Component. Use this component to add OpenStreetMaps maps to you applications.

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>autoCenter</td><td>Automatically centers map on current GPS position when enabled.
Example value:


```
true
```


</td>
</tr>
<tr>
<td>center</td><td>Map center coordinates used to initialize or recenter the map.
Example value:


```
{ lat: 48.8566, lng: 2.3522 }
```


</td>
</tr>
<tr>
<td>circles</td><td>Circle overlays rendered on the map.
Example value:


```
[{ lat: 48.8566, lng: 2.3522, radius: 1800, tooltip: 'Center', popup: 'Circle example' }]
```


</td>
</tr>
<tr>
<td>disabled</td><td>Disables map interactions (drag/zoom) when enabled.
Example value:


```
false
```


</td>
</tr>
<tr>
<td>geoCodeSearchAddress</td><td>Displays a geocoding search bar on top of the map when enabled.
Example value:


```
true
```


</td>
</tr>
<tr>
<td>layers</td><td>Tile layer definitions rendered as base layers.
Example value:


```
[{ name: 'OpenStreetMap', source: 'https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', options: { maxZoom: 19, attribution: '© OpenStreetMap contributors' } }]
```


</td>
</tr>
<tr>
<td>markers</td><td>Marker overlays rendered on top of base layers.
Example value:


```
[{ lat: 48.85837, lng: 2.294481, options: { title: 'Eiffel Tower' }, tooltip: 'Eiffel Tower', popup: 'Paris preset: Eiffel Tower' }]
```


</td>
</tr>
<tr>
<td>minHeight</td><td>Minimum CSS height applied to the map container.
Example value:


```
'72vh'
```

 or 

```
'480px'
```


</td>
</tr>
<tr>
<td>polygons</td><td>Polygon overlays rendered on the map.
Example value:


```
[{ coord: [[48.8622, 2.3222], [48.8704, 2.3449], [48.8586, 2.3655]], tooltip: 'Area', popup: 'Polygon example' }]
```


</td>
</tr>
<tr>
<td>searchLabel</td><td>Label displayed inside the geosearch input.
Example value:


```
'Search address'
```


</td>
</tr>
<tr>
<td>zoom</td><td>Initial zoom level.
Example value:


```
13
```


</td>
</tr>
</table>

**events**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>GpsCentered</td><td>This event will be emitted when the GPS has be acquired and the map centered on the current GPS position. The parent.out will hold a 


```

{
	lat: nnn,
	lng: mmm
}

```


Object holding the acquired GPS position.

</td>
</tr>
<tr>
<td>MapReady</td><td>This event will be emitted when the map is ready and displayed. The (map) will hold a reference to the underlying leaflet map object so you can use the leaflet Api to interact with it.

</td>
</tr>
</table>



