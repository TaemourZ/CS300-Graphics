# **CLASS NOTES** by Taemour Zaidi

## Early Graphics Systems
In the early days of computer graphics, computers were so slow that refreshing even simple images, containing a few hundreds of line segments, would burden even expensive computers

CRTs had only the basic capability to generate line segments connecting 2 points. An issue was that if the picture changed, the whole picture had to be redrawn.

Earliest attempts to buld a special purpose graphics system were concerned primarily with relieving the task of refreshing the display.

**Display processors:**
- Standard architecture with capabilities to display primitives (primitives are basic shapes or polygons)
- compositions made at the host
- memory-display list: contains primitives to be displayed

## Graphics pipeline
A graphics pipeline is a sequence of steps used to render 3D objects to a 2D image in computer graphics. Input is vertices, output is pixels.

There are 4 major steps in the geometric pipeline:
- Vertex processing
- Clipping & Primitive Assembler
- Rasterization
- Fragment processing

### Vertex Processing
- Access each vertex individually
- Perform any necessary transformations
- Compute colors and attributes

### Primitive Assembler
- How do we process the vertex data?
    - Points
    - Lines
    - Triangles

### Clipper
- Remove those parts that are out of the viewing field

### Rasterizer
- Creates a set of fragments (set of pixels that make up an object)
- depth of the pixel
- color and location

### Fragment Processor
- hidden surface removal
- texture mapping
- sends result to frame buffer



