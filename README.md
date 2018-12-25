# Dijkstra-Shortest-Reach-2

Practice>Algorithms>Graph Theory>Dijkstra: Shortest Reach 2

https://www.hackerrank.com/challenges/dijkstrashortreach/problem

This challenge is as much about Dijkstra Algorithm as about squeezing every drop of slack code in order to improve time complexity! Otherwise the algorithm will not pass all the tests and will time out!

Therefore, my solution includes:
- BufferReader instead of Scanner.
-  Adjacency List for vertices and edges.
- Array of integers for distances from the start.
- Array of booleans for visited vertices.
- Wrapper classes for the methods' parameters. Since the parameters in these methods
  do not change their value, only the pointer to the wrapper class is passed to the algorithm.
- Class variables for the Adjacency List that contains the vertices and edges
  and for the Array of integers that contains distances from the start.
- Printing of the results is divided into two smaller loops in order to avoid 
  an "if statement" for the start vertex while looping through the results.
