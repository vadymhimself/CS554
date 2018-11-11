# CS554 Big Data Technology


## Lecture 1 - Aug 23

### Module 1b

#### Distributed system
Distributed computer system - independent coherent system that acts like a single system even though the nodes run on a different computers.

Properties:
* Access transperency: enables local and remote resources to be used identically
* Location transparency
* Mobility transparency
* Performance transparency
* Scaling transparancy
* Failure transparancy


#### Distributed app
```
    Machine A               Machine B               Machine C

+-----------------+    +-----------------+     +----------------+
| +-----------------------------------------------------------+ |
| |                   Distributed application                 | |
| |                                                           | |
| +---------------+----+-----------------+-----+--------------+ |
| +-------------+ |    |                 |     |                |
| |  Middleware | |    |                 |     |                |
| |             | |    |                 |     |                |
| +-------------+ |    |                 |     |                |
| +-------------+ |    | +-------------+ |     | +------------+ |
| |      OS     | |    | |             | |     | |            | |
| |             | |    | |             | |     | |            | |
| +-------------+ |    | +-------------+ |     | +------------+ |
+-----------------+    +-----------------+     +----------------+
```
#### Homework  

Set up azure account for homework #2. Hortonworks Sandbox

## Lecture 2 - Aug 30 (Hadoop)

### Parallel Data Processing System (Big Data Platform)

* Parallel data processing platforms and ecosystems
    * ElasticSearch
       * An open source search engine built on top of Apache Lucene
       * It is Java-based and can search and index document files in diverse formats
    * Apache Hadoop
        * An open source, Java-based programming framework that supports the processing and storage of very large data sets in a distributed computing environment
* Non-relational (NoSQL) distributed database systems
    * Cloud Services
        * Amazon DynamoDB, Azure DocumentDB, Google BigTable
    * Commercial Products
        * MongoDB, Cassandra, Neo4j, Others
* Column-oriented SQL distributed database systems
    * HP Vertica
    * Amazon Redshift
    

### Hadoop

![image](https://user-images.githubusercontent.com/11277453/44885761-46505680-ac88-11e8-9a9b-13d7afa3c432.png)

Data Arhitects - data architecture designers
System Operators - sysadmins of a big data system
Enterprise Data Warehouse - temporary storage

Many tools have developed across Hadoop. 

#### Hadoop Common
The common utilities that provide basic support to other Hadoop modules. 

* Hadoop Distributed File System
    * Enables storage of large amounts of data in redundancy over a cluster of commodity machines, 
* Zookeeper
    * A centralized service for maintaining Hadoop cluster configuration information, naming and providing distributed synchronization
* Hadoop YARN: 
    * A framework that takes care of cluster resource management and job scheduling tasks


![image](https://user-images.githubusercontent.com/11277453/44886169-726cd700-ac8a-11e8-8855-c4fbbb01edc9.png)

![image](https://user-images.githubusercontent.com/11277453/44886313-39813200-ac8b-11e8-8225-8cbfdbc32e7e.png)


#### HDFS

Hadoop works best with a modest number of large files:
* Millions, not billions of files
* Each file of 100MB or more (default block size is 120MB)

![image](https://user-images.githubusercontent.com/11277453/44886718-c6c58600-ac8d-11e8-8b53-a156cc057f0e.png)

### NoSQL Databases
![image](https://user-images.githubusercontent.com/11277453/48310491-ad766b00-e555-11e8-96bf-48883bd40074.png)


