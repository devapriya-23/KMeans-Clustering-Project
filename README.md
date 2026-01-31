Implementing K-Means Clustering on Synthetic Data
​Project Overview
​This project demonstrates the implementation of the K-Means clustering algorithm using a synthetic dataset. The goal is to group unlabelled data points into distinct clusters and evaluate the model's performance using the Elbow Method.
​Methodology
​Data Generation: Used make_blobs to create 500 samples with 4 distinct centers and a standard deviation of 1.0.
​Optimal K Selection: Implemented the Elbow Method by calculating the inertia (sum of squared distances to the nearest cluster center) for K values ranging from 1 to 10.
​Clustering Algorithm: Applied the KMeans algorithm with K=4 clusters as identified by the elbow point.
​Visualization: Generated scatter plots to visualize the clusters and their respective centroids (marked as red 'X').
​Results & Interpretation
​Optimal Cluster Count: The Elbow Method showed a sharp decrease in inertia until K=4, indicating that 4 is the most efficient number of clusters for this dataset.
​Centroid Accuracy: The centroids successfully converged to the center of each synthetic blob, ensuring high intra-cluster similarity.
​Inertia Score: The final model achieved a low inertia score at K=4, proving the effectiveness of the clustering.
​Tools Used
​Python: Core programming.
​NumPy/Scikit-learn: Data generation and algorithm implementation.
​Matplotlib: Data visualization.
