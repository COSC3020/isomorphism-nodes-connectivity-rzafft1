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
- there exists a mapping such that any single node in $A$ can be mapped to exaclty one node in $B$ (i.e. $A$ and $B$ have the same number of nodes, and are one to one)
- since there is such a mapping that all nodes in $A$ have a corresponding node mapped in $B$, both graphs are completley connected such that there exists an edge between every node in both graphs 
- any nodes in $A$ that are connected by and edge, must also have a corresponding pair of nodes in $B$ also connected by an edge 
- this holds the required one to one and onto bijection between $A$ and $B$ 
- therefore, any two graphs that are completley connected and have the same number of nodes are isomorphic
