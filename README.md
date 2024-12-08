## Comments:

isEdgeInK4SubgraphQ.txt : Test whether an edge of a graph is part of a subgraph that is isomorphic to $K_4$

Then

```
edgesInK4SubgraphQ[graph_] := 
  AllTrue[EdgeList[graph], isEdgeInK4SubgraphQ[graph, #] &]
```
