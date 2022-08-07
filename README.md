One of the standard problems in information retrieval is the nearest-neighbor problem: given an object and a database, quickly retrieve the k-most similar objects to the query from the database. A naive implementation would require one to linearly scan through the entire database, which is typically too costly for online applications. Two common approaches that have been suggested for this problem are locality-sensitive hashing and k-d-trees. Both may be viewed as data structures / algorithms for finding an approximate nearest neighbor to a query. Other approaches such as R-trees exist. In this project, you we implement these two techniques, and test them using the CIFAR10 dataset. The performance of these approaches is compared in terms of speed and accuracy.
