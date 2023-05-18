# Marketing_Analytics_HW4
## Social Network Analysis for Target Market

This repository showcases the application of social network analysis techniques for identifying influential individuals and communities within a network. By leveraging various network properties and measures such as edge betweenness, density, degree centrality, and community structure, this analysis provides valuable insights for optimizing marketing campaigns and targeting the most influential individuals or communities.

### The code in this repository performs the following tasks:
1. Creation of a directed graph: The provided dataset is used to construct a directed graph representation of the network.
2. Identification of bridge nodes.
3. Calculation of graph density.
4. Analysis of node connections: The nodes with the highest and lowest number of connections are identified.
5. Evaluation of incoming and outgoing connections: The nodes with the highest incoming and outgoing connections are determined.
6. Calculation of centrality measures: Closeness centrality, betweenness centrality, and eigenvector centrality are calculated for nodes, revealing their importance in the network.
7. Community detection: A community detection algorithm is applied to identify distinct communities within the network.
8. Identification of largest and smallest communities.
9. Visualization of top 3 communities: The top three communities are visually represented in separate plots.
10. Removal of influential nodes: The top three nodes with the highest degree centrality, closeness centrality, betweenness centrality, and eigenvector centrality are removed from each community.
11. Visualization of influencers: The influencers within the top three communities are visualized.
12.Action plan design: An action plan is developed, taking into consideration a hypothetical business, marketing budget, cost per action, and target audience selection.

### Dependencies
To run the code succesfully you should have the following libraries installed. You may install them using the pip package manager.
**infomap** 
**pandas**
**numpy**
**matplotlib**
**networkx**
**Infomap**
**from heapq import nlargest, nsmallest**
**from copy import deepcopy**




