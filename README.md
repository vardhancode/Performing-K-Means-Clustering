# Performing-K-Means-Clustering
This project applies K-Means Clustering to segment customers based on their Annual Income and Spending Score. The dataset used is the Mall Customers dataset (CSV file). The goal is to group customers into meaningful clusters for business insights.

Steps Performed:

-Importing Libraries
Imported pandas, matplotlib.pyplot, and sklearn.cluster.KMeans.

-Loading the Dataset

Read the CSV file using pd.read_csv().

Checked the dataset using head() and info().

-Selecting Features for Clustering

Selected only Annual Income (k$) and Spending Score (1-100) columns for clustering.

-Finding Optimal Number of Clusters (Elbow Method)

Ran K-Means for different cluster counts (1 to 10).

Plotted the Within-Cluster Sum of Squares (WCSS) against number of clusters.

Identified the "elbow point" where adding more clusters doesn’t improve much.

-Training K-Means Model

Chose the optimal n_clusters from the elbow method.

Fitted the model and predicted the cluster for each customer.

-Visualizing Clusters

Plotted each cluster with different colors for better visualization.

Marked cluster centroids.
