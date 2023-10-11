# **CLASS NOTES** by Taemour Zaidi


## Polygon Filling
**Polygons:** a chain of connected line segments

In order to fill a polygon:
- Find all pixels in the polygon (interior)
- Fill the pixels with the specified color

Two basic approaches to area fillingL
- Scan-line
- Boundary fill

## Scan-file Fill Algorithm
1. Find the intersections of the scan-line with all edges of the polygon
2. Sort the intersections from left to right
3. Make pairs of the intersections
4. Fill the pixels inside the pair with the specified color

**Inside-Outside Tests:** Draw a line from any position (P) to a distance point outside the coordinate extents, and count the # of edges crossing the line. if this number is odd, then P is interior. Else, P is exterior.