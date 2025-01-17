# undirected-diagram

An algorithm to solve the following undirected diagram;

Given a undirected diagram G(V,E), each edge (i,j) \in (E) has a distance. There are two nodes (source node a and target node b). The hop means the jump along the path from a to b. For an example, if there is a path 0-1-4-2-6-3 from node 0 to node 3, the value of hop is 5. Please design an algorithm to find the shortest path from a to b in the G(V,E) under the hop constraint, where hop is equal to or larger than a given value. An example is given by the following description.

G(V,E):

1,2,3,4,5<br>
a b distance<br>
1 2 2 <br>
1 5 2 <br>
1 4 1 <br>

2 3 5<br>
1 3 4<br>
3 4 8<br>
3 5 7<br>
4 5 9<br>

a,b:
1 5

hop:
1

The shortest path is 1-5, where the distance is 2, but it does not satisfy the hop constraint because the hop is 1, not equal to or larger than 2. 
So the shortest path under the constraint of hop over a given value is 1-4-5, where the distance is 1.1 and hop is 2.

