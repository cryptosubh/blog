---
layout: post
title: CS Theory Part II
---


* **Memory Leak**  
A type of resource leak that occurs when a computer program incorrectly manages memory allocations in such a way that memory which is no longer needed is not released
* **Weak Reference**  
A reference that does not protect the referenced object from collection by a garbage collector

* **Latency**  
The amount of time a message takes to traverse a system.  In a computer network, it is an expression of how much time it takes for a packet of data to get from one designated point to another.  A low latency indicates a high network efficiency.

* **Central Processing Unit (CPU)**     
A single CPU can have multiple cores, which allows for task concurrency.
* **Threading**  
Threads run in same memory space
* **Processes**  
Processes run in different memory spaces
* **Thread safe**  
Implementation is guaranteed to be free of race conditions when accessed by multiple threads simultaneously.
* **Concurrency**  
The number of pre-fork worker processes
* **Fork**  
An operation whereby a process creates a copy of itself. When a process calls fork, it is deemed the parent process and the newly created process is its child. After the fork, both processes not only run the same program, but they resume execution as though both had called the system call.
* **Payload**  
The part of transmitted data that is the actual intended message. The payload excludes any headers or metadata sent solely to facilitate payload delivery.


* **Hard Disk/Hard Drive**  
A spindle of magnetic disks that stores files you download, install or save.  Disk drive space on a typical computer is 2TB.  
* **Random Access Memory (RAM)**  
Consists of small chips known as memory modules.  Can be accessed 100s of times faster than a hard drive, which is why active programs such as the operating system are loaded into RAM.  RAM on a typical computer is 16GB.  

**Rabbit**
* **Queue Index**   
Maintains knowledge about where a given message is in a queue, including whether it has been delivered and acknowledged
* **Message Store**  
A key-value store for messages, shared among all queues in the server.  
