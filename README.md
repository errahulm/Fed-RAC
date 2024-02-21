Federated Learning is a training framework that enables multiple participants to collaboratively train a shared model while preserving data privacy. 
The heterogeneity of devices and networking resources of the participants delay the training and aggregation. The paper introduces a novel approach 
to federated learning by incorporating resource-aware clustering. This method addresses the challenges posed by the diverse devices and networking 
resources among participants. Unlike static clustering approaches, this paper proposes a dynamic method to determine the optimal number of clusters 
using Dunn Indices. It enables adaptability to the varying heterogeneity levels among participants, ensuring a responsive and customized approach to 
clustering. Next, the paper goes beyond empirical observations by providing a mathematical derivation of the communication rounds for convergence 
within each cluster. Further, the participant assignment mechanism adds a layer of sophistication and ensures that devices and networking resources 
are allocated optimally. Afterwards, we incorporate a master-slave technique, particularly through knowledge distillation, which improves the 
performance of lightweight models within clusters. Finally, experiments are conducted to validate the approach and to compare it with state-of-the-art. 
The results demonstrated an accuracy improvement of over 3% compared to its closest competitor and a reduction in communication rounds of around 10%.

This is implementation of Fed-RAC on HAR dataset and can be modified for other datasets.
