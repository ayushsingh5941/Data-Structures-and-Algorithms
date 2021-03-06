This library is created to understand and implement Data Structures and Algorithms in python. 
Since most courses on data structure and algorithm uses programming lanugages such as c and c++ which contains pointers  
and python does not so to implement data structures and algorithms in python remains quite unintiutive to most of the students.
This library is also useful to implement some custom algorithm without worrying about implementation of fundamental data structures
and run of the mill algorithms.
____________________________________________________________________________________________________________________________________
Documentation
____________________________________________________________________________________________________________________________________

ARRAYS
Arrays implementation here is to mimic static arrays used in c and c++ along with implementation some of the methods are also
available such as insertion, deletion, access, update and lenght.

# Creating a list using class Lists
list1 = Lists(size=size) 

# Inserting 5 elements in array
list1.insert(element=3)
list1.insert(element=7)
list1.insert(element=9)
list1.insert(element=2)
list1.insert(element=1)

# Inserting an element at specified location
list1.insert(element=5, index=2)

# Deleting from index of the array
list1.delete(2)

# Deleting from end of the array
list1.delete()

# update index 
list1.update(element=5, index=4)

# accesing a single element
list1.access(1)

# accesing all elements
# accesing a single element
list1.access()
=============================================================================================================================

LINKED LIST
Since python does not contain pointers implementation of linked list is not trivial hence it confuses students the most.
Here linked lists is similar to c implementation. It also contains some generic methods for Linked lists such as insertion,
deletion, access and length.

# Initializing a linked list
head = linkedList()

# Inserting some elements in linked list
head.insert(10)
head.insert(5)
head.insert(6)

# Inserting elements at end of list
head.insert(4, -1)

# Displaying all elements of the list
head.access()

# Number of elements in the list
head.length()
=============================================================================================================================

QUEUE
Queue is one of the most basic and important data structure in computer science and its implementation is quite straight forward
but time consuming this library intends to cut focus from making queues form scratch instead make algorithms from it.
It comes with some most useful methods such as head, tail, enqueue, dequeue and access.

# Initializing a queue
q = Queue()

# Inserting some elements in queue
q.enqueue(50)
q.enqueue(59)
q.enqueue(41)
q.enqueue(5)
q.enqueue(1)

# Deleting an element
q.dequeue()

# accessing by index
q.access(2)

# accessing all elements
q.access()

# Position of head
q.head()

# Position of tail
q.tail()
============================================================================================================================

STACK
Stack is most famous and widely used data structure and its implementation is easier than queue and even more easy in python.
This library poses this data structure too. Happy first in first out. This library contains push, pop, n_elements, top_element.

# Initializing Stack
stack1 = Stack()

# Inserting elements in stack
stack1.push(150)
stack1.push(5)
stack1.push(8)
stack1.push(1)

# deleting an element from stack
stack1.pop()

# Number of elements in stack
stack1.n_elements()

# Element at top of stack
stack1.top_element()
============================================================================================================================

Binary Search Tree
Binary search tree is one of most complicated data structure to understand and implementat especially in python due to lack of pointers.
This package tries to cover all the nuances of BST such as insertion, deletion, max element, min element, height of tree, 
traversals such as breadth first, depth first including preorder, inorder and postorder traversala and a function to check
whether given tree is BST or not.

# Initializing tree
tree = BinarySearchTree()

# Inserting element at root
root = tree.insert(6)

# Inserting elemnts
root.insert(12)
root.insert(4)

# Maximum value in tree
root.max_element()

# Minimun value in tree
root.min_element()

# height of tree
root.height()

# Bfs traversal
root.bfs_traversal([root])

# Pre order depth first traversal
root.pre_order_dfs()

# Inorder traversal
root.in_order_dfs()

# Post order traversal
root.post_order_dfs()

# Checking whether a tree is BST or not
root.isBST()

# Deleting value from tree
root.delete(8)
============================================================================================================================

SORTING ALGORITHMS
Currently this library contains few sorting algorithms such as insertion sort, bubble sort, merge sort and heap sort. In future
revision more will be added.

# Instertion sort
insertion_sort(array)

# Bubble sort
bubble_sort(array)

# Merge sort
merge_sort(array)

# Heap sort
heap_sort(array)
============================================================================================================================

More algorithms and data structures in future updates.