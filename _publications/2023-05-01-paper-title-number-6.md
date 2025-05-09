---
title: "Heterogeneous Hypergraph Neural Network for Social Recommendation using Attention Network"
collection: publications
category: manuscripts
permalink: /publication/2023-05-01-paper-title-number-6
excerpt: 'Authors: Bilal Khan, Jia Wu, Jian Yang, Xiaoxiao Ma'
date: 2023-05-01
venue: 'ACM Transactions on Recommender Systems'
citation: ' '
---
Graph neural networks (GNNs) have been used extensively as a backbone for social recommendation. However, their application to a diverse range of situations is still rather limited. This is because graph structures only leverage pairwise user relationships. They cannot capture the higher-order relationships so common in the real world, and ignoring the interest friends and strangers might have in similar items is severely hampering the expressiveness of the current graph-based recommendation models. Hence, in this article, we outline a heterogeneous hypergraph neural network for social recommendation, called Heterogeneous Hypergraph neural network for Social Recommendation using an Attention Network (HHGSA), that incorporates an attention network to address these issues. The hypergraph is able to represent higher-order relationships through five motifs: friend and stranger item appeal, item similarity, user similarity based on interactions with items, and social relations. Two modules, the attentive vertex aggregation module and the attentive hyperedge aggregation module, capture user and item attention. In addition, it has been discovered that similar items have identical appeal when displayed to users. A GNN aggregates the user embedding data, including information about the friend and stranger and item embeddings. Finally, information about users and items is aggregated for social recommendations. Extensive experiments on four datasets demonstrate that the HHGSA model outperforms a wide range of baselines and can significantly improve the accuracy of recommendations.