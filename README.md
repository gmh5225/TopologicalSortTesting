# TopologicalSortTesting

Selects a vertex from the DAG graph that has no precursors (i.e., has an entry of 0) and outputs it.

Delete that vertex and all directed edges starting from it from the graph.

Repeat 1 and 2 until the current DAG graph is empty or there are no vertices without precursors in the current graph. The latter case indicates that there must be a ring in the directed graph.

