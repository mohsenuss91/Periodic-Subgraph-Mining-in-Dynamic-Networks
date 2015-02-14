# Periodic-Subgraph-Mining-in-Dynamic-Networks
Implement an algorithm to find the maximal subgraphs that recur at regular time period in a dynamic networks G for time T over a vertex set with uniquely labeled vertices. A maximal periodic subgraph means that it cannot be enriched by adding edges or expanding temporal span without losing support. The implementation is based on a hash table from a subgraph to a list of descriptors, a list containing the subgraph at period p with phase m and a matrix containing the list heads for different periods and phases. The time complexity is O((V+E)T^2 and the space complexity is O((V+E)T).
