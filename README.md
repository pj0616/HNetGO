# HNetGO
HNetGO: protein function prediction via heterogeneous network transformer
# Abstract
Protein function annotation is one of the most important research topics for revealing the essence of life at molecular level in the post-genome era. Current research shows that integrating multi-source data can effectively improve the performance of protein function prediction models. However, the heavy reliance on complex feature engineering and model integration methods limits the development of existing methods. In addition, models based on deep learning only uses labeled data in a certain dataset to extract sequence features, thus ignoring a large amount of existing unlabeled sequence data. In this paper, we propose an end-to-end protein function annotation model named HNetGO, which innovatively uses heterogeneous network to integrate protein sequence similarity and PPI network information, and combines the pre-training model to extract the semantic features of the protein sequence. In addition, we design an attention-based graph neural network model, which can effectively extract node-level features from heterogeneous networks, and predict protein function by measuring the similarity between protein nodes and GO term nodes. Comparative experiments on the human dataset show that HNetGO achieves state-of-the-art performance on CCO and MFO branches.
