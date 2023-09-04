# **CLASS NOTES** by Taemour Zaidi

### Question: What is a computer system?
It is a combination of hardware and software

Computer system has 4 main components:
- Input devices
- Output devices
- Memory
- Processing unit (CPU)

Graphics systems has 5 components:
- input devices
- output devices
- memory
- Processing unit (GPU)
- Memory buffer

### CPU vs GPU
The CPU handles all the tasks required for all software on the server to run correctly. A GPU, on the other hand, supports the CPU to perform concurrent calculations. A GPU can complete simple and repetitive tasks much faster because it can break the task down into smaller components and finish them in parallel.

GPUs have many more cores than CPUs, although they are smaller. With the additional cores, GPUs can handle many more mathematical and geographical calculations at once with greater efficiency, whereas CPUs are more restricted due to the fact it is a more “generalist” component.

The main difference between the two is GPUs are specialized for graphics

CPUs and GPUs have *cores*. Cores are capable of running a single task at a time (not really, but just for simplicity sake). CPUs tend to run tasks in a serial manner. GPUs run tasks in parallel.

### CPU
- Generalist component: Handles main processing functions of a computer
- Core count: 2-64 (most CPUs)
- Runs processes serially
- Better at processing one big task at a time

### GPU
- Specialized component: Handles graphic and video rendering
- Core count: Thousands
- Runs processes in parallel
- Better at processing several smaller tasks at a time