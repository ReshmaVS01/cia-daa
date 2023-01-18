# cia-daa
1. I have used C programming language.The reason why I chose C is I have already learnt data structures in c the previous semester.I have also did my lab exercises wherein I have executed prims & kruskals algorithm in C.

2. + Dijkstra’s algorithm is ussed to find the shortest path, but Prim’s & Kruskal's algorithms are used to find the Minimum Spanning Tree.
   + Prim’s & Kruskal's algorithm can handle negative weights, but Dijkstra’s algorithm may not accurately compute distances if at least one negative            weight exists
   + Prim’s algorithm runs faster in dense(more edges) graphs whereas Kruskal’s algorithm runs faster in sparse(less edges) graphs.
   + Time complexity of prims is O(v^2) where v-vertices,since one node is traversed more than 1 time
     Time complexity of Kruskals is O(e log v),since the minimum spanning tree is constructed by considering the least weighted edges and each node is          traversed only once.
     Time complexity of dijstra's is O(v^2).
     
