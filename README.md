# Exploring Graph Neural Architectures

As mentioned in the proposal, our primary goal is to learn about neural architectures used on graph-based data. Text data can be represented as linear graphs. In contrast, images can be described as rectangular graphs. Though ample neural architecture exists that performs well on those graphs, more complicated graph structures require GNNs.

Our project tackles two conceptual problems: first, is there a better way to represent the irregular graph-like structures when it comes to neural architectures, and second, can we create an architecture such that we could "attend" to specific nodes more than the others.

We explore Graph Convolutional Networks (GCNs), a simple graph-based neural architecture with multiple layers. It modifies the node's features based on the adjacency matrix as we go through numerous layers via learn able matrices. Next, we try to answer our second question by building Graph Attention Network (GAT) on top of GCNs to focus on certain edges more, which may or may not help the model. We also visualise the said attention so we can understand the process happening.

Finally, we try to recreate glove embedding for text, to better understand how different structures of languages effect quality of embedding, and how attention interacts with different words given the context. 
