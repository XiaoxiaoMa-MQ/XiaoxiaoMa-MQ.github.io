---
title: "Rethinking Unsupervised Graph Anomaly Detection with Deep Learning: Residuals and Objectives"
collection: publications
category: manuscripts
permalink: /publication/2024-12-01-Paper-title-number-13
excerpt: 'Authors: *Xiaoxiao Ma, *Fanzhen Liu, Jia Wu, Jian Yang, Quan Z. Sheng'
date: 2024-12-01
venue: 'IEEE Transactions on Knowledge and Data Engineering'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10756792'
citation: ' '
---

Anomalies often occur in real-world information networks/graphs, such as malevolent users in online review networks and fake news in social media. When representing such structured network data as graphs, anomalies usually appear as anomalous nodes that exhibit significantly deviated structure patterns, or different attributes, or the both. To date, numerous unsupervised methods have been developed to detect anomalies based on residual analysis, which assumes that anomalies will introduce larger residual errors (i.e., graph reconstruction loss). While these existing works achieved encouraging performance, in this paper, we formally prove that their employed learning objectives, i.e., MSE and cross-entropy losses, encounter significant limitations in learning the major data distributions, particularly for anomaly detection, and through our preliminary study, we reveal that the vanilla residual analysis-based methods cannot effectively investigate the rich graph structure. Upon these discoveries, we propose a novel structure-biased graph anomaly detection framework (SALAD) to attain anomalies’ divergent patterns with the assistance of a specially designed node representation augmentation approach. We further present two effective training objectives to empower SALAD to effectively capture the major structure and attribute distributions by emphasizing less on anomalies that introduce higher reconstruction errors under the encoder-decoder framework. The detection performance on eight widely-used datasets demonstrates SALAD's superiority over twelve state-of-the-art baselines. Additional ablation and case studies validate that our data augmentation method and training objectives result in the impressive performance.