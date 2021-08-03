# Shortest-Path-Dynamic-Programming

g1.txt g2.txt g3.txt The first line indicates the number of vertices and edges, respectively. Each subsequent line describes an edge (the first two numbers are its tail and head, respectively) and its length (the third number). NOTE: some of the edge lengths are negative. NOTE: These graphs may or may not have negative-cost cycles.

The code computes the "shortest shortest path". It first identifies which, if any, of the three graphs have no negative cycles. Then For each such graph, it computes all-pairs shortest paths and remember the smallest one (i.e., compute min u,v∈V d(u,v), where d(u,v) denotes the shortest-path distance from u to v).
