
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

Leaflet map page
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
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompvariable_16x16.png?raw=true "  alt="UICompVariable" >&nbsp;autoCenter
</td>
<td>
Automatically centers map on current GPS position when enabled.
Example value:


```
true
```



</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompvariable_16x16.png?raw=true "  alt="UICompVariable" >&nbsp;center
</td>
<td>
Map center coordinates used to initialize or recenter the map.
Example value:


```
{ lat: 48.8566, lng: 2.3522 }
```



</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompvariable_16x16.png?raw=true "  alt="UICompVariable" >&nbsp;circles
</td>
<td>
Circle overlays rendered on the map.
Example value:


```
[{ lat: 48.8566, lng: 2.3522, radius: 1800, tooltip: 'Center', popup: 'Circle example' }]
```



</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompvariable_16x16.png?raw=true "  alt="UICompVariable" >&nbsp;disabled
</td>
<td>
Disables map interactions (drag/zoom) when enabled.
Example value:


```
false
```



</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompvariable_16x16.png?raw=true "  alt="UICompVariable" >&nbsp;geoCodeSearchAddress
</td>
<td>
Displays a geocoding search bar on top of the map when enabled.
Example value:


```
true
```



</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompvariable_16x16.png?raw=true "  alt="UICompVariable" >&nbsp;layers
</td>
<td>
Tile layer definitions rendered as base layers.
Example value:


```
[{ name: 'OpenStreetMap', source: 'https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', options: { maxZoom: 19, attribution: '© OpenStreetMap contributors' } }]
```



</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompvariable_16x16.png?raw=true "  alt="UICompVariable" >&nbsp;markers
</td>
<td>
Marker overlays rendered on top of base layers.
Example value:


```
[{ lat: 48.85837, lng: 2.294481, options: { title: 'Eiffel Tower' }, tooltip: 'Eiffel Tower', popup: 'Paris preset: Eiffel Tower' }]
```



</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompvariable_16x16.png?raw=true "  alt="UICompVariable" >&nbsp;minHeight
</td>
<td>
Minimum CSS height applied to the map container.
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
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompvariable_16x16.png?raw=true "  alt="UICompVariable" >&nbsp;polygons
</td>
<td>
Polygon overlays rendered on the map.
Example value:


```
[{ coord: [[48.8622, 2.3222], [48.8704, 2.3449], [48.8586, 2.3655]], tooltip: 'Area', popup: 'Polygon example' }]
```



</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompvariable_16x16.png?raw=true "  alt="UICompVariable" >&nbsp;searchLabel
</td>
<td>
Label displayed inside the geosearch input.
Example value:


```
'Search address'
```



</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompvariable_16x16.png?raw=true "  alt="UICompVariable" >&nbsp;zoom
</td>
<td>
Initial zoom level.
Example value:


```
13
```



</td>
</tr>
</table>


<span style="color:DarkGoldenRod">Events</span>

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
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompevent_16x16.png?raw=true "  alt="UICompEvent" >&nbsp;GpsCentered
</td>
<td>
This event will be emitted when the GPS has be acquired and the map centered on the current GPS position. The parent.out will hold a 


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
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompevent_16x16.png?raw=true "  alt="UICompEvent" >&nbsp;MapReady
</td>
<td>
This event will be emitted when the map is ready and displayed. The (map) will hold a reference to the underlying leaflet map object so you can use the leaflet Api to interact with it.


</td>
</tr>
</table>

</p></blockquote></details>
</p></blockquote></details>
