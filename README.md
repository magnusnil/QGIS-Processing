# QGIS-Processing

## Table of contents
* [General info](#general-info)
* [Excel file to 2D points](#excel-file-to-2D-points)
* [Filter points based on distance from line](#filter-points-based-on-distance-from-line)
* [Geocode address list](#geocode-address-list)
* [Write to PostGIS](#write-to-postgis)
<br/>

## General info
A collection of Processing models for QGIS 3
<br/><br/>

## Excel file to 2D points
Creates 2D points from coordinates in an excel file. Model output is:
- 2D points
<br/>

## Filter points based on distance from line
Filters points based on distance from line. Created in QGIS 3.18.1. Model output is:
- Points 0-1 km from line
- Points 1-5 km from line

![Image description](https://github.com/magnusnil/QGIS-Processing/blob/master/Filter%20points%20based%20on%20distance%20from%20line.JPG)

<br/>

## Geocode address list
Geocodes an address list, using a separate table from Lantmäteriet. Created in QGIS 3.18.1. Model output is:
- List of geocoded addresses with 2D point geometry
- List of addresses with incorrect information

![Image description](https://github.com/magnusnil/QGIS-Processing/blob/master/Geocode%20address%20list.JPG)

<br/>

## Write to PostGIS
Manages attributes, filter features and writes the output to PostGIS. Created in QGIS 3.18.1. Model output is:
- A new table in PostGIS

![Image description](https://github.com/magnusnil/QGIS-Processing/blob/master/Write%20to%20PostGIS.JPG)
