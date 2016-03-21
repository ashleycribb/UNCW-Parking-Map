fusion-point-polygon-list
========================
Searchable point and polygon layer map template, with sortable list results, using Google Maps and Fusion Tables

Use this template if you wish to create a Search-and-Filter map that turns on/off at least 2 layers (points and polygons), displays results in a sortable list, and draws data from Google Fusion Tables. The default point map displays a textual legend (A, B, C), with option to switch to numeric (0-100) values. Also, thematic polygon layers may be turned on/off in the background. Based on template customized by Derek Eder http://derekeder.com/searchable_map_template/

##Demos
Toggle display between map view and sortable list view
- http://ashleycribb.github.io/UNCW-Parking-Map/

Display both map view and sortable list
- http://jackdougherty.github.io/fusion-point-polygon-list/index_both.html


See tutorial in Fusion Tables template section of  *Data Visualization for All* book at http://DataVizForAll.org

General steps:

1) Use Google Fusion Tables to create your point layer (all types in one table), and set the feature styles (set ranges, colors, etc.) and info windows.

2) Use Google Fusion Tables to create your polygon layers (each layer in its own table), and set feature styles (thematic shading, etc.) and info windows

3) Make your own copy of this template: either Fork to your own GitHub account, or Clone in Desktop, or Download a ZIP compressed version to your desktop.

4) Modify two files, following instructions in the code comments, to match your Google Fusion Tables:

- index.html (to toggle between map and sortable list) or index_both.html (to display both at same time)
- maps_lib.js (located inside the js folder)


