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
  ![MST](img/hw9-1.svg) <br/>
  Where there is a choice, consider vertices in **alphabetical** order,
  and edges in **lexicographic** order of endpoints:
    e.g., *(a,c)* < *(a, d)* < *(b, d)*.
  + (a) *(4 pts)* Demonstrate **Kruskal's**
    minimum spanning tree algorithm on the graph.
  + (b) *(4 pts)* Demonstrate **Prim's** algorithm on the graph,
    starting at vertex `a`.
  + (c) *(4 pts)* Demonstrate the **Bellman-Ford** algorithm
    on the graph for shortest-paths from the source `a`.
1. Given a weighted undirected graph \`G = (V, E, w)\`
  with \`w(u,v) > 0 forall (u,v) in E\`,
  consider **increasing** each edge weight by 1: <br/>
  Let \`w'(u,v) = w(u,v) + 1 forall (u,v) in E\`,
  and \`G' = (V, E, w')\`.
  + (a) *(3 pts)* **Prove** or disprove via counterexample:
  **MST**s are preserved by this transformation.
  I.e., if *T* is an MST of *G*, then *T* is also an MST of *G'*.
  + (b) *(3 pts)* **Prove** or disprove via counterexample:
  **shortest paths** are preserved by this transformation.
  I.e., if *p* is a shortest path from *u* to *v* in *G*,
  then *p* is also a shortest path from *u* to *v* in *G'*.
1. **Programming project:** Implement **Prim's algorithm** for minimum spanning tree.
  Input format is discussed below. <br/>
  You may use a library for priority queue
  (e.g., [Python's `heapq`](https://docs.python.org/3.0/library/heapq.html);
  you don't have to implement it yourself.
  + *(12 pts)* Correct, working **code**.
  + *(5 pts)* **Documentation**: write-up, readable code, good identifiers, etc.
  + *(5 pts)* **Tests**, including edge cases, etc.
  + *(4 pts extra credit)* A nice **graphical user interface**.
