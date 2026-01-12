CS110 - Problem Solving with Data Structures and Algorithms: Complete Concept Summary (Sessions 1-20)
Session 1: Writing Algorithms in Python—Part I
* Control flow structures (if/else, loops)
* Iteration basics
* Strings and lists in Python
* String slicing operations
* Iterating over strings and lists
* Indexing with negative indices
* Basic algorithm structure
Session 2: Fundamentals of Algorithms
* Algorithmic problem solving
* Introduction to pseudocode
* Algorithm correctness and invariants
* Loop invariants (initialization, maintenance, termination)
* Input/output specifications
* Problem decomposition
Session 3: Introduction to Asymptotic Notation
* Big-O notation
* Asymptotic analysis
* Time complexity fundamentals
* Comparing algorithm efficiencies
* Growth rates of functions
* Upper bounds on running time
Session 4: Runtime Analysis
* Best case, worst case, average case analysis
* Big-Ω (Omega) and Big-Θ (Theta) notation
* Analyzing nested loops
* Logarithmic time complexity
* Linear vs. quadratic time complexity
* Analyzing recursive algorithms
Session 5: Quadratic Sorting Algorithms
* Selection sort algorithm and analysis
* Insertion sort algorithm and analysis
* Comparison-based sorting
* In-place sorting
* Stable vs. unstable sorting
* O(n²) complexity of basic sorts
Session 6: Recursion
* Recursive function structure (base case, recursive case)
* The call stack
* Recursive problem decomposition
* Recursion trees
* Fibonacci sequence implementation
* Memoization basics
Session 7: Divide and Conquer—Maximum Subarray Problem
* Divide and conquer paradigm
* Maximum subarray problem
* Recursive problem splitting
* Combining subproblem solutions
* Master theorem introduction
* O(n log n) divide and conquer solutions
Session 8: Merge Sort
* Merge sort algorithm
* Merging two sorted arrays
* Space complexity considerations
* Stable sorting guarantee
* Recurrence relations: T(n) = 2T(n/2) + O(n)
* O(n log n) time complexity analysis
Session 9: Deterministic Quicksort
* Quicksort algorithm
* Partitioning schemes (Lomuto, Hoare)
* Pivot selection strategies
* In-place sorting advantage
* Worst-case O(n²) analysis
* Average-case O(n log n) behavior
Session 10: Randomized Quicksort
* Randomization in algorithms
* Random pivot selection
* Expected running time analysis
* Probabilistic analysis of algorithms
* Reducing worst-case probability
* Las Vegas algorithms
Session 11: Writing Algorithms in Python—Part II (OOP)
* Object-Oriented Programming fundamentals
* Classes and objects in Python
* Attributes and methods
* The __init__ constructor
* Instance vs. class attributes
* self keyword usage
* Encapsulation principles
Session 12: Heaps and Heapsort
* Heap data structure (complete binary tree)
* Max-heap property
* Heap representation as array
* Parent-child index relationships
* Build-heap operation
* Heapsort algorithm
* O(n log n) heapsort complexity
Session 13: Heaps and Priority Queues
* Priority queue ADT
* Heap-based priority queue implementation
* Insert operation (heapify-up)
* Extract-max operation (heapify-down)
* Heap increase-key operation
* Applications: task scheduling, event simulation
Session 14: Algorithms for Computing the Median
* Selection problem
* Median finding algorithms
* Quickselect algorithm
* Expected linear time selection
* Worst-case linear time algorithm (median of medians)
* Order statistics
Session 15: Binary Search Trees (BSTs)
* BST property and structure
* Search operation in BSTs
* Insertion in BSTs
* Deletion in BSTs (3 cases)
* In-order traversal for sorted output
* Tree successor and predecessor
* O(h) operations where h is height
Session 16: Randomly Built BSTs
* Expected height of random BSTs
* Relationship between insertion order and tree structure
* E[height] = O(log n) for random insertions
* Balanced vs. unbalanced trees
* Tree depth analysis
* Probabilistic tree construction
Session 17: Red-Black Trees
* Red-black tree properties (5 properties)
* Black-height concept
* Rotations (left and right)
* Recoloring operations
* RBT insertion with fix-up
* RBT deletion with fix-up
* Guaranteed O(log n) height
Session 18: k-d Trees
* k-dimensional space organization
* Building k-d trees with alternating dimensions
* Space partitioning and bounding boxes
* Median-based balanced tree construction
* k-d tree search operation
* Nearest neighbor algorithm
* Candidate hypersphere pruning
* Comparison with BSTs
Session 19: Aspects of Graphs
* Graph fundamentals (vertices, edges, paths, levels)
* Directed vs. undirected graphs
* Weighted vs. unweighted graphs
* Graph representations:
    * Adjacency matrix: O(V²) space
    * Edge list: O(E) space
    * Adjacency list: O(V+E) space
* Stacks (LIFO) and Queues (FIFO)
* Python deque for efficient queues
* Depth-First Search (DFS): iterative and recursive
* Breadth-First Search (BFS)
* O(V+E) time complexity for traversals
* Tree traversals: pre-order, in-order, post-order, level-order
* Trees vs. graphs comparison
* Topological ordering application (course scheduling)
Session 20: Computational Applications of Trees and Graphs
* AVL trees and strict balance requirement
* AVL balance factor (max ±1)
* AVL rotations for rebalancing
* AVL vs. Red-Black trees trade-offs:
    * AVL: stricter balance, faster lookups, more expensive insertion/deletion
    * RBT: less strict, faster modifications
* Comparing BST, RBT, and AVL expected heights
* Applications of different tree structures
* When to choose each tree type
* Height computation and maintenance