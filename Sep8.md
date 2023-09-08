# **CLASS NOTES** by Taemour Zaidi

### What is a pixel?
- The mosy basic element of an image, a dot on a screen with color and location

### What is resolution?
- Pixels per image. High resolution = more pixels

### What are the main four types of raster images used in computer graphics?
- Indexed images (colors come from color map or color lookup table. Made up on 2 matrices: one for index on the color table, and the color table which stores RGB values)
- Intensity images (grayscale)
- RGB images (each pixel has R, G, B values. True colors)
- Binary images (each pixel is either white [ON] or black [OFF])

Images are usually represented by a matrix or an array.

- *Sampling* means measuring the value of an image at a finite number of points
- *Quantization* is the representation of the measured value at the sampled point by an integer.

## Basic Relationship Between Pixels
When relating the position pf pixels, rather that coordinates like in math, their location is always in relation to a reference point pixel, (x, y). Pixels to the left have (x-1, y). Pixels to the right have (x+1, y). Above is y-1, below is y+1.

So the pixel to the diagonal upper left would have a position (x-1, y-1).

Pixels have 8 neighbors:
- 2 vertical neighbors
- 2 horizontal neighbors
- 4 diagonal neighbors

### Neighbors of a Pixel

Neighborhood relation is used to tell adjascent pixels. It is useful for analyzing regions. 

The 4-Neighborhood relation, notated as $N_4(p)$ for some pixel $p$ has 4 neighbors. 2 vertical, 2 horizontal.
- $N_4(p) = \set{(x-1,y),(x+1,y),(x,y-1), (x,y+1)}$

The 8-Neighborhood relation contains all adjascent pixels surrounding the reference pixel
- Denoted as $N_8(p)$

The Diagonal-beighborhoof relation considers only diagonal neighbor pixels.
- Denoted as $N_D(p)$

### Connectivity
Connectivity is adapted from neighborhood relation

Two pixels ae connected if they are in the same class (i.e. the same color or the same range of intensity) and are neighbors of one another

For $p$ and $q$ from the same class:
- 4-connectivity: $p$ and $q$ are 4-connected if $q \in N_4(p)$
- 8-connectivity: $p$ and $q$ are 8-connected if $q \in N_8(p)$
- mixed-connectivity (m-connectivity): $p$ and $q$ are m-connected if $q \in N_4(p)$ or $q \in N_D(p)$ and $N_4(p) \cap N_4(q) = \empty$

### Adjacency
A pixel $p$ is adjacent to pixel $q$ if they are connected. 

Two image subsets $S_1$ and $S_2$ are connected if some pixel in $S_1$ is adjacent to some pixel in $S_2$

We can define types of adjacency: 4-adjacency, 8-adjacency, and m-adjacency depending on the type of connectivity.