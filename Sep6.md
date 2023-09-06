# **CLASS NOTES** by Taemour Zaidi

## Early Graphics Systems
In the early days of computer graphics, computers were so slow that refreshing even simple images, containing a few hundreds of line segments, would burden even expensive computers

CRTs had only the basic capability to generate line segments connecting 2 points. An issue was that if the picture changed, the whole picture had to be redrawn.

Earliest attempts to buld a special purpose graphics system were concerned primarily with relieving the task of refreshing the display.

**Display processors:**
- Standard architecture with capabilities to display primitives (primitives are basic shapes or polygons)
- compositions made at the host
- memory-display list: contains primitives to be displayed

### Graphics pipeline
