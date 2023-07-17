# Resilient Distributed Dataset
https://www.bigdatainrealworld.com/what-is-rdd/

#### RDD is a fault tolerant collection of elements that can be parallelized (can be made to operated on in parallel). THe elements of RDD can be operated on in parallel



#### 3 methods for creating RDD:
##### - Parallelizing an existing collection
###### Caution: When RDDs are created, a direct acyclic graph (DAG) is created. This is called transformations.Transformations return a pointer to the RDD created and actions return values coming from the actions.
##### - Referencing a dataset
##### - Transformation a dataset

#### 2 types of RDD operations:
##### - Transformations
##### - Actions
