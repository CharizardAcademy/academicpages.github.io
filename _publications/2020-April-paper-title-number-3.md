---
title: "Local Citation Recommendation with Hierarchical-Attention Text Encoder and SciBERT-Based Reranking "
collection: publications
permalink: /publication/2020-April-paper-title-number-3
excerpt: ''
date: 2020-April
venue: '44th European Conference on IR Research, ECIR 2022, Stavanger, Norway, April 10–14, 2022, Proceedings, Part I'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-030-99736-6_19'
citation: 'Gu, Nianlong, Yingqiang Gao, and Richard HR Hahnloser. &quot;Local citation recommendation with hierarchical-attention text encoder and SciBERT-based reranking.&quot; Advances in Information Retrieval: 44th European Conference on IR Research, ECIR 2022, Stavanger, Norway, April 10–14, 2022, Proceedings, Part I. Cham: Springer International Publishing, 2022.'
---
### Abstract

The goal of local citation recommendation is to recommend a missing reference from the local citation context and optionally also from the global context. To balance the tradeoff between speed and accuracy of citation recommendation in the context of a large-scale paper database, a viable approach is to first prefetch a limited number of relevant documents using efficient ranking methods and then to perform a fine-grained reranking using more sophisticated models. In that vein, BM25 has been found to be a tough-to-beat approach to prefetching, which is why recent work has focused mainly on the reranking step. Even so, we explore prefetching with nearest neighbor search among text embeddings constructed by a hierarchical attention network. When coupled with a SciBERT reranker fine-tuned on local citation recommendation tasks, our hierarchical Attention encoder (HAtten) achieves high prefetch recall for a given number of candidates to be reranked. Consequently, our reranker requires fewer prefetch candidates to rerank, yet still achieves state-of-the-art performance on various local citation recommendation datasets such as ACL-200, FullTextPeerRead, RefSeer, and arXiv.

[Download](https://link.springer.com/chapter/10.1007/978-3-030-99736-6_19)