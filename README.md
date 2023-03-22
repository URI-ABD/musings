# musings
Ideas for Future works in CLAM and related research

## Visualizing the entropy/homogeneity of clusters
- Create a cluster tree using labeled data such as the mnist dataset.
- For each cluster in the tree, cache the percentage of its indices that correspond to each label. 
- Create a visualization that walks through the tree and displays the homogeneity of each cluster. 
- For example, the root cluster would contain a mix of all data labels. At a certain depth, a specific cluster might contain all data that is associated with a specific label.
- Allow the user to run this program with different distance metrics, labels, and datasets to view how the clustering algorithm and different distance metrics affect the homogeneity of the clusters.


