---
layout: post
title: Data Engineering
---

Data engineering is like finance in that there is a lot of jargon and you just have to hang out with people who use the language until it all sinks in.  There will probably come a time when words like *throughput* and *atomicity* feel obvious to me, but for now they just feel really unnatural.  I pretty much look up *throughput* every time I read it (or hear it).  

Here's my cheat sheet.  Vocab and definitions come from *Designing Data-Intensive Applications* by Martin Kleppman. 

#### Chapter 1: Reliable, Scalable, Maintainable Applications
* **data-intensive**  
An application where a limiting factor is the amount and complexity of the data it uses.  Compare to **compute-intensive** applications, where the limiting factor is CPU power.
* **data systems**
Examples: databases, caches, search indexes, message queues
* **reliability**  
The ability for a system to work correctly, even in the face of software/hardware faults and human errors
* **fault**  
When one component of the system deviates from the spec
* **failure**   
When the system as a whole stops providing the required service to users
* **fault-tolerant** or **resilient**  
A system that can anticipate faults and prevent them from causing failutres
* **scalability**  
The ability for a system to support growth in data volume, traffic volume and complexity
* **throughput** 
The number of records we can process per second, or the total time it takes to run a job on a dataset of a certain size.  Mostly relevant when discussing batch processes.
* **response time** 
The time between a client sending a request and receiving a response (i.e. service time)
* **latency**  
The duration that a request is waiting to be handled (i.e., during which it is latent)
* **tail latency amplification**  
If a single user request makes multiple server calls in parallel, it only takes one call to make the entire request slow.
* **scaling up** or **vertical scaling**  
Moving to a more powerful machine
* **scaling out** or **horizontal scaling** or **shared-nothing architecture**  
Distributing the load to multiple machines
* **maintainability**  
The ability for others to keep up and adapt the system


#### Chapter 2: Data Models and Query Languages
* **NoSQL**  
Stands for Not Only SQL
* **storage locality**  
* **normalization** 
* **schema-on-read**  
* **schema-on-write**  
* **declarative**   
* **imperative**  


