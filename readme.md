


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
     lib_Leaflet=https://github.com/convertigo/c8oprj-lib-leaflet.git:branch=master
     ```
     </td></tr>
     <tr><td>To simply use</td><td>

     ```
     lib_Leaflet=https://github.com/convertigo/c8oprj-lib-leaflet/archive/master.zip
     ```
     </td></tr>
    </table>
3. Click the `Finish` button. This will automatically import the __lib_Leaflet__ project


## Mobile Library

Describes the mobile application global properties

### Shared Components

#### LeafletMap

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>center</td><td>The map will be centered on this coordinates described by this object
```
{ lat: 46.879966, lng: -121.726909}
```
</td>
</tr>
<tr>
<td>circles</td><td>Add Circles on the map using an array of objects :


```

[
	// Circle #1
	{
		lat: 46.879966,		// lat of the circle center
		lng: -121.726909,	// lng of the circle center
		radius: 5000			// Circle radius
	},
	// Circle #2
	...
]

```


You can add as many circles you want in the array.
</td>
</tr>
<tr>
<td>layers</td><td>The maps will display layers coming for data sources. You can give the layer information here by using an array of objects such as :


```

[
	// layer #1
	{
		name: 'OpenStreetMap',											// Name of the layer source
		source: 'https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png',	// Layer url pattern (here To feed the layer from Open 																											// Street Maps)
		options: {														// Layer options
			maxZoom: 18,
			attribution: '...' 
		}
	},
	// Layer #2
	...
]

```



You can add as many layers you want.</td>
</tr>
<tr>
<td>markers</td><td>Add Markers on the maps using an array of Objects :


```

[
	// Marker #1
	{
		lat: 46.879966,			// lat of marker
		lng: -121.726909,		// lng of Marker
		options: {
			title: 'here'		// All the marker options you can find at https://leafletjs.com/reference.html#marker
		},
		tooltip: 'I am Here',	// The tooltip on the marker
		popup: 'I am Here'		// a Popup displayed over the marker
	},
	// Marker #2
	...
]

```



</td>
</tr>
<tr>
<td>polygons</td><td>Add polygons to the maps using an Array of objects :


```

[
	// Polygon #1
	[
		[ 46.8, -121.85 ],		// Latlng segment #1
		[ 46.92, -121.92 ],		// Latlng segment #2
		[ 46.87, -121.8 ]		// Latlng segment #3
	],
	// Polygon #2
	...
]

```


</td>
</tr>
</table>



