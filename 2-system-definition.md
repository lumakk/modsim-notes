# System Definition 

## System Classifications

* **Discrete systems** - changing values of certain states at some discrete point of time where the events occur.
* **Continuous event systems** - means that the status of some component in the system is continuously changing with respect to time. 
* **Terminating simulation** - is one in which the simulation starts at a defined state or time and ends when it reaches some other defined state or time. 
* **Nonterminating or ready-state simulation** - means that the simulation never ends nor does it mean that the system being simulated has no eventual termination. 

## High-level Flowchart

**Flowcharts** - graphically depicts how the major components and events interact. It also illustrates how the input and output data play a role in the model. Standard Flowchar symbols include:
* **Oval** - used to define the start and end processes 
* **Rectangle** - used to represent general-purpose processes that are not specifically covered by any of the other flow chart symbols.
* **Tilted Parallelogram** - used for processes that involve some sort of input our output. 
* **Diamond** - used to represent a decision in the flow chart logic.

## Processes and Events 

A **Process** is a series of steps and decisions in the way work is completed. 

An **Event** is an important happening, especially one that is out of and related to previous happenings. 

A **Queuing procedure** occurs to give way to one event or process to be finshed first. **Queuing** can be either **parallel** or **single snake.**
* **Parallel queues** are found in systems that have multiple server resources while **single snake** queues is often used to model complex systems. 
* **Queue priority** - means that the order of entities in the queue may change according to the priority scheme:
    * **First-In, First-Out (FIFO)**
    * **Last-In, Last-Out (LIFO)**
    * **Shortest Processing Time (SPT)**
    * **longest Processing Time (LPT)**
    * **Lowest Value First (LVF)**
    * **Highest Value First (HVF)**
    * **User-Defined Rules**

* **Queue entity** behavior involves the actions of the **entities** with respect to entering and remaining in the system queues.
    * **Balking** - occurs when a customer enters the system but leaves **before entering a queue**
    * **Reneging** - is when an entity enters the line but leaves **before being processed**
    * **Jockeying** - is associated only with parallel queues. This is when an entity **switches between two different queues.**  

## Data to be Included in the Model 


