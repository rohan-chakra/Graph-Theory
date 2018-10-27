# Graph-Theory
Includes standard graph theory algorithm source codes in python

## 1. Maximum Flow (Ford-Fulkerson's Algorithm)
Basic python code of finding the maximum flow in a network using Ford Fulkerson's Algorithm with an addition of printing the residual graph, the path flow and the maximum flow at each stage.

### About the Algorithm
 Ford Fulkerson's method says that we follow any augmenting path from source to sink/target and find the bottle neck capacity (min. capacity) in that path and add it to the maximum flow. Update the flow of each edge in that augmented path with the bottle neck capacity and repeat this process till no augmented path exists that leads from source to sink.

## 2. DFS (Depth First Search) Traversal
Basic Python code of traversing a graph in depth first search method, reporting the visited and finished times at the end. This code requires an input text file containing all the edges in the graph called "dfs_input.txt".
>Note that the points on the graph start from 0,1,2 and so on.

### About the Algorithm
 DFS traversal is done by arbitrarily selecting nodes and traversing from the source node to the point where all the neighbors of any node is visited. From that point we start to back-track on the path we had followed and look for new nodes left unvisited in the previous traversal. The time that we visit each node is its Visiting Time/Discovery Time and the time that we visit it and all of its neighbors is called its Finished Time.
