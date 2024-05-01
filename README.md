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
### Depth First Search ( DFS ): Procedure

Let's consider the following graph to understand DFS traversal. 

<img src="IMG1.jpg" width="60%" alt="image_1"/>

Now we need to generate an input for the code. We can create an adjacency matrix from this graph.

<img src="IMG_22.jpg" width="60%" alt="image_2"/>

## Step 1:
In this case we can start the traversal from node "0". We need to define a stack to track the nodes.


<img src="IMG_20.jpg" width="60%" alt="image_3"/>

<ul>
  <li>First put the first node 0 to the stack. </li>
  <li>Then check if there are any adjacent nodes.</li>
</ul>

## Step 2:

We found 1 adjacent nodes here (node 3). 

<img src="IMG_23.jpg" width="60%" alt="image_4"/>

<ul>
  <li>Now push node 3 to the stack. </li>
  <li>Then check if there are any adjacent nodes of the current node (of node 3).</li>
</ul>

## Step 3:

Keep repeating this process untill there are no adjacent node of the current node.

<img src="IMG_21.jpg" width="60%" alt="image_5"/>

<ul>
  <li>Here node 3 has no adjacent node. So we will pop it out of the stack to check the previous node.</li>
  <li>If the previous node has an adjacent node push it in the stack or pop the current node out of stack until any unvisited node is found</li>
</ul>


## Step 4:

Keep repating step 2 and step 3 until the stack is empty.


## Step 5:

Now the output is generated and it represents a spanning tree.

And the DFS output starting from node "0" is: 0, 3, 2, 4, 1
<img src="IMG020.jpg" width="60%" alt="output"/>

## Output of the Code:
<img src="Screenshot from 2024-05-01 23-44-37.png" width="60%" alt="image_11"/>

## Git Bash Screenshot:

<img src="git_cmd.png" width="60%" alt="git_bash"/>
<img src="git_push_cmd.png" width="60%" alt="git_bash"/>
