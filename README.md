DBSCAN (Density-Based Spatial Clustering of Applications with Noise) is an unsupervised machine learning algorithm that is highly effective for outlier detection and clustering in datasets with arbitrary shapes. While it is commonly used for spatial data, it can also be applied to time series analysis for detecting anomalies and removing outliers.
Applying DBSCAN for Outlier Detection

DBSCAN groups dense regions of data into clusters while treating sparse points as outliers (noise points).
The two key parameters:
eps: Defines the neighborhood radius around a point.
min_samples: The minimum number of points required to form a dense cluster.
Any point not belonging to any cluster is considered an outlier, which can indicate an anomalous event in the time series. These anomolous points are marked as red in the graph output.
