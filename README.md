# clustering-low-level-evenlogs-in-Processmining
Abstract


This thesis abstract addresses the use of process mining techniques when event data is stored at varying levels of granularity. While most techniques assume that events have the same level of granularity, real data is often stored differently. Pre-processing techniques allow for appropriate summarization of the data, which simplifies the output while retaining important process details. The goal is to ensure an interpretable output for stakeholders and different business teams without losing critical process points. However, adding new data as a feature to the dataset can be expensive, and at times, infeasible. Therefore, existing data is the only solution.
To overcome this challenge, this study proposes using centrality criteria to create new features for clustering. Centrality criteria is calculated based on the structure and topology of the graph in the early stages of the mining process. Two unsupervised machine learning algorithms, Gaussian mixture, and DBSCAN are employed to cluster the data. By setting the hyperparameters of each clustering algorithm, the study selects the Gaussian mixture algorithm, with a silhouette score of 0.92638, to identify 44 clusters as a map of the appropriate summarized process. The vertex with the highest score is introduced as the representative of the cluster.
This approach effectively simplifies the output while retaining important process details. 

Keywords: 
graph theory, process mining, event log abstraction, unsupervised machine learning algorithms, network theory

![image](https://user-images.githubusercontent.com/113856629/232314267-f77af825-ba42-4b5c-ac80-cd27e33d9c89.png)
![image](https://user-images.githubusercontent.com/113856629/232314298-cbf2083b-41ab-408f-b39f-4f08d4127e49.png)
![image](https://user-images.githubusercontent.com/113856629/232314329-ecf2ff38-d81a-48e0-862b-9f2db5c0804e.png)
This figure generally shows a view of the process of summarizing with the proposed idea. The point is that in summarizing the fine-grained processes, the innovation of this research is that in addition to making the output simpler and more interpretable, the fine-grained activities around the hubs do not disappear in general. In fact, the desired output is the output that does not lose the most important and useful vertices in the process of summarizing the event graph, but also reaches a less complicated graph.
