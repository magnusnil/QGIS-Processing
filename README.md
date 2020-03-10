# QGIS-Processing
A collection of Processing models for QGIS 3

Excel file to 2D points.model3
Creates 2D points from coordinates in an excel file. Model output is:
- 2D points

Filter points based on distance from line.model3. 
Filters points based on distance from line. Created in QGIS 3.4.11. Model output is:
- Points 0-1 km from line
- Points 1-5 km from line

Geocode address list.model3
Geocodes an address list, using a separate table from Lantmäteriet. Filter points based on distance from line. Model output is:
- List of geocoded addresses with 2D point geometry
- List of addressess with incorrect information
