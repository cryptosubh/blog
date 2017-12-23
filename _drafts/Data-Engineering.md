---
layout: post
title: Data Engineering
---

Software engineering is like finance in that there is a lot of jargon and you just have to hang out with people who use the language until it all sinks in.  There will probably come a time when words like *throughput* and *atomicity* feel obvious to me, but for now they just feel really unnatural.  I pretty much look up *throughput* every time I read it (or hear it).  

Vocab and definitions come from *Designing Data-Intensive Applications* by Martin Kleppmann. 

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
A system that can anticipate faults and prevent them from causing failures
* **scalability**  
The ability for a system to support growth in data volume, traffic volume, and complexity
* **throughput**  
The number of records we can process per second, or the total time it takes to run a job on a dataset of a certain size.  Mostly relevant when discussing batch processes.
* **response time**  
The time between a client sending a request and receiving a response (i.e. service time)
* **latency**  
The duration that a request is waiting to be handled (i.e., during which it is latent)
* **tail latency amplification**  
If a single user request makes multiple server calls in parallel, it only takes one slow call to make the entire request slow.
* **scaling up** or **vertical scaling**  
Moving to a more powerful machine
* **scaling out** or **horizontal scaling** or **shared-nothing architecture**  
Distributing the load to multiple machines
* **maintainability**  
The ability for others to keep up and adapt the system


#### Chapter 2: Data Models and Query Languages
* **NoSQL**  
Stands for Not Only SQL
* **polyglot persistence**  
The idea that different applications have different requirements, so that relational as well as non-relational databases will continue to both be important for the foreseeable future
* **normalization**  
Removing duplication for a database to decrease write overhead and reduce the risk of inconsistencies. 
* **storage locality**  
The opposite of normalization, when relevant data is split across multiple tables. 
* **document model** 
A model with good locality and less normalization.  Examples: JSON, XML.
* **schema-on-read**  
Schema is implicit in the data, and is only interpreted once the data is read.  Schema is not defined or enforced by the database.
* **schema-on-write**  
Schema is explicitly defined and enforced by the database
* **imperative language**  
A language in which you specify which operations to perform, and in which order
* **declarative language**   
A language in which you specify the pattern of data you want, but not how to procure that data.  Examples: SQL, CSS
* **Triple-Stores**  
A model in which all information is stored as (subject, predicate, object)

#### Chapter 3: Storage and Retrieval
* **log**  
Append-only data file (sequence of records)
* **log-structured storage engine**  
* **compaction**  
The process of throwing away duplicate keys in the log, and only keeping the most recent update for each key in order to conserve disk space
* **solid state drives** or **SSDs**
* **Sorted String Table** or **SSTable**  
Each log-structured storage segment of key-value pairs is sorted by key
* **memtable**  
* **Log-Structured Merge-Tree** or **LSM-Tree**
* **Bloom filters**  
* **write amplification**  
* **B-Tree**  
* **blocks** or **pages**  
* **branching factor**  
* **write-ahead log** or **WAL** or **redo log**  
* **latches**  
* **page-oriented storage engine**  
* **online transaction processing** or **OLTP**  
* **online analytical processing** or **OLAP**  
* **data warehouse** 
* **Extract-Transform-Load** or **ETL**  
* **star schema** or **dimensional modeling**
* **fact table**
* **dimension tables** 
* **snowflake schema** 
* **row-oriented**
* **column-oriented storage**
* **bitmap encoding**
* **materialized view** 
* **data cube** or **OLAP cube** 
