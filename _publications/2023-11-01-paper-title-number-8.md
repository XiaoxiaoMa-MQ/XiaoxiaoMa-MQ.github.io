---
title: "Heterogeneous Subgraph Transformer for Fake News Detection"
collection: publications
category: manuscripts
permalink: /publication/2023-11-01-paper-title-number-8
excerpt: 'Authors: *Yuchen Zhang, *Xiaoxiao Ma, Jia Wu, Jian Yang, Hao Fan'
date: 2023-11-01
venue: 'WebConf'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3589334.3645680'
citation: ' '
---

Fake news is pervasive on social media, inflicting substantial harm on public discourse and societal well-being. We investigate the explicit structural information and textual features of news pieces by constructing a heterogeneous graph concerning the relations among news topics, entities, and content. Through our study, we reveal that fake news can be effectively detected in terms of the atypical heterogeneous subgraphs centered on them, which encapsulate the essential semantics and intricate relations between news elements. However, suffering from the heterogeneity, exploring such heterogeneous subgraphs remains an open problem. To bridge the gap, this work proposes a heterogeneous subgraph transformer HeteroSGT to exploit subgraphs in our constructed heterogeneous graph. In HeteroSGT, we first employ a pre-trained language model to derive both word-level and sentence-level semantics. Then the random walk with restart (RWR) is applied to extract subgraphs centered on each news, which are further fed to our proposed subgraph Transformer to quantify the authenticity. Extensive experiments on five real-world datasets demonstrate the superior performance of HeteroSGT over five baselines. Further case and ablation studies validate our motivation and demonstrate that performance improvement stems from our specially designed components.