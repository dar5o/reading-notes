# Reading notes for whiteboard final of 401

##### What is a Data-Structure
Data Structures are a specialized means of organizing and storing data in computers in such a way that we can perform operations on the stored data more efficiently. Data structures have a wide and diverse scope of usage across the fields of Computer Science and Software Engineering.

## Data-Structures
- ### Arrays
  + An array is a structure of fixed-size, which can hold items of the same data type. It can be an array of integers, an array of floating-point numbers, an array of strings or even an array of arrays (such as 2-dimensional arrays). Arrays are indexed, meaning that random access is possible.
  + Array Operations:
    1. Traverse: Go through the elements and print them.
    2. Search: Search for an element in the array. You can search the element by its value or its index
    3. Update: Update the value of an existing element at a given index
  + Application of arrays
    * Used as the building blocks to build other data structures such as array lists, heaps, hash tables, vectors and matrices.
    * Used for different sorting algorithms such as insertion sort, quick sort, bubble sort and merge sort.

- ### Linked Lists
  + A linked list is a sequential structure that consists of a sequence of items in linear order which are linked to each other. Hence, you have to access data sequentially and random access is not possible. Linked lists provide a simple and flexible representation of dynamic sets.
  + Linked list operations
    1. Search: Find the first element with the key k in the given linked list by a simple linear search and returns a pointer to this element
    2. Insert: Insert a key to the linked list. An insertion can be done in 3 different ways; insert at the beginning of the list, insert at the end of the list and insert in the middle of the list.
    3. Delete: Removes an element x from a given linked list. You cannot delete a node by a single step. A deletion can be done in 3 different ways; delete from the beginning of the list, delete from the end of the list and delete from the middle of the list.
  + Application of linked lists
    * Used for symbol table management in compiler design.
    * Used in switching between programs using Alt + Tab (implemented using Circular Linked List).

- ### Stacks and Queues
  + A stack is a LIFO (Last In First Out — the element placed at last can be accessed at first) structure which can be commonly found in many programming languages. This structure is named as “stack” because it resembles a real-world stack — a stack of plates.
  + Stack Operations
    1. Push: Insert an element on to the top of the stack.
    2. Pop: Delete the topmost element and return it.
    3. Peek: Return the top element of the stack without deleting it.
    4. isEmpty: Check if the stack is empty.
    5. isFull: Check if the stack is full.
  + Applications of stacks
    * Used for expression evaluation (e.g.: shunting-yard algorithm for parsing and evaluating mathematical expressions).
    * Used to implement function calls in recursion programming.
  + A queue is a FIFO (First In First Out — the element placed at first can be accessed at first) structure which can be commonly found in many programming languages. This structure is named as “queue” because it resembles a real-world queue — people waiting in a queue.
  + Queue Operations
    1. Enqueue: Insert an element to the end of the queue.
    2. Dequeue: Delete the element from the beginning of the queue.
  + Applications of queues
    * Used to manage threads in multithreading.
    * Used to implement queuing systems (e.g.: priority queues).

- ### Hash Tables
  + A Hash Table is a data structure that stores values which have keys associated with each of them. Furthermore, it supports lookup efficiently if we know the key associated with the value. Hence it is very efficient in inserting and searching, irrespective of the size of the data.
  + Hash Table Operations
    1. A special function named as the hash function (h) is used to overcome the aforementioned problem in direct addressing. In direct accessing, a value with key k is stored in the slot k. Using the hash function, we calculate the index of the table (slot) to which each value goes. The value calculated using the hash function for a given key is called the hash value which indicates the index of the table to which the value is mapped. `h(k) = k % m` 
        * h: Hash Function
        * k: Key of which the hash value should be determined
        * m: Size of the hash table. A prime value that is not close to an exact power of 2 is a good choice for m.
  + Applications of hash tables
    * Used to implement database indexes.
    * Used to implement associative arrays.
    * Used to implement the “set” data structure.

- ### Trees
  + A tree is a hierarchical structure where data is organized hierarchically and are linked together. This structure is different from a linked list whereas, in a linked list, items are linked in a linear order. Some examples of different types of trees are binary search tree, B tree, treap, red-black tree, splay tree, AVL tree and n-ary tree.
  + Binary Search Trees
    1. key: The value stored in the node.
    2. left: The pointer to the left child.
    3. right: The pointer to the right child.
    4. p: The pointer to the parent node.
  + Applications of trees
    * Binary Trees: Used to implement expression parsers and expression solvers.
    * Binary Search Tree: used in many search applications where data are constantly entering and leaving.
    * Heaps: used by JVM (Java Virtual Machine) to store Java objects.
    * Treaps: used in wireless networking.

- ### Graphs
  + A graph consists of a finite set of vertices or nodes and a set of edges connecting these vertices.
  + The order of a graph is the number of vertices in the graph. The size of a graph is the number of edges in the graph.
  + The order of a graph is the number of vertices in the graph. The size of a graph is the number of edges in the graph.
  + Application of graphs
    * Used to represent social media networks. Each user is a vertex, and when users connect they create an edge.
    * Used to represent web pages and links by search engines. Web pages on the internet are linked to each other by hyperlinks. Each page is a vertex and the hyperlink between two pages is an edge. Used for Page Ranking in Google.
    * Used to represent locations and routes in GPS. Locations are vertices and the routes connecting locations are edges. Used to calculate the shortest route between two locations.

##### What is data
Data is classified into types, such as a set of whole numbers (also known as integers) or a set of printing characters.

## Data Types
- Integer (whole number)
  + Example: 4, 27, 65536
- Floating point (decimal number)
  + Example: 4.2, 27.4, 3.141
- String
  + Example: abc, hello world
- Boolean
  + true or false
- Character
  + a, F, 3, $, #, @
