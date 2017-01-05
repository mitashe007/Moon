---
layout: post
title:  "Data Structures"
date:   2013-01-22
excerpt: "Data Structures"
comments: false
---

## Theory Contents

### Array and Linked List

* Linear and Circular

### Recursion
### Searching and Sorting

* Sequential Search
* Binary Search
* Key-indexed Search
* Bubble Sort
* Selection Sort
* Insertion Sort

### Stacks and Queues

* Array-based Implementation
* Linked List-based Implementation
* Priority Queue

### Trees and Graph

* Free trees
* Rooted trees
* Ordered trees
* M-ary trees: Binary trees
* Binary Search Trees
* Directed and Undirected graphs
* Directed Acyclic graphs
* Weighted and Unweighted graphs

### Graph Traversal

* Breadth-first Traversal
* Depth-first Traversal

### Data Structures and Representations

* Adjacency Matrix
* Adjancecy List

### Hashing and Hashtables


## Practical Work

### Assignments

#### Assignment-01

In this assignment, we'll implement a List Abstract Data Type (ADT) that is defined as the following:
* A List is a dynamic ordered tuple of homogeneous elements:
[ A0, A1, A2, ..., An-1 ]
where Ai is the ith element of the list.
* The index or position of the element Ai is i; the positions/indices range from 0 to n-1 inclusive.
* The size of a list is n.

#### Assignment-02

This assignment is a continuation of assignment 1, where we implemented the List interface using Java's built-in array container, and called it ArrayList. In this assignment, we will implement the List interface using a linked list, more specifically a dummy head-referenced doubly-linked circular list (see the notes on DHDLC lists on our course website).
Recall from assignment 1 the List Abstract Data Type (ADT) that is defined as the following:
•	A List is a dynamic ordered tuple of homogeneous elements: 
[ A0, A1, A2, ..., An-1 ]
where Ai is the ith element of the list. 
•	The index or position of the element Ai is i; the positions/indices range from 0 to n-1 inclusive. 
•	The size of a list is n. 

#### Assignment-03

In this assignment, you will implement dynamically resizable stack and queue of objects, using both an array and a linked list as the underlying container. Both Stack and Queue are a restricted access containers, where the container protocol determines where you can add to and remove from.
Stack 
You can only add an item by putting it on top of the stack (called push), and only remove the item that is currently at the top of the stack (called pop), which moves the next item, if any left, to the top. You can also look at what is currently at the top of the stack (called peek). 
Queue 
You can only add an item by putting it at the end of the queue (called enqueue), and only remove the item that is currently in the front of the queue (called dequeue), which moves the next item, if any left, to the front. You can also look at what is currently in the front of the queue (called peek). 
 
Applications of Stack — Postfix Calculator
There are great many applications of stacks, and we will look at a particular one in this assignment: arithmetic expression evaluator.

#### Assignment-04

You are going to implement very simple searching and sorting algorithms in this assignment, all of which were covered in class (in some detail).
•	The two simple searching algorithms we have covered in class: 
o	Linear search 
o	Binary search. We will also implement a variation of binary search that returns the first occurrence of a key in a sorted array, not just any occurrence, in case of multiple copies of the key. 
•	The two simple sorting algorithms we have covered in class: 
o	Selection sort 
o	Insertion sort 

#### Assignment-05

This is a purely paper assignment where you start practicing thinking recursively. You will write
formulate the recursive definitions (consisting of one or more recursive and base cases) for each of the
following problems. You will then translate each of these recursive algorithms to a Java method, which is
quite often very straightforward.

Problem 1: Summing the first n integers
You are to compute the sum 1 + 2 + 3 + … + n for some n ≥ 1. Write the recursive definition, and
translate that to Java static method sumN which takes n as a parameter, and returns the sum.

Problem 2: Sequential search through an List
You are to sequentially search through a List for a given key and return true if it exists in the list. The
list may be an array or a linked list, since sequential search does not require random access. Write the
recursive definitions of sequential search in an array, and in a linked list. Then write the Java methods
seqSearchArray, which takes an array and a key as parameters, and seqSearchList, which takes a node
reference and a key as parameters.

Problem 3: Finding the maximum value in a List
You are to sequentially scan a List for the maximal element and return it. The list may be an array or a
linked list, since sequential scan does not require random access. Write the recursive definitions of the
search for maximum in an array, and in a linked list. Then write the Java methods findMaxArray, which
takes an array as the parameter, and findMaxList, which takes a node reference as the parameter.

Problem 4: Binary search in an array
Write the recursive definition for searching a sorted array using the binary search algorithm. Then write
the Java method binSearch that takes an array to search in and a key to search as parameters.

### Lab Assignments
