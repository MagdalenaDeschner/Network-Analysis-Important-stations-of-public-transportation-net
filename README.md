## Data

Subway stations and lines in Vienna 2018

## What?

In this notebook, we will find out which stations could turn out to be some kind of bootlenecks. Think of ticket terminal breakdowns, overcrowded escalators or train cancellation at a station. Knowing the bottlenecks of a subway or any other transportation network could help to better maintain frequently travelled stations by knowing at which edge a failure would harm most.
Another use case concerning transportation networks is finding out which stations are highly connected with other lines. Imaging moving to Vienna. You want to know where exactly to move in order to not be dependent on one single subway line. Let's find out stations, which enable you to use as many different lines as possible.

## Graph-theory

Finding out bottleneck nodes within a network -> "betweenness centrality":
... is the ratio between the "number of shortest paths trough a node" and "all possible shortest paths" in a graph.
Detecting highly connected nodes -> "degree centrality":
... divides the "number of edges held by a specific node" by the "total number of nodes in the network minus 1". 
