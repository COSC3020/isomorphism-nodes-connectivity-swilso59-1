[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/ppBU16qM)
# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

- If we have two graphs A and B that have the same number of nodes and are completely connected we can create a bijection.
- We can do this by pairing each node from A to a node in B.
- Every node in the graphs are completely connected so the way they are connection does not matter.
- Since both graphs are completely connected, every node in A is connected to every other node. This is also true for graph B
  this means that any bijection between the nodes of A and B will preserve this connectivity property.
- This allows us to see that no matter what the permutation of the mapping is each node in A will have a connection to its own node in B
- All nodes from B can be reached from A.
- This give us a bijection and tells us two graphs with the same number of nodes that are completely connected must be isomorphic. 

// For this assignment I ended up looking at these repositories:
// isomorphism-nodes-connectivity-IshitaPatel18
// isomorphism-nodes-connectivity-AndonM
