# Georegistration or Georeferencing
 Python based implementation

Image data can be obtained from various sources, like satellite, aerial cameras, and maps.
However, the spatial reference information in such image data is not typically available.
So, we need to convert image data into real-world data means we need to georeference
this image data to a map coordinate system. As we know that a map coordinate system
is a method by which the earth's curved surface is portrayed on a 
at surface. 

When our image data is georeferenced, we describe its position using map coordinates and assign
the map frame's coordinate system. In this, we are going to learn how to georeference an
image data using ground control points. The focal length of a nearly vertical photograph
is given. Photo coordinate in image coordinate system and ground coordinate is given for
five points. We are interested in knowing the extrinsic parameter using the collinearity
condition.