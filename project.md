
# ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/core/images/project_color_16x16.png?raw=true "Project") lib_Leaflet

This is the Leaflet Interactive maps for OpenStreatMap for Convertigo


<details><summary><span style="color:DarkGoldenRod"><i>Connectors</i></span></summary><blockquote><p>


## ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/connectors/images/sqlconnector_color_16x16.png?raw=true "SqlConnector") void

void connector, replace or don't use it

<details><summary><span style="color:DarkGoldenRod"><i>Transactions</i></span></summary><blockquote><p>


### ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/transactions/images/sqltransaction_color_16x16.png?raw=true "SqlTransaction") void

does nothing
</p></blockquote></details>
</p></blockquote></details>

<details><summary><span style="color:DarkGoldenRod"><i>Mobile Application</i></span></summary><blockquote><p>


## ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/core/images/mobileapplication_color_16x16.png?raw=true "MobileApplication") Application

Describes the mobile application global properties

<details><summary><span style="color:DarkGoldenRod"><i>Pages</i></span></summary><blockquote><p>


### ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/pagecomponent_color_16x16.png?raw=true "PageComponent") Page

My First Page as root page
</p></blockquote></details>

<details><summary><span style="color:DarkGoldenRod"><i>Shared Components</i></span></summary><blockquote><p>


### ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uisharedcomponent_16x16.png?raw=true "UISharedRegularComponent") LeafletMap

The Leaflet Shared Component. Use this component to add OpenStreetMaps maps to you applications.

<span style="color:DarkGoldenRod">Variables</span>

<table>
<tr>
<th>
name
</th>
<th>
comment
</th>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompvariable_16x16.png?raw=true "  alt="UICompVariable" >&nbsp;center
</td>
<td>
The map will be centered on this coordinates described by this object


```

{ lat: 46.879966, lng: -121.726909}

```



</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompvariable_16x16.png?raw=true "  alt="UICompVariable" >&nbsp;circles
</td>
<td>
Add Circles on the map using an array of objects :


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
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompvariable_16x16.png?raw=true "  alt="UICompVariable" >&nbsp;layers
</td>
<td>
The maps will display layers coming for data sources. You can give the layer information here by using an array of objects such as :


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



You can add as many layers you want.
</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompvariable_16x16.png?raw=true "  alt="UICompVariable" >&nbsp;markers
</td>
<td>
Add Markers on the maps using an array of Objects :


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
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompvariable_16x16.png?raw=true "  alt="UICompVariable" >&nbsp;polygons
</td>
<td>
Add polygons to the maps using an Array of objects :


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
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompvariable_16x16.png?raw=true "  alt="UICompVariable" >&nbsp;zoom
</td>
<td>
Zoom factor
</td>
</tr>
</table>

</p></blockquote></details>
</p></blockquote></details>
