##### Weak Vertices

##### Input consists of up to 100 graphs. Each starts with an integer, 1 <= n <= 20, giving the number of vertices in the graph. Next comes n lines with n integers on each line, which describes an n x n adjacency matrix for the graph. Vertices are numbered from 0 to n - 1. If the adjacency matrix contains a one at row r, column c (where r >= 0, c <= n - 1), it means that there is an edge from vertex r to vertex c. Since the graph is undirected, the adjacency matrix is symmetric. The end of input is marked by a value of -1 for n.

##### For each graph, produce a line listing the weak vertices ordered from least to greatest.

##### Personal Runtime: 0.34s
