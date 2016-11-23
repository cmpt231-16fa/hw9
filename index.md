---
layout: page
title: "HW9: CMPT231"
subtitle: "Lecture 11-12, ch23-25"
ext-js: "https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=AM_CHTML"
---

{% include policies.md %}

{% include programming.md %}

### HW9 (40pts)
1. *(5 pts)* Demonstrate **Prim's** algorithm on the following weighed undirected graph. Consider vertices in alphabetical order.
  ![MST](img/hw9-1.svg)
1. *(5 pts)* Demonstrate **Kruskal's** algorithm on the above graph. Consider edges in lexicographic order of endpoints: e.g., (a,c) < (a, d) < (b, d)
1. *(5pts)* **Prove** or disprove via counterexample: **minimum spanning trees** are preserved if every edge weight is increased by 1.
1. *(5 pts)* **Prove** or disprove via counterexample: **shortest paths** (e.g., from a single source) are preserved if every edge weight is increased by 1.
1. *(8 pts)* (**Programming project**) Implement **priority queue** using binary min-heaps.
1. *(12 pts)* (**Programming project**) Use your priority queue to implement **Prim's algorithm** for minimum spanning tree.
  + *(4 pts extra credit)* Implement a **graphical user interface** to your MST implementation.
