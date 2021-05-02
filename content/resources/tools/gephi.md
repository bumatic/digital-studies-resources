	---
title: Gephi
draft: false
bookFlatSection: true
bookCollapseSection: false
weight: 20
summary: summary
---

## Glossary

Degree (Grad):
:	The degree of a node is the number of edges that are adjacent to the node. [https://github.com/gephi/gephi/wiki/Degree](https://github.com/gephi/gephi/wiki/Degree) See: Average Degree (Mittlerer Grad) and Average Weighted Degree (Mittlerer gewichteter Grad)


## Statistics

### Modularity (Modularität)

**Description:** Modularity is one measure of the structure of networks or graphs. It was designed to measure the strength of division of a network into modules (also called groups, clusters or communities). Networks with high modularity have dense connections between the nodes within modules but sparse connections between nodes in different modules. Modularity is often used in optimization methods for detecting community structure in networks. However, it has been shown that modularity suffers a resolution limit and, therefore, it is unable to detect small communities. Biological networks, including animal brains, exhibit a high degree of modularity.
[Source: [https://en.wikipedia.org/wiki/Modularity_(networks)](Wikipedia)]


### PageRank (Page Rank)

**Description:** A measure of the importance of each node within the network. The metric assigns each node a probability that is the probability of being at that page after many clicks. The page rank values are the values in the eigenvector that has the highest corresponding eigenvalue of a normalized adjacency matrix A'. The standard adjacency matrix is normalized so that the columns of the matrix sum to 1. [Source: [https://github.com/gephi/gephi/wiki/PageRank](Gephi Github Wiki)]

[https://github.com/gephi/gephi/wiki/PageRank](https://github.com/gephi/gephi/wiki/PageRank)


### HITS (HITS)

**Description:** Hyperlink-Induced Topic Search (HITS) (also known as Hubs and authorities) provides a metrics to analyze the relevance of pages (nodes) in a network. It deternines two values: its authority, which estimates the value of the content of the page, and its hub value, which estimates the value of its links to other pages. [Source: [https://github.com/gephi/gephi/wiki/HITS](Gephi Github Wiki)]


### Connected Components (Verbundene Komponenten)

**Description undirected graphs:** In graph theory, a component, sometimes called a connected component, of an undirected graph is a subgraph in which any two vertices are connected to each other by paths, and which is connected to no additional vertices in the supergraph. For example, the graph shown in the illustration has three components. A vertex with no incident edges is itself a component. A graph that is itself connected has exactly one component, consisting of the whole graph. [Source: [https://en.wikipedia.org/wiki/Component_(graph_theory)](Wikipedia)]

**Description directed graphs:** In the mathematical theory of directed graphs, a graph is said to be strongly connected if every vertex is reachable from every other vertex. The **strongly connected components** of an arbitrary directed graph form a partition into subgraphs that are themselves strongly connected. It is possible to test the strong connectivity of a graph, or to find its strongly connected components, in linear time (that is, Θ(V+E)). [Source: [https://en.wikipedia.org/wiki/Strongly_connected_component](Wikipedia)]


### Eigenvector Centrality (Eigenvektorzentralität)

**Description:** In graph theory, eigenvector centrality (also called eigencentrality or prestige score) is a measure of the influence of a node in a network. Relative scores are assigned to all nodes in the network based on the concept that connections to high-scoring nodes contribute more to the score of the node in question than equal connections to low-scoring nodes. A high eigenvector score means that a node is connected to many nodes who themselves have high scores. Google's PageRank and the Katz centrality are variants of the eigenvector centrality. [Source: [https://en.wikipedia.org/wiki/Eigenvector_centrality](Wikipedia)]

[https://github.com/gephi/gephi/wiki/Eigenvector-Centrality](https://github.com/gephi/gephi/wiki/Eigenvector-Centrality)


### Average (Shortest) Path Length (Mittlere Pfadlänge)

**Description:** The average shortest path length is calculated by finding the shortest path between all pairs of nodes, and taking the average over all paths of the length thereof (the length being the number of intermediate edges contained in the path, i.e., the distance {\displaystyle d_{u,v}}{\displaystyle d_{u,v}} between the two vertices {\displaystyle u,v}u,v within the graph). This shows us, on average, the number of steps it takes to get from one member of the network to another. The behavior of the expected average shortest path length (that is, the ensemble average of the average shortest path length) as a function of the number of vertices {\displaystyle N}N of a random network model defines whether that model exhibits the small-world effect; if it scales as {\displaystyle O(\ln N)}{\displaystyle O(\ln N)}, the model generates small-world nets. For faster-than-logarithmic growth, the model does not produce small worlds. The special case of {\displaystyle O(\ln \ln N)}{\displaystyle O(\ln \ln N)} is known as ultra-small world effect. [Source: [https://en.wikipedia.org/wiki/Network_science#Average_shortest_path_length_(or_characteristic_path_length)](Wikipedia)]

### Network Diameter (Netzwerk Durchmesser)

**Description:** As another means of measuring network graphs, we can define the diameter of a network as the longest of all the calculated shortest paths in a network. It is the shortest distance between the two most distant nodes in the network. In other words, once the shortest path length from every node to all other nodes is calculated, the diameter is the longest of all the calculated path lengths. The diameter is representative of the linear size of a network. If node A-B-C-D are connected, going from A->D this would be the diameter of 3 (3-hops, 3-links). [Source: [https://en.wikipedia.org/wiki/Network_science](Wikipedia)]

**Related measures:**
	- Betweenness Centrality 
	- Closeness Centrality


#### Betweenness Centrality

**Description:** In graph theory, betweenness centrality (or "betweeness centrality") is a measure of centrality in a graph based on shortest paths. For every pair of vertices in a connected graph, there exists at least one shortest path between the vertices such that either the number of edges that the path passes through (for unweighted graphs) or the sum of the weights of the edges (for weighted graphs) is minimized. **The betweenness centrality for each vertex is the number of these shortest paths that pass through the vertex.** [Source: [https://en.wikipedia.org/wiki/Betweenness_centrality](Wikipedia)]

#### Closeness Centrality

**Description:** The average distance from a given node to all other nodes in the network. [Source: [https://github.com/gephi/gephi/wiki/Closeness-Centrality](Gephi Github Wiki)]


### Average Clustering Coefficient (Durchschnittlicherer Clustering Koeffizient)

**Clusterin coefficient (Clusterkoeffizient):** In graph theory, a clustering coefficient (Watts-Strogatz) is a measure of the degree to which nodes in a graph tend to cluster together. Evidence suggests that in most real-world networks, and in particular social networks, nodes tend to create tightly knit groups characterised by a relatively high density of ties; this likelihood tends to be greater than the average probability of a tie randomly established between two nodes. Two versions of this measure exist: the global and the local. The global version was designed to give an overall indication of the clustering in the network, whereas the local gives an indication of the embeddedness of single nodes. [Source: [https://en.wikipedia.org/wiki/Clustering_coefficient](Wikipedia)]

**Objective:** The clustering coefficient, along with the mean shortest path, can indicate a "small-world" effect. For the clustering coefficient to be meaningful it should be significantly higher than in version of the network where all of the edges have been shuffled. [Source: [https://github.com/gephi/gephi/wiki/Average-Clustering-Coefficient](Gephi Github Wiki)]

Watts, D.J., Strogatz, S.H.(1998) Collective dynamics of 'small-world' networks. Nature 393:440-442. [http://tam.cornell.edu/SS_nature_smallworld.pdf](PDF)


### Graph Density (Kantendichte)

**Description:** In mathematics, a dense graph is a graph in which the number of edges is close to the maximal number of edges. The opposite, a graph with only a few edges, is a sparse graph. The distinction between sparse and dense graphs is rather vague, and depends on the context. [Source: [https://en.wikipedia.org/wiki/Dense_graph](Wikipedia)]

