---
title: "Knowledge Graph Enhanced Heterogeneous Graph Neural Network for Fake News Detection"
collection: publications
category: manuscripts
permalink: /publication/2023-01-01-paper-title-number-5
excerpt: 'Authors: *Bingbing Xie, *Xiaoxiao Ma, Jia Wu, Jian Yang, Hao Fan'
date: 2023-01-01
venue: 'IEEE Transactions on Consumer Electronics'
citation: ' '
---
The rapid proliferation of online fake news has caused confusion and social panic, underscoring the urgency of effective detection. Although tremendous research effort has been devoted to extracting semantic information from news pieces and detecting fake news regarding their linguistic characteristics, the abundant factual information in knowledge graphs (KGs) has yet to be explored. There remain two significant challenges to utilizing KGs for fake news detection: 1) The unknown relation between existing knowledge and news content, and 2) fusing characters of fake news from both KGs and news content inherently requires balancing the contributions of these resources, but no prior domain knowledge is available. Therefore, we propose KEHGNN-FD, a novel KG-enhanced Heterogeneous Graph Neural Network, to unleash the power of KGs for fake news detection. We model news content, topics, and entities as a heterogeneous graph and use graph attention to learn high-level news representations by adaptively aggregating neighboring information from the heterogeneous graph and ground-truth KG entities (i.e., Wikidata). Finally, we train a semi-supervised detector to label news as fake or true. Extensive experiments on four fake news datasets show the superiority of KEHGNN-FD over seven baselines regarding accuracy, precision, recall, F1-score, and ROC. The ablation study further validates the efficacy of the KG for fake news detection as well as KEHGNN-FD’s components.