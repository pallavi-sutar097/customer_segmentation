Customer Segmentation using K-Means Clustering


Objective:
The primary objective of this project is to segment customers into distinct groups based on their annual income and spending score. This segmentation can help businesses understand customer behavior and preferences better, leading to more effective marketing strategies and improved customer relationships.

Working:

Data Loading and Exploration:

Customer data is loaded from a CSV file (Mall_Customers.csv).
The data is explored to check its shape, information, and missing values.
Relevant features for clustering (annual income and spending score) are extracted.
Determining Optimal Clusters (Elbow Method):

The Elbow Method is employed to identify the optimal number of clusters.
It involves calculating the Within-Cluster Sum of Squares (WCSS) for different cluster numbers.
The WCSS values are plotted against the corresponding cluster numbers, creating an "elbow" shape.
The elbow point, representing the point of diminishing returns in WCSS reduction, indicates the optimal number of clusters (5 in this case).
K-Means Clustering:

The K-Means algorithm is applied to the data with the determined number of clusters (5).
K-Means works by iteratively assigning data points to clusters based on their proximity to the cluster centroids.
This process continues until the centroids stabilize, and each data point belongs to a specific cluster.
Cluster Visualization and Interpretation:

The resulting clusters are visualized using a scatter plot with annual income and spending score as axes.
Each cluster is represented by a different color for easy distinction.
The centroids of the clusters are also plotted, highlighting the central tendencies of each group.
By analyzing the clusters' characteristics (income, spending), businesses can identify meaningful customer segments and tailor their strategies accordingly.
In summary, this project utilizes K-Means clustering to effectively segment customers based on their purchasing behavior. The insights gained from this segmentation can be used to personalize marketing campaigns, improve customer targeting, and ultimately enhance business outcomes.
