# Breadth-First Search (BFS) Algorithm

**BFS** (Breadth-First Search) is an algorithm designed for traversing or searching through graph or tree data structures. It is named "breadth-first" because it explores all neighbor nodes at the current depth before moving on to nodes at the next depth level.

## Key Principles:

1. **Initialization:** Start with the root node and enqueue it as the initial node in the queue.

2. **Queue:** Maintain a queue to keep track of nodes to be explored.

3. **Exploration:** While the queue is not empty, dequeue the front node and process it.

4. **Neighbors:** Explore all neighboring nodes of the current node.

5. **Enqueue:** Enqueue any unvisited neighbors into the queue.

6. **Repeat:** Repeat steps 3-5 until the queue is empty or a specific condition is met.

## Key Features:

- BFS is typically implemented using a queue data structure, making use of the "first-in, first-out" (FIFO) principle.

- It is suitable for finding the shortest path in an unweighted graph since it explores nodes level by level.

- BFS can be used to solve various problems, including finding connected components, checking for bipartite graphs, and more.

- The time complexity of BFS is O(V + E), where V represents the number of vertices and E represents the number of edges in the graph.

- It ensures that the shortest path to a node is found first, making it useful for navigation and route planning.



