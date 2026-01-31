# 📊 Implementing K-Means Clustering on Synthetic Data

## ​📝 Project Overview
​This project demonstrates the implementation of the K-Means clustering algorithm from scratch using a synthetic dataset. The primary goal is to understand how unsupervised learning groups unlabelled data points and to evaluate the model using the Elbow Method.

## ​⚙️ Methodology
### ​1. Data Generation
* ​Used the make_blobs function to create a dataset of 500 samples.
* ​Configured the data to have 4 distinct clusters with a standard deviation of 1.0 to ensure clear separation.
  
### ​2. The Elbow Method (Finding Optimal K)
* ​Calculated the Inertia (sum of squared distances to the nearest cluster center) for K values ranging from 1 to 10.
​* The "elbow" point was identified at **K=4**, confirming it as the optimal number of clusters.

### ​3. Clustering Implementation
* ​Applied the KMeans algorithm with **K=4** clusters.
* ​Visualized the final grouping using a scatter plot where each cluster is color-coded.

## ​📈 Results & Interpretation

* **Optimal Cluster Count:** As shown in the Elbow plot, the inertia drops significantly until **K=4**, after which the decrease becomes gradual.

* **​Centroid Positioning:** The final visualization shows **4 red 'X' markers** representing the centroids. These are perfectly positioned at the center of each data blob.
  
* **​Performance:** The model successfully identified the underlying patterns in the feature space with a very low final inertia score.

## ​🛠️ Tools & Libraries

* **​Python:** Main programming language.
 
* **Scikit-Learn:** For *make_blobs* and *KMeans* implementation.

* **Matplotlib:** For generating visual reports and graphs.

* **NumPy:** For numerical operations.
