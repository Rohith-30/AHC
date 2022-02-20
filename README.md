# AHC
Have performed Agglomerative Hierarchial Clustering on the **NCI microarray dataset**, wherein the dataset has **64 columns and 6830 rows**.
Each column is an observation, and each row represents a feature. Therefore, the dataset is represented via its transposed data matrix.
The following linkages were used for the AHC: **Single**, **Complete**, **Average** and **Centroid** linkages.
The output is a data structure which represents a dendrogram.
A seperate function is declared, which takes in an argument which will determine the number of clusters required. 
