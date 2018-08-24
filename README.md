# CS554 Big Data Technology


## Lecutre 1 - Aug 23

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

