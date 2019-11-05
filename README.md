# GraphPathes

R implementation of self-modified methods of depth-first search, breadth-first search and Dijkstra's algorithm.

DFS and BFS were modified to work not only for tree graphs, but for more complex cases. They DO NOT return optimal path in general case. They return just some path.

Dijkstra's search, however, returns optimal path. This algorithm works with weights for edges, which means, it can be used for solving variety of cases, such as logistic tasks (e.g. optimal navigation), networking in social services etc.
To find optimal path for unweighted graph, all weights can be set to equal value (e.g. 1).
