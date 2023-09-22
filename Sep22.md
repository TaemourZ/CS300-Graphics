# **CLASS NOTES** by Taemour Zaidi

What are primitives:
-   A primitive is a low level object or operation from which higher-level, more complex objects and operations can be constructed. 
- In graphics, primitives are basic elements, such as lines, curves, and polygons, which can be combined to create more complex graphical images.

Two algorithms for drawing lines between two points: DDA and Bresenham's. 

## Digital Differential Analyzer (DDA)
**DDA** is a line drawing algorithm used in computer graphics to generate a line segment between two specified endpoints. It is a simple and efficient algorithm that works by using the incremental difference between the x-coordinates and y-coordinates of the two endpoints to plot the line.

The steps involved in DDA line generation algorithm are:

- Input the two endpoints of the line segment, $(x1,y1)$ and $(x2,y2)$.
- Calculate the difference between the x-coordinates and y-coordinates of the endpoints as $dx$ and $dy$ respectively.
- Calculate the slope of the line as $m = dy/dx$.
- Set the initial point of the line as $(x1,y1)$.
- Loop through the x-coordinates of the line, incrementing by one each time, and calculate the corresponding y-coordinate using the equation $y = y1 + m(x – x1)$.
- Plot the pixel at the calculated $(x,y)$ coordinate.
- Repeat steps 5 and 6 until the endpoint $(x2,y2)$ is reached.

DDA algorithm is relatively easy to implement and is computationally efficient, making it suitable for real-time applications. However, it has some limitations, such as the inability to handle vertical lines and the need for floating-point arithmetic, which can be slow on some systems. Nonetheless, it remains a popular choice for generating lines in computer graphics.

| Advantages | Disadvantages |
| :--- | :--- |
| It is a simple and easy-to-implement algorithm. | It deals with the rounding off operation and floating point arithmetic so it has high time complexity.|
| It avoids using multiple operations which have high time complexities. | As it is orientation-dependent, so it has poor endpoint accuracy. |
| It is faster than the direct use of the line equation because it does not use any floating point multiplication and it calculates points on the line. | Due to the limited precision in the floating point representation, it produces a cumulative error. |

## Uses of DDA Algorithm: 

1. **Creating basic graphics primitives:** DDA algorithm can be used to draw simple shapes such as lines, polygons, and rectangles. By using a series of line segments generated using DDA, more complex shapes can also be created.
1. **Computer-aided design (CAD):** In CAD software, DDA algorithm is used to draw lines between two points, which are used to create 2D and 3D models.
1. **Image processing:** DDA algorithm can be used in image processing for tasks such as edge detection and image segmentation.
1. **Video game development:** DDA algorithm is used for rendering lines and polygons in real-time graphics rendering for video games.
1. **Simulation and modeling:** DDA algorithm is used to simulate physical phenomena such as ray tracing, which is used in computer graphics to create realistic images of 3D objects.

## Issues in DDA Algorithm: 

1. **Floating point arithmetic:** The DDA algorithm requires floating-point arithmetic, which can be slow on some systems. This can be a problem when dealing with large datasets.
1. **Limited precision:** The use of floating-point arithmetic can lead to limited precision in some cases, especially when the slope of the line is very steep or shallow.
1. **Round-off errors:** Round-off errors can occur during calculations, which can lead to inaccuracies in the generated line. This is particularly true when the slope of the line is close to 1.
1. **Inability to handle vertical lines:** The DDA algorithm is unable to handle vertical lines, as the slope becomes undefined.
1. **Slow for complex curves:** The DDA algorithm is not suitable for generating complex curves such as circles and ellipses, as it requires a large number of line segments to approximate these curves accurately.
1. **Aliasing:** Aliasing occurs when the line segments generated using the DDA algorithm do not accurately represent the line being drawn, resulting in a jagged appearance.
1. **Not suitable for thick lines:** The DDA algorithm generates thin lines, which can be problematic when drawing thick lines, as the line segments may overlap or leave gaps.
