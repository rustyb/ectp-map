## ArcGIS Tutorial 

The aim of this tutorial is to demonstrate the application of three common tools present in any GIS system.

The tutorial provides step by step instructions which can be followed to complete the tasks.

### Goals
1. Understand how to load shapefiles in ArcGIS and join with tabular data in order to perform geosptaial analysis. 
2. Create spatial query on joined data to display only features with a certain attribute. 
3. Use the buffer tool to create buffers surrounding lines and points, and subsequently use these buffers to select polygons located within.
4. TBC

### Software
- ArcGIS 10.1

### Tutorial Data

- Dublin City Council Planning Applications shapes 2003-2012 [(Dublinked)](http://dublinked.com/datastore/datasets/dataset-303.php)
- Luas Line Alignments and Stations [(Dublinked)](http://dublinked.com/datastore/datasets/dataset-301.php)
- Dublin Bus Route Alignments [(Dublinked)](http://dublinked.com/datastore/datasets/dataset-258.php)

### Loading your Data
In this example we will be using data from Dublin, Ireland on the location of sites which planning applications have been made in the last 10 years. There are a number of files in the download which include a shapefile which identifies the polygons which show the site boundary of the applications and a number of tables which contain attributes relating to the applications - such as date lodged, the decision made, when this decision was made and both short and long descriptions of the proposed developments.

Two light rail lines were built in Dublin in the last 10 years. As a transport planner we would like to know how many applications were granted for change of use and new developments within 500 meteres of the stations (stops) on these new light rail lines.
