What is a Heap?
Is a binary tree data structure that satisfies the heaps property 
i.e. for every node the value of its children is less than or equal to its own value. 

Advantages of Heaps.
1. Efficient insertion and deletion of elements
2. Efficient priority queue where the high element is always at the top of the queue
3. Space efficiency
4. Guaranteed access of maximum and minimum element
5. Efficient sorting algorithm

Disadvantages of Heaps.

1. Lack of flexibility as it designed to maintain specific order of elements
2. Not a stable data structure.
3. Memory management which can be challenging in some systems with limited memory.
4 Complexity


Adding items in a heap
1. Insert the node in the first available order position
2. Compare the newly inserted node with its parent.If the newly inserted node is greater than the parent then swap.
3. Repeat step two until the heap property is restored


Removing items in a heap
1. Find the maximum heap.
2. Replace the maximum node with the last leaf node 
3. Compare the replacement against its children.

