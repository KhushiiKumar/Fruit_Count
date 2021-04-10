# Fruit_Count
Calculates the frequency of "Apple", "Banana" and "Grapes" from the input file through MapReduce program.


## Map Reduce
MapReduce is a programming model and an associated implementation for processing and generating big data sets with a parallel, distributed algorithm on a cluster.
A MapReduce program comprises of :  

**Map procedure:** Performs filtering and sorting.  

**Reduce method:** Performs a summary operation.  


**Driver Class**  
Driver class is the main class which controls the execution of the program. Here we create a Job object and set the driver, mapper, and reducer class used in our program.  


**Mapper Class**  
Any mapper class for a MapReduce program extends the abstract Mapper class. And then we have to override the map function, which takes the key-value pair and reference to a Context variable, which is them handled by the reduce function.  


**Reducer Class**  
Reducer class for a MapReduce program extends the abstract class Reducer. The reduce method is to be overridden in this class.


