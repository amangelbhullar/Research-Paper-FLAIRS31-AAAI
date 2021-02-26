# Research-Paper-FLAIRS31-AAAI
WSCAN-TFP: Weighted SCAN Clustering Algorithm for Team Formation Problem in Social Network. FLAIRS Conference 2018: 209-212

# Abstract
In this paper, we provide a novel approach for the Team Formation Problem (TFP) in social networks.With a given social network of experts and communication cost between them, we address the problem of finding a team with a set of required skills necessary to complete a project. An expert of
this network is treated as a node and possesses a given set of skills. The basic idea of the Structural Clustering Algorithm for Networks (SCAN) is to detect clusters, hubs, and outliers in networks. To employ SCAN on TFP, we first find the pool of experts with required skills. Then we search for highly connected (core) expert among all experts network. We expand the cluster from core to neighborhood nodes, and it goes from densely connected to loosely connected nodes within a threshold range of communication cost. We solve this TFP by identifying experts while minimizing communication cost for the project with specific skills. We then measure the communication cost with the sum of a distance function. An enhanced variant of SCAN is the weighted structural clustering algorithm (WSCAN) which is implemented in this paper to solve the TFP with minimum communication cost. Our result with WSCAN performed approximately equal to Greedy algorithms while slightly worse than other Genetic, Cultural and Exact Algorithms. The run-time of WSCAN however, was better compared to the others.

# Reference link
https://dblp.org/pid/219/9005.html
