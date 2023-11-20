# DBSCAN
Visualizing density-based clustering on a synthetic dataset
Three clusters are defined with specific centroids, synthetic dataset with 400 samples is generated using make_blobs with these centroids and a standard deviation of 0.5 for each cluster.
The DBSCAN algorithm is applied to the normalized dataset and the parameters used are an epsilon value of 0.4, specifying the maximum distance between two samples for one to be considered as in the neighborhood of the other, and a minimum number of samples set to 20.
The fitted DBSCAN model is used to predict cluster labels for each data point in the dataset.

![image](https://github.com/KshitijShresth29/DBSCAN/assets/145615126/7a6075b4-b037-4d74-964d-842f4b42e2eb)

Another scatter plot is created to visualize the dataset with points colored according to the clusters assigned by DBSCAN:

![image](https://github.com/KshitijShresth29/DBSCAN/assets/145615126/7698395e-b263-4343-8216-2583f26088a6)




