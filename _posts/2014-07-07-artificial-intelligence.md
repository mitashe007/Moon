---
layout: post
title: "Artificial Intelligence"
date: 2014-07-07
excerpt: "Artificial intelligence (AI)" 
comments: false
---

## Contents

### Introduction and Agents

* Sartorial hoodie
* Labore viral forage
* Tote bag selvage
* DIY exercitation et id ugh tumblr church-key

### Search

* Sartorial hoodie
* Labore viral forage
* Tote bag selvage
* DIY exercitation et id ugh tumblr church-key

### Logic

* Sartorial hoodie
* Labore viral forage
* Tote bag selvage
* DIY exercitation et id ugh tumblr church-key

### Planning

* Sartorial hoodie
* Labore viral forage
* Tote bag selvage
* DIY exercitation et id ugh tumblr church-key

### Uncertainty

* Sartorial hoodie
* Labore viral forage
* Tote bag selvage
* DIY exercitation et id ugh tumblr church-key

### Learning

* Sartorial hoodie
* Labore viral forage
* Tote bag selvage
* DIY exercitation et id ugh tumblr church-key

### Natural Language Processing

* Sartorial hoodie
* Labore viral forage
* Tote bag selvage
* DIY exercitation et id ugh tumblr church-key

## Practical Works

### Breadth-First Search (BFS) 

BFS is an algorithm for traversing or searching tree or graph data structures. It starts at the tree root (or some arbitrary node of a graph, sometimes referred to as a 'search key') and explores the neighbor nodes first, before moving to the next level neighbors.

TODO: Implementation of BFS Algorithm in C# or Java

>Input: A graph Graph and a starting vertex root of Graph
>Output: All vertices reachable from root labeled as explored.

Breadth-First-Search(Graph, root):
    
    for each node n in Graph:            
        n.distance = INFINITY        
        n.parent = NIL

    create empty queue Q      

    root.distance = 0
    Q.enqueue(root)                      

    while Q is not empty:        
        current = Q.dequeue()
        for each node n that is adjacent to current:
            if n.distance == INFINITY:
                n.distance = current.distance + 1
                n.parent = current
                Q.enqueue(n)
                

### A-star Search

A* is a computer algorithm that is widely used in pathfinding and graph traversal, the process of plotting an efficiently traversable path between multiple points, called nodes. It enjoys widespread use due to its performance and accuracy.

TODO: Implementation of A-star Search Algorithm in C# or Java

function A*(start, goal)
    // The set of nodes already evaluated.
    closedSet := {}
    // The set of currently discovered nodes still to be evaluated.
    // Initially, only the start node is known.
    openSet := {start}
    // For each node, which node it can most efficiently be reached from.
    // If a node can be reached from many nodes, cameFrom will eventually contain the
    // most efficient previous step.
    cameFrom := the empty map

    // For each node, the cost of getting from the start node to that node.
    gScore := map with default value of Infinity
    // The cost of going from start to start is zero.
    gScore[start] := 0 
    // For each node, the total cost of getting from the start node to the goal
    // by passing by that node. That value is partly known, partly heuristic.
    fScore := map with default value of Infinity
    // For the first node, that value is completely heuristic.
    fScore[start] := heuristic_cost_estimate(start, goal)

    while openSet is not empty
        current := the node in openSet having the lowest fScore[] value
        if current = goal
            return reconstruct_path(cameFrom, current)

        openSet.Remove(current)
        closedSet.Add(current)
        for each neighbor of current
            if neighbor in closedSet
                continue		// Ignore the neighbor which is already evaluated.
            // The distance from start to a neighbor
            tentative_gScore := gScore[current] + dist_between(current, neighbor)
            if neighbor not in openSet	// Discover a new node
                openSet.Add(neighbor)
            else if tentative_gScore >= gScore[neighbor]
                continue		// This is not a better path.

            // This path is the best until now. Record it!
            cameFrom[neighbor] := current
            gScore[neighbor] := tentative_gScore
            fScore[neighbor] := gScore[neighbor] + heuristic_cost_estimate(neighbor, goal)

    return failure

function reconstruct_path(cameFrom, current)
    total_path := [current]
    while current in cameFrom.Keys:
        current := cameFrom[current]
        total_path.append(current)
    return total_path

### Genetic Algorithm 

Genetic algorithm (GA) is a metaheuristic inspired by the process of natural selection that belongs to the larger class of evolutionary algorithms (EA). Genetic algorithms are commonly used to generate high-quality solutions to optimization and search problems by relying on bio-inspired operators such as mutation, crossover and selection.

TODO: Implementation of Genetic Algorithm in C# or Java
