# Composite-files-Candidates-Identification
Existing systems provided the one-to-one mapping of logical files to physical metadata. A new approach,proposed
composite-file file system with the technique of many-to-one mapping and explored different mapping strategies by studying
the metadata of the files.

As an extension of the compositefile file system, this work mainly aims at extending the existing work and thereby exploring different strategies to combine files(cluster) together. 

I have implemented the composite file-file system using the directory-based strategy, time-based strategy, and session-based strategies.I have explored those strategies by grouping them together using both frequent mining techniques
and clustering techniques. 
FP-Growth algorithm and dynamic hashing and pruning based Apriori helped us to realize files accessed as transactions whereas the clustering algorithms like the K-Means and Hierarchical Agglomerative Clustering helped us realize them as clusters. By using different approaches to clustering the files, we could have more data to do benchmark testing on Log and Web Log data. 

The clusters and transactions have been evaluated by using a testing benchmark in the experimentation phase and we have considered different workloads to infer the results.
