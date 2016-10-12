# Module 4: Networks of physical interactions
Welcome to your practical assessment for Module 4 of MIT Big Data and Social Analytics.

Engage with the tutor team in the forums if you get stuck, or if you learn something that you think is useful.
We hope that you enjoy this course, and acquire skills that are of use to you in your personal journey.

## Objective
This module will explore the fundamentals and structure of peer networks, and introduce you to the concepts of network theory and graph clustering.

# Notebook 1: Introduction to NetworkX
> **Notebook goal**: Identify how to represent and manipulate data as a graph object, using NetworkX.

In this notebook, you will be introduced to NetworkX, a Python module for working with graph objects. Using simple examples, you will be shown how to create and visualize graphs.

**List of exercises:**
- **Exercise 1:**
 Create and manipulate NetworkX graphs.

# Notebook 2: Network analysis using NetworkX
> **Notebook goal:** Execute graph analysis with NetworkX, using the "Friends and Family" data set.

You will use the graph objects generated from the data set to evaluate and compare structural properties that can reveal the relationships between the nodes. These properties include the following:
- **Degree centrality:** Identify nodes with most interactions.
- **Closeness and betweenness centrality:** Identify important nodes within a graph, with respect to a specified measure.
- **Eigenvector centrality:** Identify important nodes using a measure of a node that is estimated through transference of that measure from other connected nodes.

You will also start exploring indications of subgraph relationships
by evaluating the tendency of nodes within a graph to form tight-knit groups. In addition, the notebook also engages with the concept of small-world networks, which is used to characterise social networks, power grids, and other networks with unique properties of regional specialization with efficient information transfer. These networks exhibit high clustering coefficients, but have small characteristic path lengths, like random graphs.


**List of exercises:**
- **Exercise 1:** Compute number of call interactions between a pair of nodes.
- **Exercise 2:** Evaluate structure qualitatively in a graph based on visualization.
- **Exercise 3:** Create a graph object using the SMS data set.
- **Exercise [Advanced] 4:** Compare the centrality structural properties evaluated on a graph.
- **Exercise 5:** Describe the effect on the average clustering coefficient when nodes of lower degree are removed.
- **Exercise 6:** List the two criteria of a small-world network.
- **Exercise 7:** Identify small-world networks, given the values for the characteristic path length and clustering coefficient.


# Notebook 3: Finding connected components using  clustering
> **Notebook goal**: Use hierarchical clustering, modularity maximization, and spectral graph partitioning to find connected components.

Community detection is an important task in social network analysis. The idea behind it is to identify groups of people who share a common interest, based on the assumption that these people tend to link to each other more than to the rest of the network. Specifically, real-world networks exhibit clustering behavior that can be observed in the graph representation of these networks by the formation of clusters or partitions. These groups of nodes on a graph (clusters) correspond to communities that share common properties, or have a common role in the system under study.

**List of exercises:**
- **Exercise 1**: Understanding hierarchical clustering.

- **Exercise 2 [Advanced]**: Interpreting the results of hierarchical clustering.

- **Exercise 3 [Advanced]**: Summarizing clustering results based on modularity maximization and spectral graph partitioning.

# Notebook 4: Graph signal processing
> **Notebook goal:** Evaluate graph signal processing.

Graphs not only capture relationship between nodes, but also information about the nodes. The data on these graphs can be visualized as a finite collection of samples, with one sample at each vertex in the graph, and each such sample described by a scalar value. The collection of these scalar samples, defined on each vertex of a graph, is referred to as a graph signal. Graph signal processing is a generalization of the classical signal processing framework in the graph spectral domain.

You will be introduced to this emerging field by reviewing a simple example demonstrating a network of temperature sensors. As such, you will not be required to complete any exercises in this notebook.

<br></br>
**Contributors**:
**Andre Voges**, Mieszko Manijak, **Gorden Jemwa**, Arek Stopczynski, **Xiaowen Dong**, and Yves-Alexandre de Montjoye.
