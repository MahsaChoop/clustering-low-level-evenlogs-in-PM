# clustering-low-level-evenlogs-in-PM
Abstract


This thesis abstract addresses the use of process mining techniques when event data is stored at varying levels of granularity. While most techniques assume that events have the same level of granularity, real data is often stored differently. Pre-processing techniques allow for appropriate summarization of the data, which simplifies the output while retaining important process details. The goal is to ensure an interpretable output for stakeholders and different business teams without losing critical process points. However, adding new data as a feature to the dataset can be expensive, and at times, infeasible. Therefore, existing data is the only solution.
To overcome this challenge, this study proposes using centrality criteria to create new features for clustering. Centrality criteria is calculated based on the structure and topology of the graph in the early stages of the mining process. Two unsupervised machine learning algorithms, Gaussian mixture, and DBSCAN are employed to cluster the data. By setting the hyperparameters of each clustering algorithm, the study selects the Gaussian mixture algorithm, with a silhouette score of 0.92638, to identify 44 clusters as a map of the appropriate summarized process. The vertex with the highest score is introduced as the representative of the cluster.
This approach effectively simplifies the output while retaining important process details. 

Keywords: 
graph theory, process mining, event log abstraction, unsupervised machine learning algorithms, network theory