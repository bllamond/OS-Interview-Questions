# Operating System Notes

### 1) What is an operating system?

It is a program that provides an interface between the software and hardware of a computer. In other words, an operating system offers an environment for the user to execute software using hardware.

- Your Application do not need interact directy with hardware, Applications talk to the operating system and operating systems talk with the hardware.

---

### 2) Types of operating system?

According to the functionality that operating Systems provides the types are:

- **Single Tasking System**: This OS are very very basic. They do not provide multiple functionality they just exist in Ram. They are loaded in the ram then they allow only one processor to be there in the Ram at a time and to be run at a time.
  
  - Eg: MS-DOC

- **Multitasking**: It is a system that allows more efficient use of computer hardware. This system works on more than one task at one time by rapidly switching between various tasks. These systems are also known as time-sharing systems.


- **Multiprocessing**: It is a system that allows multiple or various processors in a computer to process two or more different portions of the same program simultaneously. It is used to complete more work in a shorter period of time. 


- **Multithreading**: In multithreading you have multiple threads running within a process in interleaved fashion

---

### 3) What is Kernel? Explain the types of kernel.

The kernel is basically a computer program usually considered as a central component or module of OS. It is responsible for handling, managing, and controlling all operations of computer systems and hardware. Whenever the system starts, the kernel is loaded first and remains in the main memory. It also acts as an interface between user applications and hardware.


#### Types of Kernel:

Though there are many types of kernels, only two of them are the most popular:

**Monolithic Kernel**: In this type of OS kernel, all user and kernel services reside in the same memory space. Old operating systems would use this type of kernel. Some examples are Windows 95, 98, and Unix. Linux also uses it.

**MicroKernel**: This kernel type is small, and all the user and kernel services reside in different memory addresses. Operating systems like macOS and Windows use microkernels.

---

### 4) Difference between Kernel and OS?

**Kernel**: Kernel is a system program that controls all programs running on the computer. The kernel is basically a bridge between the software and hardware of the system.

**Operating System**: Operating system is a system program that runs on the computer to provide an interface to the computer user so that they can easily operate on the computer.
