# Systems-Programming

Includes key features like:

- Memory management: Implementing concepts like paging, segmentation, and virtual memory.
- Process management: Creating, scheduling, and managing processes.
- File systems: Implementing file systems, managing files and directories.
- Inter-process communication: Implementing communication between processes using methods like pipes, message queues, shared memory, etc.
- Device management: Writing device drivers, managing I/O devices.

1. main.c: This code is to enhance an image's contrast through histogram equalization and then detect edges using the Sobel operator, utilizing parallel processing to speed up the computation. The program is intended to work on systems with multiple processors, distributing the workload among them and combining the results at the end. Program produces two output images: 
- histeql.pgm: The histogram-equalized grayscale image. 
- final.pgm: The image after applying the Sobel operator, showing the edges detected.

2. Demand_Paging: Demand paging, a method of managing computer memory in operating systems. The README.md file in this directory should provide more details.

3. File_System: Two subdirectories, iNode_Implementation and LinkedList_Implementation, which contain implementations of a file system using iNodes and linked lists respectively.

4. Job_Scheduler: CPU scheduling, a process by which a computer system determines which process should access the CPU. The README.md and Documentation.md files in this directory should provide more details.

5. LKM: Loadable Kernel Modules (LKM), which are object files that contain code to extend the running kernel of an operating system.

6. SHM_Shell: Shared memory and shell programming.

The README.md and Documentation.md files in each directory should provide more details.
