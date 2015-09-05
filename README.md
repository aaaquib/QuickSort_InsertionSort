# QuickSort_InsertionSort

Project 1:
One way to improve the performance of QuickSort is to switch to InsertionSort when a subfile has <= M elements instead of recursively calling itself. Implement a recursive QuickSort with a cutoff to InsertionSort for subfiles with M or less elements. Include counters in the codes, empirically determine the value of M for which it performs fewest total number of key comparisons and key assignments on inputs of 10000 random natural numbers each ess than K for K = 100, 1000, 10000, 100000.

Project 2:
Process a weighted undirected graph as follows:

1. Read in the number of vertices V and the number of edges E of the graph followed by its E edges, each in the form u, v, w where 1 <= u, v <= V & w > 0 representing an edge uv with weight w.

2. Set up and print the adjacency matrix representation of the Graph.

3. Determine whether the graph is connected.

4. Find a minimum spanning tree for each component and print the minimum spanning forest in adjacency matrix representation (regardless it has just one or more than one components).

5. If the graph is connected, use Priority-First Search to find a shortest path tree from vertex 1. Print the adjacency matrix representation of the tree.
