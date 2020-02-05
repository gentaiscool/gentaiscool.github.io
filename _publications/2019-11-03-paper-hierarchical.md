---
title: "Hierarchical Meta-Embeddings for Code-Switching Named Entity Recognition"
collection: publications
status: published
permalink: /publication/2019-11-03-paper-hierarchical
excerpt: ''
date: 2019-11-03
venue: 'EMNLP'
paperurl: ''
authors: 'Genta Indra Winata, Zhaojiang Lin, Jamin Shin, Zihan Liu, Pascale Fung'
citation: ''
code: 'https://github.com/gentaiscool/meta-emb'
paper: 'https://www.aclweb.org/anthology/D19-1360.pdf'
---
In countries that speak multiple main languages, mixing up different languages within a conversation is commonly called code-switching. Previous works addressing this challenge mainly focused on word-level aspects such as word embeddings. However, in many cases, languages share common subwords, especially for closely related languages, but also for languages that are seemingly irrelevant. Therefore, we propose Hierarchical Meta-Embeddings (HME) that learn to combine multiple monolingual word-level and subword-level embeddings to create language-agnostic lexical representations. On the task of Named Entity Recognition for English-Spanish code-switching data, our model achieves the state-of-the-art performance in the multilingual settings. We also show that, in cross-lingual settings, our model not only leverages closely related languages, but also learns from languages with different roots. Finally, we show that combining different subunits are crucial for capturing code-switching entities.