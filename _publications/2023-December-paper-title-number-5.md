---
title: "GreedyCAS: Unsupervised Scientific Abstract Segmentation with Normalized Mutual Information"
collection: publications
permalink: /publication/2023-December-paper-title-number-5
excerpt: ''
date: 2023-December
venue: 'Proceedings of the 2023 Conference on Empirical Methods in Natural Language Processing'
paperurl: 'https://aclanthology.org/2023.emnlp-main.372'
citation: 'Yingqiang Gao, Jessica Lam, Nianlong Gu, and Richard Hahnloser. 2023. GreedyCAS: Unsupervised Scientific Abstract Segmentation with Normalized Mutual Information. In Proceedings of the 2023 Conference on Empirical Methods in Natural Language Processing, pages 6093–6108, Singapore. Association for Computational Linguistics.'
---
### Abstract 

The abstracts of scientific papers typically contain both premises (e.g., background and observations) and conclusions. Although conclusion sentences are highlighted in structured abstracts, in non-structured abstracts the concluding information is not explicitly marked, which makes the automatic segmentation of conclusions from scientific abstracts a challenging task. In this work, we explore Normalized Mutual Information (NMI) as a means for abstract segmentation. We consider each abstract as a recurrent cycle of sentences and place two segmentation boundaries by greedily optimizing the NMI score between the two segments, assuming that conclusions are strongly semantically linked with preceding premises. On non-structured abstracts, our proposed unsupervised approach GreedyCAS achieves the best performance across all evaluation metrics; on structured abstracts, GreedyCAS outperforms all baseline methods measured by $P_k$. The strong correlation of NMI to our evaluation metrics reveals the effectiveness of NMI for abstract segmentation.

[Download](https://aclanthology.org/2023.emnlp-main.372.pdf)