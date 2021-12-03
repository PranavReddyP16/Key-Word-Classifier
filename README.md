# Key-Word-Classifier
Classifies academic keywords under their Domain names

For example, Neural Network would be classified under Deep Learning, and SHA-256 would be classified under Cryptography. This is done by creating a dependency graph out of abstracts from arxiv.org. Nodes are abstracts and edges are present between two abstracts with common keywords. The graphs are then embedded and clustering is performed to group keywords into domain names.

Future Work: Instead of Embeddings, try something like Graph Convolutional Networks.
