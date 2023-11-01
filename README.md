[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12476395&assignment_repo_type=AssignmentRepo)
# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

proof

- if we have two graphs $A$ and $B$ that are completley connected and have the same number of nodes...
- since $A$ and $B$ have the same number of nodes, there can exist a mapping such that every node in $A$ can be mapped to a unique node in $B$. This creates a one to one bijection between the two graphs.
- since $A$ and $B$ are completley connected and have the same number of nodes, every node has an edge, and both graphs must have the same number of edges, so if two nodes are connected by an edge in the first graph, they must be mapped to two nodes connected by an edge in the second graph.
- this means that there exists a one to one bijection between $A$ and $B$ such that if $A = (V_1 , E_1)$ and $B = (V_2, E_2)$ then $(u,v) \in E_1$ iff $(f(u),f(v)) \in E_2$.
- this fullfills the definition of isomorphism, such that there exists a one to one bijection between the nodes and edges of graphs $A$ and $B$ where two nodes in $A$ that are connected by an edge can be mapped to two nodes in $B$ connected by an edge
- therefore, any two graphs that are completley connected and have the same number of nodes are isomorphic
