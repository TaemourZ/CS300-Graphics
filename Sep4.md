# **CLASS NOTES** by Taemour Zaidi

**Question: What is a computer system?:**
It is a combination of hardware and software. In its most basic form, a computer system is a programmable electronic device that can accept input; store data; and retrieve, process and output information.

## Computer systems and Graphics systems

Computer system has 4 main components:
- Input devices
- Processor (CPU)
- Memory
- Output devices

## Graphics system
Graphics systems has 5 components:
- Input devices
- Processor (GPU)
- Memory
- Frame buffer
- Output devices

**How it works:**
- A picture is produced as an array (raster) of picture elements (pixels)
- These pixels are collectively stores in the frame buffer
- Properties of frame buffer:
    - Resolution: number of picels in the frame buffer
    - Depth or Precision: number of bits used for each pixel
        - For example: a 1-bit deep frame buffer allows 2 colors, while an 8-bit deep frame buffer allows 256 colors
    - A frame buffer is implemented either with special types of memory chips or it can be a part of system memory
    - In simple systems, the CPU does both normal and graphical processing
- **Graphics processing:** Take specifications of graphical primitives from application program and assign values to pixels in the frame buffer
    - AKA **Rasterization** or scan conversion.

## CPU vs GPU
The CPU handles all the tasks required for all software on the server to run correctly. A GPU, on the other hand, supports the CPU to perform concurrent calculations. A GPU can complete simple and repetitive tasks much faster because it can break the task down into smaller components and finish them in parallel.

GPUs have many more cores than CPUs, although they are smaller. With the additional cores, GPUs can handle many more mathematical and geographical calculations at once with greater efficiency, whereas CPUs are more restricted due to the fact it is a more “generalist” component.

The main difference between the two is GPUs are specialized for graphics

CPUs and GPUs have *cores*. Cores are capable of running a single task at a time (not really, but just for simplicity sake).

### CPU
- Generalist component: Handles main processing functions of a computer
- Core count: 2 to 64 (most CPUs)
- Runs processes serially
- Better at processing one big task at a time

### GPU
- Specialized component: Handles graphic and video rendering
- Core count: Thousands
- Runs processes in parallel
- Better at processing several smaller tasks at a time

## Early Graphics Systems
In the early days of computer graphics, computers were so slow that refreshing even simple images, containing a few hundreds of line segments, would burden even expensive computers

CRTs had only the basic capability to generate line segments connecting 2 points. An issue was that if the picture changed, the whole picture had to be redrawn.

Earliest attempts to buld a special purpose graphics system were concerned primarily with relieving the task of refreshing the display.

**Display processors:**
- Standard architecture with capabilities to display orimitives
- compositions made at the host
