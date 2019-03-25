# Data Structures and Algorithms in JavaScript

This repository covers the implementation of the classical algorithms and data structures in JavaScript.

<!-- This goes along with [these posts series](https://adrianmejia.com/tags/tutorial-algorithms/) that explain each implementation in details and also this [book](https://gum.co/dsajs) that explain these topics and some with more examples and illustrations. -->

## Data Structures
We are covering the following data structures.

[![Interactive Data Structures](https://user-images.githubusercontent.com/418605/46118890-ba721180-c1d6-11e8-82bc-6a671428b422.png)](https://embed.kumu.io/85f1a4de5fb8430a10a1bf9c5118e015)

### Linear Data Structures
1. **Arrays**: Built-in in most languages so not implemented here. [Code](https://github.com/amejiarosario/algorithms.js/blob/master/src/data-structures/arrays/array.js) | [Details](https://adrianmejia.com/blog/2018/04/28/data-structures-time-complexity-for-beginners-arrays-hashmaps-linked-lists-stacks-queues-tutorial/#Array).
2. **Linked Lists**: each data node has a link to the next (and previous). [Code](https://github.com/amejiarosario/algorithms.js/tree/master/src/data-structures/linked-lists) | [Details](https://adrianmejia.com/blog/2018/04/28/data-structures-time-complexity-for-beginners-arrays-hashmaps-linked-lists-stacks-queues-tutorial/#Linked-Lists).
3. **Queue**: data flows in a "first-in, first-out" (FIFO) manner. [Code](https://github.com/amejiarosario/algorithms.js/tree/master/src/data-structures/queues) | [Details](https://adrianmejia.com/blog/2018/04/28/data-structures-time-complexity-for-beginners-arrays-hashmaps-linked-lists-stacks-queues-tutorial/#Queues).
4. **Stacks**:  data flows in a "last-in, first-out" (LIFO) manner. [Code](https://adrianmejia.com/blog/2018/04/28/data-structures-time-complexity-for-beginners-arrays-hashmaps-linked-lists-stacks-queues-tutorial/#Stacks) | [Details](https://github.com/amejiarosario/algorithms.js/tree/master/src/data-structures/stacks).

### Non-Linear Data Structures
1. **Trees**: data nodes has zero or more adjacent nodes a.k.a. children. Each node can only have one parent node otherwise is a graph not a tree. [Code](https://github.com/amejiarosario/algorithms.js/tree/master/src/data-structures/trees) | [Details](https://adrianmejia.com/blog/2018/06/11/data-structures-for-beginners-trees-binary-search-tree-tutorial/)
	1. **Binary Trees**: same as tree but only can have two children at most. [Details](https://adrianmejia.com/blog/2018/06/11/data-structures-for-beginners-trees-binary-search-tree-tutorial/#Binary-Trees)
	1. **Binary Search Trees** (BST): same as binary tree, but the nodes value keep this order `left < parent < rigth`. [Code](https://github.com/amejiarosario/algorithms.js/blob/master/src/data-structures/trees/binary-search-tree.js) | [Details](https://adrianmejia.com/blog/2018/06/11/data-structures-for-beginners-trees-binary-search-tree-tutorial/#Binary-Search-Tree-BST)
	2. **AVL Trees**: Self-balanced BST to maximize look up time. [Code](https://github.com/amejiarosario/algorithms.js/blob/master/src/data-structures/trees/avl-tree.js) | [Details](https://adrianmejia.com/blog/2018/07/16/self-balanced-binary-search-trees-with-avl-tree-data-structure-for-beginners/)
	3. **Red-Black Trees**:  Self-balanced BST more loose than AVL to maximize insertion speed. [Code](https://github.com/amejiarosario/algorithms.js/blob/master/src/data-structures/trees/red-black-tree.js) | Details
2. **Maps**: key-value store.
	1. **Hash Maps**: implements map using a hash function. [Code](https://github.com/amejiarosario/algorithms.js/blob/master/src/data-structures/hash-maps/hashmap.js) | [Details](https://adrianmejia.com/blog/2018/04/28/data-structures-time-complexity-for-beginners-arrays-hashmaps-linked-lists-stacks-queues-tutorial/#HashMaps)
	2. **Tree Maps**: implement map using a self-balanced BST. WIP
3. **Graphs**: data *nodes* that can have a connection or *edge* to zero or more adjacent nodes. Unlike trees, nodes can have multiple parents, loops. [Code](https://github.com/amejiarosario/algorithms.js/blob/master/src/data-structures/graphs/graph.js) | [Details](https://adrianmejia.com/blog/2018/05/14/data-structures-for-beginners-graphs-time-complexity-tutorial/)

## Algorithms

We cover the following algorithms and techniques.

- Sorting algorithms
  - Bubble Sort
  - Insertion Sort
  - Selection Sort
  - Merge Sort
  - Quicksort
- Greedy Algorithms
- Divide and Conquer
- Dynamic Programming
- Backtracking algorithms

## Book

You can check out the book that goes deeper into each topic and provide addtional illustrations and explanations.

<a href="https://gum.co/dsajs"><img src="book/cover.png" height="400px"></a>
