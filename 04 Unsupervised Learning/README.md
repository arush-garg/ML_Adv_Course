# Unsupervised Learning - Clustering

Unsupervised learning is when a model is expected to learn from data that does not have labels. This is particularly useful for scenarios like customer analysis and fraud/anomaly detection.
<br>
<br>
The way clustering works is by first choosing k random points in the n-dimensional feature space. Then, the distance from each data point is calculated and each data point is assigned to the closest cluster. Finally, each cluster is updated to move to the average of all the data points that are assigned to it. This process is repeated until the clusters stop moving much.

![Training process for unsupervised learning](media/ClusteringVisualization.gif)