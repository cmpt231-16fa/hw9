---
layout: page
title: "HW9: CMPT231"
subtitle: "Lecture 11, ch23-24"
ext-js: "https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=AM_CHTML"
---

{% include policies.md %}

{% include programming.md %}

### HW9 (40pts)
1. Consider the following weighted undirected graph: <br/> 
  ![MST](img/hw9-1.svg)
  + (a) *(5 pts)* Demonstrate **Kruskal's**
    minimum spanning tree algorithm on the graph.
    Consider edges in lexicographic order of endpoints:
    e.g., *(a,c)* < *(a, d)* < *(b, d)*
  + (b) *(5 pts)* Demonstrate **Prim's** algorithm on the graph,
    starting at vertex `a`.
    Consider vertices and neighbours in alphabetical order.
  + (c) *(5 pts)* Demonstrate the **Bellman-Ford** algorithm
    on the graph for shortest-paths from the source `a`.
1. Given a weighted undirected graph *G = (V, E, w)*
  with *w(u,v)* > 0 &forall; *(u,v)* &in; *E*,
  consider **increasing** each edge weight by 1: <br/>
  Let *w'(u,v)* = *w(u,v)* + 1 &forall; *(u,v)* &in; *E*,
  and *G' = (V, E, w')*.
  + (a) *(5pts)* **Prove** or disprove via counterexample:
  **MST**s are preserved by this transformation.
  I.e., if *T* is an MST of *G*, then *T* is also an MST of *G'*.
  + (b) *(5 pts)* **Prove** or disprove via counterexample:
  **shortest paths** are preserved by this transformation.
  I.e., if *p* is a shortest path from *u* to *v* in *G*,
  then *p* is also a shortest path from *u* to *v* in *G'*.
1. **Programming project:**
  + (a) *(6 pts)* Implement **priority queue** using binary min-heaps.
  + (b) *(8 pts)* Implement **Prim's algorithm** for minimum spanning tree.
  + (c) *(4 pts extra credit)* Implement a **graphical user interface** to your MST.
