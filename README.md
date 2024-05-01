# DFS Algorithm and Steps 

### Depth First Search ( DFS ): Algorithm
<ol>
  <li>Created a stack of nodes and take the adjacency matrix as input.</li>
  <li>Define a stack with size of total number of nodes. Here we are taking total 5 nodes.</li>
  <li>Select any node as the starting point of traversal and push it in the stack.In this following graph we are starting with node 0.</li>
  <li>Check if it has any unvisited neighbour nodes. If so push it in the stack</li>
  <li>Repeat step 4 untill there is no neighbour node of the node which is at the top of the stack.</li>
  <li>Pop the node from the top of the stack.</li>
  <li>Repeat step 4, 5 and 6 untill the stack is empty.</li>
  <li>When the stack is empty the whole graph is traversed.</li>
</ol>
