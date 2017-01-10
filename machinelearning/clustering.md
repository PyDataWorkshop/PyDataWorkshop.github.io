Hierarchical agglomerative clustering (Ward)
============================================
A Hierarchical clustering method is a type of cluster analysis that aims to build a hierarchy of clusters. 
In general, the various approaches of this technique are either:

- Agglomerative : bottom-up approaches, or
- Divisive : top-down approaches.

For estimating a large number of clusters, top-down approaches are both statistically ill-posed and slow due to 
it starting with all observations as one cluster, which it splits recursively. 

Agglomerative hierarchical-clustering is a bottom-up approach that successively merges observations together and 
is particularly useful when the clusters of interest are made of only a few observations. 

Ward clustering minimizes a criterion similar to k-means in a bottom-up approach. 

When the number of clusters is large, it is much more computationally efficient than k-means.
